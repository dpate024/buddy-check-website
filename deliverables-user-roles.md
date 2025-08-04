<!-- HEADER SECTION -->
<div style="background: linear-gradient(to right, #1e5799, #2ecc71); padding: 2rem 1rem; text-align: center; border-radius: 4px 4px 0 0;">
  <h1 style="color: white; margin-bottom: 0.5rem;">User Roles & User Stories</h1>
  <p style="font-size: 1.1rem; color: white; margin-top: 0;">Personalized goals and role-driven engagement for digital well-being</p>
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
      <a href="deliverables-user-roles.html">User Roles & Stories</a>
      <a href="deliverables-ui-mockups.html">UI Mockups</a>
      <a href="deliverables-algorithms.html">Algorithm Flows</a>
    </div>
  </div>
  <a href="glossary.html">Glossary</a>
  <a href="references.html">References</a>
</div>

<!-- MAIN CONTENT -->
<div class="content-card">
  <p>This section outlines the primary user roles Buddy Check is built for, and pairs them with real-world user stories that inspired our features and design. These stories shaped functionality ranging from Air Tanks to Reflection prompts and partner accountability.</p>

  <h3>👤 User</h3>
  <p><strong>Role:</strong> Individuals looking to reduce screen time, set goals, and improve digital wellbeing using reflective, mindful tools.</p>
  <p><strong>User Story:</strong> “As a User, I want to set a personal goal like better sleep so the app can track my progress and offer reflections.”</p>
  
  <h3>🤝 Partner</h3>
  <p><strong>Role:</strong> A trusted friend or family member who offers support and motivation. Partners can be invited to help the user stay accountable.</p>
  <p><strong>User Story:</strong> “As a Partner, I want to join a challenge with my friend so we can both improve our focus and stick to shared goals.”</p>
  
  <h3>👨‍💻 Developer</h3>
  <p><strong>Role:</strong> Maintains and enhances platform functionality. Ensures data sync, Air Tank logic, and reflection algorithms work across platforms.</p>
  <p><strong>User Story:</strong> “As a Developer, I want to log performance stats so we can measure usage trends and fine-tune future features.”</p>

  <h3>🛡️ Admin</h3>
  <p><strong>Role:</strong> Oversees platform-level control like partner moderation, abuse reporting, and backend configuration.</p>
  <p><strong>User Story:</strong> “As an Admin, I want to audit partner history to ensure safety and prevent misuse.”</p>
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
