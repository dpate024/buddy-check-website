---
layout: default
title: Labs
---

<!-- Page Styles -->
<style>
  .project-tagline {
    color: white !important;
    text-shadow: 1px 1px 4px rgba(0,0,0,0.5);
  }
</style>

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
    padding-bottom: 2rem;
  }

  .dropdown-content {
    display: none;
    top: 100%;
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

/* Lab Content */
.lab-container {
  max-width: 900px;
  margin: 2rem auto;
  padding: 2rem;
  background-color: rgba(255, 255, 255, 0.04);
  border-radius: 12px;
  box-shadow: 0 0 15px rgba(0, 255, 255, 0.1);
}

.lab-container h2 {
  text-align: center;
  color: #4dd0e1;
  margin-bottom: 1rem;
}

.lab-container p {
  text-align: center;
  margin-bottom: 1.5rem;
  color: #0de0f0; /* Sharper aqua-blue text */
  font-weight: 500;
}


.lab-container iframe {
  width: 100%;
  height: 800px;
  border: 2px solid #4dd0e1;
  border-radius: 8px;
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

<!-- LAB CONTENT -->
<div class="lab-container">
  <h2>Lab 1 – Outline Document</h2>

  <p>The document below outlines all major lab sessions and technical tasks completed during the development of Buddy Check.</p>

  <iframe src="https://docs.google.com/document/d/e/2PACX-1vSp_vy_aJgktg7NzktndOsbLV8ySU85lN932RJ_QY3gO_2h7J_fRN8bz0Tv6XlVC8BRGzZsina9BeZM/pub?embedded=true"></iframe>
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
