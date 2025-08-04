
<!-- HEADER SECTION -->
<div style="background: linear-gradient(to right, #1e5799, #2ecc71); padding: 2rem 1rem; text-align: center; border-radius: 4px 4px 0 0;">
  <h1 style="color: white; margin-bottom: 0.5rem;">UI Mockups</h1>
  <p style="font-size: 1.1rem; color: white; margin-top: 0;">Final visual layout of Buddy Check’s core screens</p>
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
  <p>The following mockups illustrate key screen designs from Buddy Check, focusing on usability and minimal distraction. These visuals were finalized in Design Iteration 3 and reflect real-time behavior support for users, partners, and reflections.</p>

  <h3>📱 Preview Screens</h3>

  <p><strong>Welcome & Sign-In:</strong> Introduces users to Buddy Check and leads them into personalized setup. Clean layout and branding help the user feel at ease immediately.</p>
  <img src="assets/UI_welcomescreen.png" alt="Welcome and Sign-In Screen" style="width: 100%; border-radius: 12px; box-shadow: 0 0 10px rgba(0,0,0,0.1); margin-bottom: 2rem;">

  <p><strong>Settings, Goals, and App Selection:</strong> Lets users define sleep, productivity, and social wellness targets while configuring Air Tank app limits. Personal control is a core theme here.</p>
  <img src="assets/UI_Settinggoals.png" alt="Settings, Goal Setup, Add App Screens" style="width: 100%; border-radius: 12px; box-shadow: 0 0 10px rgba(0,0,0,0.1); margin-bottom: 2rem;">

  <p><strong>Weekly Reflections & Break Prompts:</strong> Helps users assess their mood and goal success weekly. Also includes an intervention screen when doomscrolling is detected to gently suggest better choices.</p>
  <img src="assets/UI_WeeklyReflection.png" alt="Weekly Reflection & Breathing Break Screens" style="width: 100%; border-radius: 12px; box-shadow: 0 0 10px rgba(0,0,0,0.1); margin-bottom: 2rem;">

  <p><strong>Dashboards & Visual Progress:</strong> Gives users a sense of momentum through daily usage tracking, goal snapshots, and tank availability. Visual charts keep motivation clear and tangible.</p>
  <img src="assets/UI_Dashboard1.png" alt="Dashboard Overview Screens" style="width: 100%; border-radius: 12px; box-shadow: 0 0 10px rgba(0,0,0,0.1); margin-bottom: 2rem;">

  <p><strong>Screen Time Breakdown:</strong> Final screens give insight into individual app usage over time. This reinforces awareness and supports behavior change based on real data.</p>
  <img src="assets/UI_Dashboard2.png" alt="Progress, Usage and Screen Time Stats" style="width: 100%; border-radius: 12px; box-shadow: 0 0 10px rgba(0,0,0,0.1);">
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
