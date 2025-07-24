---
layout: default
title: Glossary
---

<style>
.navbar {
  display: flex;
  gap: 1rem;
  font-weight: bold;
  flex-wrap: wrap;
  justify-content: center;
  padding: 1rem;
  background-color: #f9f9f9;
}

.navbar a, .dropdown > span {
  text-decoration: none;
  color: #0077cc;
  padding: 0.5rem 1rem;
  cursor: pointer;
  transition: background-color 0.2s ease;
  border-radius: 5px;
}

.navbar a:hover, .dropdown:hover > span {
  background-color: #e0f7ff;
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
  border-radius: 5px;
  overflow: hidden;
}

.dropdown-content a {
  color: black;
  padding: 10px 14px;
  display: block;
  text-decoration: none;
}

.dropdown-content a:hover {
  background-color: #f2f2f2;
}

.dropdown:hover .dropdown-content {
  display: block;
}

/* Glossary Style */
.glossary-container {
  max-width: 850px;
  margin: 2rem auto;
  padding: 2rem;
  background-color: rgba(255, 255, 255, 0.04);
  border-radius: 12px;
  box-shadow: 0 0 15px rgba(0, 255, 255, 0.1);
}

.glossary-term {
  margin-bottom: 1.5rem;
  padding: 1rem 1.5rem;
  background-color: #072e40; /* Deep readable background */
  border-left: 4px solid #00e5ff;
  border-radius: 6px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.3);
}

.glossary-term h3 {
  color: #00e5ff;
  font-size: 1.25rem;
  margin-bottom: 0.5rem;
}

.glossary-term p {
  color: #d1f5ff;
  font-size: 1rem;
  line-height: 1.5;
  margin: 0;
}
</style>

<!-- NAVIGATION -->
<div class="navbar">
  <a href="index.html">Home</a>
  <a href="team.html">Team</a>
  <div class="dropdown">
    <span>Presentations ▼</span>
    <div class="dropdown-content">
      <a href="feasibility-draft-1.html">Feasibility Draft 1</a>
      <a href="feasibility-draft-2.html">Feasibility Draft 2</a>
      <a href="feasibility-draft-3.html">Feasibility Draft 3</a>
    </div>
  </div>

  <div class="dropdown">
    <span>Labs ▼</span>
    <div class="dropdown-content">
      <a href="labs.html">Lab 1 Outline</a>
    </div>
  </div>

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

<!-- GLOSSARY CONTENT -->
<div class="glossary-container">

  <div class="glossary-term">
    <h3>Doomscrolling</h3>
    <p>The compulsive consumption of negative news or content, often leading to stress, anxiety, and loss of time.</p>
  </div>

  <div class="glossary-term">
    <h3>Air Tank</h3>
    <p>A time-limited access system in Buddy Check that lets users use social media in bursts, then forces breaks.</p>
  </div>

  <div class="glossary-term">
    <h3>Reflection Prompt</h3>
    <p>A feature that encourages users to pause and consider why they opened an app or how they’re feeling.</p>
  </div>

  <div class="glossary-term">
    <h3>Quiet Hours</h3>
    <p>Scheduled times where social media is blocked or limited to support better sleep and focus.</p>
  </div>

  <div class="glossary-term">
    <h3>Mindful Scrolling</h3>
    <p>The conscious act of using social platforms with intention, avoiding rabbit holes and passive usage.</p>
  </div>

  <div class="glossary-term">
    <h3>Weekly Summary</h3>
    <p>A feature that provides users with a report of their screen usage and prompts them to reflect on their behavior.</p>
  </div>

  <div class="glossary-term">
    <h3>System Flow</h3>
    <p>The underlying decision logic that powers how Buddy Check enforces restrictions and interacts with the user during app usage.</p>
  </div>

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
