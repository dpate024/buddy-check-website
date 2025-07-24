---
layout: default
title: Overview
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
  }<!-- HEADER SECTION -->
<div style="background: linear-gradient(to right, #1e5799, #2ecc71); padding: 2rem 1rem; text-align: center; border-radius: 4px 4px 0 0;">
  <h1 style="color: white; margin-bottom: 0.5rem;">Buddy Check – Before the Doom Scroll</h1>
  <p style="font-size: 1.1rem; color: white; margin-top: 0;">Helping people reclaim time by interrupting doomscrolling habits.</p>
</div>

<style>
.navbar {
  display: flex;
  align-items: center;
  justify-content: flex-start;    
  flex-wrap: nowrap;
  background-color: #0d1b2a;
  padding: 1rem 2.5rem;           
  font-size: 1rem;
                    
}

.navbar a, .dropdown > span {
  color: #ffffff;
  text-decoration: none;
  padding: 0.6rem 1rem;
  border-radius: 5px;
  font-weight: bold;
  white-space: nowrap;
}

.navbar a:hover, .dropdown:hover > span {
  background-color: #1e5799;
}

.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: white;
  min-width: 200px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.15);
  z-index: 10;
  border-radius: 6px;
}

.dropdown-content a {
  color: black;
  padding: 10px 14px;
  display: block;
  text-decoration: none;
}

.dropdown:hover .dropdown-content {
  display: block;
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

 


  /* Footer */
  .footer {
    background-color: #0d1b2a;
    color: #e0e0e0;
    padding: 1rem 2rem;
    text-align: center;
    font-size: 0.9rem;
    margin-top: 3rem;
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

## Problem Statement
Despite widespread awareness of the negative impacts of excessive screen use on productivity, mental health, and sleep, most people still struggle to implement lasting behavioral changes.
The convenience and design of modern digital platforms promote habitual doomscrolling, making it difficult for individuals to break the cycle without external support or intentional intervention.

## Problem Characteristics
- Impulse behavior
- Infinite scroll
- 24/7 access
- Low awareness

## Solution Statement
Buddy Check is a multi-platform, behavioral tool designed to help people build healthier screen habits without giving up social media entirely.
It introduces features like time-limited access ("Air Tanks"), Quiet Hours, and reflective prompts that encourage mindful scrolling, reduce impulsivity, and give users more control over their time.

## Solution Characteristics
- Air Tank system
- Weekly reflections
- Quiet Hours
- Settings delay
- Breathing Breaks

<!-- FOOTER -->
<div class="footer">
  © 2025 Buddy Check Project · Designed by CS 410 Team at ODU
</div>


<hr />
<footer style="text-align: center; font-size: 0.9rem; padding: 1rem 0; color: #444;">
  <a href="https://www.odu.edu/" target="_blank">Old Dominion University</a> |
  <a href="https://www.odu.edu/computer-science" target="_blank">ODU Computer Science Department</a>
</footer>


