---
layout: default
title: Risk Matrix
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



# ⚠️ Risk Matrices

Buddy Check faces a variety of risks in its development and deployment. These are categorized into three main areas:

---

## 🔒 Security Risk Matrix

These risks deal with data privacy and user trust.

- **S1**: The app may request more permissions than needed, causing users to worry about surveillance or data misuse.  
  → *Mitigation*: Clearly disclose permissions and limit requests to only what’s essential.

- **S2**: There's a risk of user tracking data being misused or sold.  
  → *Mitigation*: Implement full encryption and store data locally or in a user-controlled environment.

<img src="assets/security-risk.png" alt="Security Risk Matrix"
     style="width: 100%; max-width: 600px; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); margin: 1rem 0;" />


---

## 👥 Customer Risk Matrix

These risks relate to user engagement and satisfaction.

- **C1**: Users might ignore or dismiss check-in prompts.  
  → *Mitigation*: Make reminders customizable and friendly.

- **C2**: Weekly reflections could feel judgmental or stressful.  
  → *Mitigation*: Design feedback with supportive, motivational language.

- **C3**: The app may be too complex for older or non-technical users.  
  → *Mitigation*: Use simple onboarding, default settings, and tutorials.

- **C4**: Some users might uninstall Buddy Check too soon.  
  → *Mitigation*: Encourage gradual behavior change and celebrate small wins.

<img src="assets/customer-risk.png" alt="Customer Risk Matrix"
     style="width: 100%; max-width: 600px; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); margin: 1rem 0;" />


---

## 🛠️ Technical Risk Matrix

These focus on development challenges and platform issues.

- **T1**: Syncing data across platforms (iOS, Android, PC) could be difficult.  
  → *Mitigation*: Use a centralized cloud database and device-specific tokens.

- **T2**: Platform APIs may complicate features like settings delay.  
  → *Mitigation*: Break down the logic by OS and stagger implementation.

- **T3**: Bugs in timers or logic could affect app reliability.  
  → *Mitigation*: Write automated unit tests and conduct QA regularly.

- **T4**: App store approvals may delay launch.  
  → *Mitigation*: Prepare early and follow guidelines for each store.

<img src="assets/technical-risk.png" alt="Technical Risk Matrix"
     style="width: 100%; max-width: 600px; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); margin: 1rem 0;" />


<!-- FOOTER -->
<div class="footer">
  © 2025 Buddy Check Project · Designed by CS 410 Team at ODU
</div>


<hr />
<footer style="text-align: center; font-size: 0.9rem; padding: 1rem 0; color: #444;">
  <a href="https://www.odu.edu/" target="_blank">Old Dominion University</a> |
  <a href="https://www.odu.edu/computer-science" target="_blank">ODU Computer Science Department</a>
</footer>
