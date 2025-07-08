---
layout: default
title: Major Functional Components
---

<div style="background: linear-gradient(to right, #1e5799, #2ecc71); padding: 2rem 1rem; text-align: center; border-radius: 4px 4px 0 0;">
  <h1 style="color: white; margin-bottom: 0.5rem;">Buddy Check – Before the Doom Scroll</h1>
  <p style="font-size: 1.1rem; color: white; margin-top: 0;">Helping people reclaim time by interrupting doomscrolling habits.</p>
</div>

<style>
.navbar {
  display: flex;
  gap: 1rem;
  font-weight: bold;
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
  z-index: 1;
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
</style>

<div class="navbar">
  <a href="index.html">Home</a>
  <a href="team.html">Team</a>
  <a href="presentations.html">Presentations</a>

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
</div>


## Major Functional Component Diagram

# 🧩 Major Functional Component Diagram

This diagram shows how the front-end, back-end, and database interact in Buddy Check.

<img src="assets/mfcd.png" alt="MFCD Diagram"
     style="width: 100%; max-width: 600px; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); margin: 1rem 0;" />

- **Front-End**: React Native
- **Back-End**: Node.js
- **Database**: MySQL
- **Cloud**: AWS / Google Cloud
