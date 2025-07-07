---
layout: default
title: Buddy Check
---

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

# Buddy Check

Welcome to **Buddy Check** — a CS 410/411W project focused on reducing screen addiction through mindful app usage and user reflection.

Explore our pages to learn more about the problem, our proposed solution, and the team behind it.
