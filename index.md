---
layout: default
title: Buddy Check
---

<style>
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  margin: 0;
  padding: 0;
}

.navbar {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  background-color: #f2f2f2;
  padding: 1rem 2rem;
  font-weight: bold;
  justify-content: center;
}

.navbar a,
.dropdown > span {
  text-decoration: none;
  color: #333;
  padding: 0.5rem 1rem;
  transition: background-color 0.2s ease;
}

.navbar a:hover,
.dropdown:hover > span {
  background-color: #e0e0e0;
  border-radius: 5px;
}

.dropdown {
  position: relative;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: white;
  min-width: 200px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.15);
  z-index: 1;
}

.dropdown-content a {
  display: block;
  padding: 10px 14px;
  color: black;
  text-decoration: none;
}

.dropdown:hover .dropdown-content {
  display: block;
}

/* Hero Section */
.hero {
  background-color: #e6f2ff;
  padding: 3rem 2rem;
  text-align: center;
}

.hero h1 {
  font-size: 2.5rem;
  margin-bottom: 0.5rem;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 1.5rem;
}

.button {
  background-color: #007acc;
  color: white;
  padding: 0.8rem 1.4rem;
  text-decoration: none;
  border-radius: 5px;
  font-weight: bold;
}

.button:hover {
  background-color: #005c99;
}

/* Content */
.content {
  max-width: 900px;
  margin: 2rem auto;
  padding: 0 1rem;
}

h2 {
  margin-top: 2rem;
  color: #333;
}

ul {
  padding-left: 1.5rem;
}

@media screen and (max-width: 600px) {
  .hero h1 {
    font-size: 2rem;
  }

  .navbar {
    flex-direction: column;
    align-items: center;
  }

  .dropdown-content {
    position: static;
  }
}
</style>

<!-- NAVIGATION -->
<div class="navbar">
  <a href="index.html">Home</a>
  <a href="team.html">Team</a>
  <a href="presentations.html">Presentations</a>
  <a href="labs.html">Labs</a>

  <div class="dropdown">
    <span style="cursor:pointer;">Deliverables ▼</span>
    <div class="dropdown-content">
      <a href="deliverables-overview.html">Overview</a>
      <a href="deliverables-process-flow.html">Process Flow</a>
      <a href="deliverables-mfcd.html">MFCD</a>
      <a href="deliverables-risk-matrix.html">Risk Matrix</a>
      <a href="deliverables-competition.html">Competition</a>
    </div>
  </div>

  <a href="glossary.html">Glossary</a>
  <a href="references.html">References</a>
</div>

<!-- HERO SECTION -->
<div class="hero">
  <h1>Welcome to Buddy Check</h1>
  <p>Reduce doomscrolling. Boost well-being. Reclaim your time.</p>
  <a href="features.html" class="button">Explore Features</a>
</div>

<!-- MAIN CONTENT -->
<div class="content">
  <h2>🔍 Problem Statement</h2>
  <p>Despite widespread awareness of the negative impacts of excessive screen use on productivity, mental health, and sleep, most people still struggle to implement lasting behavioral changes. The convenience and design of modern digital platforms promote <strong>habitual doomscrolling</strong>, making it difficult for individuals to break the cycle without external support or intentional intervention.</p>

  <h2>⚠️ Problem Characteristics</h2>
  <ul>
    <li>🤯 <strong>Impulse Behavior</strong> – Users open apps reflexively during idle moments.</li>
    <li>⏰ <strong>No Pauses</strong> – Infinite scroll and autoplay eliminate natural breaks.</li>
    <li>💤 <strong>No Quiet Time</strong> – Apps and notifications are available 24/7, disrupting rest.</li>
    <li>⚙️ <strong>Instant Changes</strong> – Restrictions can be easily disabled during temptation.</li>
    <li>📉 <strong>Low Awareness</strong> – Most users don’t reflect on or track their screen time.</li>
  </ul>

  <h2>💡 Solution Statement</h2>
  <p><strong>Buddy Check</strong> is a multi-platform, behavioral tool designed to help people <strong>build healthier screen habits</strong> without giving up social media entirely. It introduces features like time-limited access ("Air Tanks"), Quiet Hours, and reflective prompts that encourage mindful scrolling, reduce impulsivity, and give users more control over their time.</p>

  <h2>✅ Solution Characteristics</h2>
  <ul>
    <li>🧠 <strong>Mindful Scrolling</strong> – Interrupts automatic behavior and supports intentional use.</li>
    <li>⏳ <strong>Time Management</strong> – Helps users reclaim time for hobbies, focus, and sleep.</li>
    <li>❤️ <strong>Overall Health</strong> – Supports better mood, energy, and self-regulation through improved screen habits.</li>
  </ul>
</div>

<hr />
<footer style="text-align: center; font-size: 0.9rem; padding: 1rem 0; color: #444;">
  <a href="https://www.odu.edu/" target="_blank">Old Dominion University</a> |
  <a href="https://www.odu.edu/computer-science" target="_blank">ODU Computer Science Department</a>
</footer>
