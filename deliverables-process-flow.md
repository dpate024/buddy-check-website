---
layout: default
title: Solution Process Flow
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


# 🔁 Buddy Check Process Flows

## 🔄 Process Flow – The Doomscrolling Loop

Even with the best intentions, many people fall into the same destructive pattern when using social media. This flow illustrates the unconscious loop of doomscrolling — from a moment of boredom to guilt and burnout.

Without tools in place to interrupt or reflect, this cycle repeats daily, chipping away at productivity, well-being, and emotional energy.

> Buddy Check is designed specifically to **break this loop** by introducing intentional steps, prompts, and friction at just the right moments.

<img src="assets/process-flow.png" alt="The Doomscrolling Loop Process Flow"
     style="width: 100%; max-width: 650px; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.15); margin: 1rem 0;" />


---


## 📅 Daily Solution Flow – Using Buddy Check Day-to-Day

The daily process begins when a user opens a listed app or website:

1. **Air Tank Prompt**: A pop-up appears asking if they want to use one of their limited daily “air tanks” to begin a scrolling session.
2. **Optional Timer**: If desired, the user can set a countdown timer. This adds structure and limits impulsive overuse.
3. **Session Begins**: Scrolling is allowed as normal.
4. **Breathing Breaks**: After a prolonged session, a gentle pop-up reminds the user to pause and reflect.
5. **Session Ends**: When the app is closed or time expires, the tank is marked as used. If all tanks are used for the day, access is blocked.

> This daily loop creates intentional moments of decision and breaks the unconscious doomscrolling habit.

<img src="assets/solution-daily-flow-2.0.png" alt="Daily Flow Diagram"
     style="width: 100%; max-width: 600px; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); margin: 1rem 0;" />

---

## 📈 Weekly Solution Flow – Reflecting and Adjusting

At the end of each week, the app initiates a user reflection process:

1. **Usage Stats**: Screen time and scrolling activity from the past 7 days is displayed.
2. **Reflection Prompt**: The user is asked to consider how satisfied they are with their usage.
3. **Adjustments**: Suggestions are made (e.g., add/remove apps from the restricted list).
4. **Goal Reminders**: The app reminds the user why they wanted to change their habits in the first place.

> Weekly reflections keep personal goals front and center, helping users develop a more mindful relationship with technology over time.

<img src="assets/solution-weekly-flow-2.0.png" alt="Weekly Flow Diagram"

<!-- FOOTER -->
<div class="footer">
  © 2025 Buddy Check Project · Designed by CS 410 Team at ODU
</div>


<hr />
<footer style="text-align: center; font-size: 0.9rem; padding: 1rem 0; color: #444;">
  <a href="https://www.odu.edu/" target="_blank">Old Dominion University</a> |
  <a href="https://www.odu.edu/computer-science" target="_blank">ODU Computer Science Department</a>
</footer>
     style="width: 100%; max-width: 600px; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); margin: 1rem 0;" />
