<!-- HEADER SECTION -->
<div style="background: linear-gradient(to right, #1e5799, #2ecc71); padding: 2rem 1rem; text-align: center; border-radius: 4px 4px 0 0;">
  <h1 style="color: white; margin-bottom: 0.5rem;">Algorithm Flows</h1>
  <p style="font-size: 1.1rem; color: white; margin-top: 0;">Logic behind Air Tanks, Reflections, and Quiet Hours</p>
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
  <p>This section explains the core logic and behavior behind Buddy Check’s interactive features. These flows are based on Design Iteration 3 and ensure timely intervention and personalized guidance.</p>

  <p>The following diagrams outline the logic behind Buddy Check's behavior systems. These algorithms guide user interaction with blocking, initialization, and reflection features across different phases of the experience.</p>

  <h3>⚙️ Initialization Algorithm</h3>
  <p>This setup flow walks the user through the Buddy Check onboarding experience. It includes app introduction, goal setting, and adjusting default behavior before they begin using the platform.</p>
  <img src="assets/Initialization_Algoritm.png" alt="Initialization Algorithm" style="max-width: 100%; border-radius: 10px; margin-bottom: 2rem;">

  <h3>🚫 Blocking Algorithm</h3>
  <p>This logic controls when access to apps or sites should be limited. Based on time of day, user settings, and Air Tank availability, the system determines whether to allow or block app usage.</p>
  <img src="assets/Blocking_Algoritm.png" alt="Blocking Algorithm" style="max-width: 100%; border-radius: 10px; margin-bottom: 2rem;">

  <h3>📈 Feedback Algorithm</h3>
  <p>This reflection-based algorithm compiles user stats, checks for progress and behavior patterns, and prompts the user to reflect and update their goals accordingly.</p>
  <img src="assets/Feedback_Algorithm.png" alt="Feedback Algorithm" style="max-width: 100%; border-radius: 10px; margin-bottom: 2rem;">

  <h3>🔁 Overview Summary</h3>
  <p>This diagram gives a simplified view of how the three major algorithm systems interact across Buddy Check's architecture.</p>
  <img src="assets/Algoritm.png" alt="Overall Algorithm Structure" style="max-width: 100%; border-radius: 10px;">
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
