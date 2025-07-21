---
layout: default
title: Feasibility Draft 3
---

<style>
  body {
    background-color: #011f3f;
    color: #e0f7fa;
    font-family: "Segoe UI", "Helvetica Neue", Arial, sans-serif;
    margin: 0;
    padding: 0;
  }

  .navbar {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    background-color: #001a33;
    padding: 1rem 2rem;
    gap: 1.2rem;
    font-weight: 600;
  }

  .navbar a,
  .dropdown > span {
    text-decoration: none;
    color: #4dd0e1;
    padding: 0.5rem 1rem;
    transition: background-color 0.2s ease;
    border-radius: 5px;
    cursor: pointer;
  }

  .navbar a:hover,
  .dropdown:hover > span {
    background-color: #004466;
  }

  .dropdown {
    position: relative;
  }

  .dropdown-content {
    display: none;
    position: absolute;
    background-color: #002b4d;
    min-width: 180px;
    box-shadow: 0 4px 8px rgba(0, 255, 255, 0.1);
    z-index: 1000;
    top: 2.5rem;
    border-radius: 5px;
    overflow: hidden;
  }

  .dropdown-content a {
    display: block;
    padding: 0.75rem 1rem;
    color: #e0f7fa;
    text-decoration: none;
  }

  .dropdown-content a:hover {
    background-color: #00334d;
  }

  .dropdown:hover .dropdown-content {
    display: block;
  }

  .hero {
    background: linear-gradient(to right, #1e5799, #2ecc71);
    padding: 2rem 1rem;
    text-align: center;
    border-radius: 0 0 10px 10px;
  }

  .hero h1 {
    color: white;
    margin-bottom: 0.5rem;
  }

  .hero p {
    font-size: 1.1rem;
    color: white;
    margin-top: 0;
  }

  .content {
    max-width: 900px;
    margin: 2rem auto;
    padding: 0 1.2rem;
    line-height: 1.7;
  }

  .footer {
    background-color: #0d1b2a;
    color: #e0e0e0;
    padding: 1rem 2rem;
    text-align: center;
    font-size: 0.9rem;
    margin-top: 3rem;
  }

  @media screen and (max-width: 600px) {
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

<!-- NAVIGATION BAR -->
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

<!-- HERO HEADER -->
<div class="hero">
  <h1>Feasibility Draft 3</h1>
  <p>Third feasibility analysis of the Buddy Check project.</p>
</div>

<!-- MAIN CONTENT -->
<div class="content">
  <p><iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSgzp4TivxkPStypFs6mAwGD2mcbpAdXUv0kZvxajRKe6Z991n18MYyL-oCXFqqLC0MaMzDY0hWNTx-/pubembed?start=true&loop=true&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe></p>
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

