---
layout: default
title: Buddy Check
---

<!-- Page Styles -->
<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    background-color: #ffffff;
    color: #333;
  }

  /* Navigation Bar */
  .navbar {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    background-color: #f9f9f9;
    padding: 1rem 2rem;
    box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    gap: 1.2rem;
    font-weight: 600;
  }

  .navbar a, .dropdown > span {
    text-decoration: none;
    color: #0077cc;
    padding: 0.5rem 1rem;
    transition: background-color 0.2s ease;
    border-radius: 5px;
    cursor: pointer;
  }

  .navbar a:hover, .dropdown:hover > span {
    background-color: #e6f2ff;
  }

  .dropdown {
    position: relative;
  }

  .dropdown-content {
    display: none;
    position: absolute;
    background-color: white;
    min-width: 180px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    z-index: 1000;
    top: 2.5rem;
    border-radius: 5px;
    overflow: hidden;
  }

  .dropdown-content a {
    display: block;
    padding: 0.75rem 1rem;
    color: #333;
    text-decoration: none;
  }

  .dropdown-content a:hover {
    background-color: #f0f8ff;
  }

  .dropdown:hover .dropdown-content {
    display: block;
  }

  /* Hero Section */
  .hero {
    background: linear-gradient(to right, #d6f0ff, #f3faff);
    padding: 4rem 2rem;
    text-align: center;
  }

  .hero h1 {
    font-size: 2.8rem;
    margin-bottom: 1rem;
    color: #005c99;
  }

  .hero p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
  }

  .button {
    display: inline-block;
    background-color: #007acc;
    color: white;
    padding: 0.9rem 1.5rem;
    border-radius: 6px;
    text-decoration: none;
    font-weight: bold;
    transition: background 0.3s ease;
  }

  .button:hover {
    background-color: #005c99;
  }

  /* Content Section */
  .content {
    max-width: 900px;
    margin: 2rem auto;
    padding: 0 1.2rem;
  }

  h2 {
    color: #005c99;
    margin-top: 2rem;
  }

  ul {
    list-style: none;
    padding-left: 0;
  }

  ul li {
    margin-bottom: 0.8rem;
    padding-left: 1.2rem;
    position: relative;
  }

  ul li::before {
    content: "•";
    color: #007acc;
    font-weight: bold;
    position: absolute;
    left: 0;
  }

  /* Footer */
  .footer {
    background-color: #0d1b2a;
    color: #e0e0e0;
    padding: 1rem 2rem;
    text-align: center;
    font-size: 0.9rem;
    margin-top: 3rem;
  }

  @media screen and (max-width: 600px) {
    .hero h1 {
      font-size: 2rem;
    }

    .navbar {
      flex-direction: column;
      gap: 0.5rem;
    }

    .dropdown-content {
      position: static;
      box-shadow: none;
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
    <span>Deliverables ▼</span>
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
  <p>
    Despite widespread awareness of the negative impacts of excessive screen use on productivity, mental health, and sleep, most people still struggle to implement lasting behavioral changes.
    The convenience and design of modern digital platforms promote <strong>habitual doomscrolling</strong>, making it difficult for individuals to break the cycle without external support or intentional intervention.
  </p>

  <h2>⚠️ Problem Characteristics</h2>
  <ul>
    <li>🤯 <strong>Impulse Behavior</strong> – Users open apps reflexively during idle moments.</li>
    <li>⏰ <strong>No Pauses</strong> – Infinite scroll and autoplay eliminate natural breaks.</li>
    <li>💤 <strong>No Quiet Time</strong> – Apps and notifications are available 24/7, disrupting rest.</li>
    <li>⚙️ <strong>Instant Changes</strong> – Restrictions can be easily disabled during temptation.</li>
    <li>📉 <strong>Low Awareness</strong> – Most users don’t reflect on or track their screen time.</li>
  </ul>

  <h2>💡 Solution Statement</h2>
  <p>
    <strong>Buddy Check</strong> is a multi-platform, behavioral tool designed to help people <strong>build healthier screen habits</strong> without giving up social media entirely.
    It introduces features like time-limited access ("Air Tanks"), Quiet Hours, and reflective prompts that encourage mindful scrolling, reduce impulsivity, and give users more control over their time.
  </p>

  <h2>✅ Solution Characteristics</h2>
  <ul>
    <li>🧠 <strong>Mindful Scrolling</strong> – Interrupts automatic behavior and supports intentional use.</li>
    <li>⏳ <strong>Time Management</strong> – Helps users reclaim time for hobbies, focus, and sleep.</li>
    <li>❤️ <strong>Overall Health</strong> – Supports better mood, energy, and self-regulation through improved screen habits.</li>
  </ul>
</div>

<!-- FOOTER -->
<div class="footer">
  © 2025 Buddy Check Project · Designed by CS 410 Team at ODU
</div>


<hr />
<footer style="text-align: center; font-size: 0.9rem; padding: 1rem 0; color: #444;">
  <a href="https://www.odu.edu/" target="_blank">Old Dominion University</a> |
  <a href="https://www.odu.edu/computer-science" target="_blank">ODU Computer Science Department</a>
</footer>
