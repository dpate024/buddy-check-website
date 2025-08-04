<!-- HEADER SECTION -->
<div style="background: linear-gradient(to right, #1e5799, #2ecc71); padding: 2rem 1rem; text-align: center; border-radius: 4px 4px 0 0;">
  <h1 style="color: white; margin-bottom: 0.5rem;">Risk Matrix</h1>
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
      <a href="design-draft-1.html">Design Draft 1</a>
      <a href="design-draft-2.html">Design Draft 2</a>
      <a href="design-draft-3.html">Design Draft 3</a>
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
