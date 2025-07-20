---
layout: default
title: Risk Matrix
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
<div class="navbar">
  <a href="glossary.html">Glossary</a>
  <a href="references.html">References</a>
 </div>
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

