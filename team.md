---
layout: default
title: Meet the Team
---

<!-- Hero Banner -->
<div style="background: linear-gradient(to right, #006064, #00acc1); padding: 3rem 1rem; text-align: center; color: white; border-radius: 0 0 12px 12px;">
  <h1 style="margin-bottom: 0.5rem;">Buddy Check – Before the Doom Scroll</h1>
  <p style="font-size: 1.1rem;">Helping people reclaim time by interrupting doomscrolling habits.</p>
</div>

<!-- Navigation -->
<style>
.navbar {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  justify-content: center;
  padding: 1rem;
  background-color: #002b36;
  font-weight: bold;
}

.navbar a, .dropdown span {
  color: #e0f7fa;
  text-decoration: none;
  padding: 8px 12px;
  cursor: pointer;
}

.navbar a:hover, .dropdown span:hover {
  background-color: #004d4d;
  border-radius: 4px;
}

.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #004d4d;
  min-width: 200px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.3);
  z-index: 1;
}

.dropdown-content a {
  color: white;
  padding: 10px 14px;
  display: block;
  text-decoration: none;
}

.dropdown-content a:hover {
  background-color: #006666;
}

.dropdown:hover .dropdown-content {
  display: block;
}
</style>

<div class="navbar">
  <a href="index.html">Home</a>
  <a href="team.html">Team</a>
  <a href="presentations.html">Presentations</a>
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

<!-- Team Card Styling -->
<style>
.team-section {
  max-width: 1000px;
  margin: 3rem auto;
  padding: 0 1rem;
}

.member {
  display: flex;
  flex-wrap: wrap;
  gap: 1.5rem;
  margin-bottom: 2.5rem;
  background: rgba(255,255,255,0.03);
  border-radius: 12px;
  padding: 1.5rem;
  box-shadow: 0 2px 6px rgba(0,255,255,0.08);
}

.member img {
  width: 160px;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.2);
}

.member h3 {
  margin-top: 0;
  color: #4dd0e1;
}

.member p {
  margin-top: 0.5rem;
  color: #e0f7fa;
  line-height: 1.6;
}

@media (max-width: 700px) {
  .member {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  .member img {
    margin-bottom: 1rem;
  }
}
</style>

<!-- Team Section -->
<div class="team-section">

<div class="member">
  <img src="assets/NicholasBrewster.jpg" alt="Nicholas Brewster" />
  <div>
    <h3>Nicholas Brewster</h3>
    <p>Nicholas is a senior at Old Dominion University majoring in computer science and plans to graduate in Spring 2026. He earned his Associate of Science from Tidewater Community College with Magna Cum Laude honors. He aims to become a software engineer. In his free time, he enjoys gaming and spending time with his cat, Ollie.</p>
  </div>
</div>

<div class="member">
  <img src="assets/daksh.jpg" alt="Daksh Patel" />
  <div>
    <h3>Daksh Patel</h3>
    <p>Daksh is a Computer Science student at ODU graduating in December 2025. With a prior degree in Computer Engineering from Canada, he's the technical lead for Buddy Check. His strengths lie in Java, front-end design, and UI/UX. He's passionate about building tools that encourage healthy digital habits.</p>
  </div>
</div>

<div class="member">
  <img src="assets/Balemual.jpg" alt="Balemual Ymamu" />
  <div>
    <h3>Balemual Ymamu</h3>
    <p>Balemual is a senior at ODU majoring in CS with a cybersecurity minor, set to graduate in Fall 2025. He earned an Associate of Science from Tidewater Community College. He's passionate about software engineering and enjoys soccer and socializing in his spare time.</p>
  </div>
</div>

<div class="member">
  <img src="assets/AugustineKpewa.jpg" alt="Augustine Kpewa" />
  <div>
    <h3>Augustine Kpewa</h3>
    <p>Augustine is a CS senior at ODU, graduating in Fall 2025. He holds an Associate Degree in CS from Northern Virginia Community College. He's proficient in Java, Python, C++, and web development. Outside of class, he enjoys soccer and fitness.</p>
  </div>
</div>

<div class="member">
  <img src="assets/DustinDobson.jpg" alt="Dustin Melton-Dobson" />
  <div>
    <h3>Dustin Melton-Dobson</h3>
    <p>Dustin is a CS senior at ODU with an associate degree in CS from NOVA. He’s skilled in Java and has working knowledge of Python, C++, and HTML. He enjoys golf and walking his dog in his free time.</p>
  </div>
</div>

</div>

<!-- Footer -->
<div style="background-color: #0d1b2a; color: #e0e0e0; padding: 1rem 2rem; text-align: center; font-size: 0.9rem; margin-top: 3rem;">
  © 2025 Buddy Check Project · Designed by CS 410 Team at ODU
</div>

<footer style="text-align: center; font-size: 0.9rem; padding: 1rem 0; color: #444;">
  <a href="https://www.odu.edu/" target="_blank">Old Dominion University</a> |
  <a href="https://www.odu.edu/computer-science" target="_blank">ODU Computer Science Department</a>
</footer>
