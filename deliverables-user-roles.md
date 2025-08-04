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
    </div>
  </div>
  <a href="glossary.html">Glossary</a>
  <a href="references.html">References</a>
</div>

<!-- MAIN CONTENT -->
<div class="content-card">
  <p>This deliverable outlines the core roles and user stories driving the Buddy Check experience. It reflects feedback and insights developed through Design Iteration 3.</p>

  <h3>👤 User Roles</h3>
  <ul>
    <li><strong>User:</strong> Sets personal goals and receives behavior-based guidance and reflection prompts.</li>
    <li><strong>Partner:</strong> Supports another user by tracking weekly updates, offering encouragement, and joining shared goals.</li>
    <li><strong>Developer:</strong> Manages backend logic, data tracking, and user input handling.</li>
    <li><strong>Admin:</strong> Oversees platform policies, onboarding, and partner moderation.</li>
  </ul>

  <h3>📝 Sample User Stories</h3>
  <ul>
    <li>As a User, I want to set a sleep goal so the app can suggest better usage patterns and reflection prompts.</li>
    <li>As a Partner, I want to join a group challenge so I can build healthier habits with friends.</li>
    <li>As a Developer, I want clear weekly metrics so I can evaluate feature effectiveness.</li>
  </ul>
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
