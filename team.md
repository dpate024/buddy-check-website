
<!-- HEADER SECTION -->
<div style="background: linear-gradient(to right, #1e5799, #2ecc71); padding: 2rem 1rem; text-align: center; border-radius: 4px 4px 0 0;">
  <h1 style="color: white; margin-bottom: 0.5rem;">Meet the Team</h1>
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
<!-- Team Members Section -->
<style>
.team-section {
  max-width: 1100px;
  margin: 3rem auto;
  padding: 0 1rem;
}

.member {
  display: flex;
  align-items: center;
  gap: 1.5rem;
  margin-bottom: 2.5rem;
  background: #e0f7fa;
  border-left: 6px solid #00bcd4;
  padding: 1.5rem;
  border-radius: 8px;
}

.member img {
  width: 150px;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.2);
}

.member h3 {
  margin: 0;
  color: #007c91;
}

.member p {
  margin-top: 0.5rem;
  color: #004d4d;
  line-height: 1.6;
}

@media (max-width: 700px) {
  .member {
    flex-direction: column;
    text-align: center;
  }
  .member img {
    margin-bottom: 1rem;
  }
}
</style>

<div class="team-section">
  <div class="member">
    <img src="assets/NicholasBrewster.jpg" alt="Nicholas Brewster">
    <div>
      <h3>Nicholas Brewster</h3>
      <p>Nicholas is a senior at Old Dominion University majoring in computer science and plans to graduate in Spring 2026. He earned his Associate of Science from Tidewater Community College with Magna Cum Laude honors. He aims to become a software engineer. In his free time, he enjoys gaming and spending time with his cat, Ollie.</p>
    </div>
  </div>

  <div class="member">
    <img src="assets/daksh.jpg" alt="Daksh Patel">
    <div>
      <h3>Daksh Patel</h3>
      <p>Daksh is a Computer Science student at ODU graduating in December 2025. With a prior degree in Computer Engineering from Canada, he's the technical lead for Buddy Check. His strengths lie in Java, front-end design, and UI/UX. He's passionate about building tools that encourage healthy digital habits.</p>
    </div>
  </div>

  <div class="member">
    <img src="assets/Balemual.jpg" alt="Balemual Ymamu">
    <div>
      <h3>Balemual Ymamu</h3>
      <p>Balemual is a senior at ODU majoring in CS with a cybersecurity minor, set to graduate in Fall 2025. He earned an Associate of Science from Tidewater Community College. He's passionate about software engineering and enjoys soccer and socializing in his spare time.</p>
    </div>
  </div>

  <div class="member">
    <img src="assets/AugustineKpewa.jpg" alt="Augustine Kpewa">
    <div>
      <h3>Augustine Kpewa</h3>
      <p>Augustine is a CS senior at ODU, graduating in Fall 2025. He holds an Associate Degree in CS from Northern Virginia Community College. He's proficient in Java, Python, C++, and web development. Outside of class, he enjoys soccer and fitness.</p>
    </div>
  </div>

  <div class="member">
    <img src="assets/DustinDobson.jpg" alt="Dustin Melton-Dobson">
    <div>
      <h3>Dustin Melton-Dobson</h3>
      <p>Dustin is a CS senior at ODU with an associate degree in CS from NOVA. He’s skilled in Java and has working knowledge of Python, C++, and HTML. He enjoys golf and walking his dog in his free time.</p>
    </div>
  </div>
</div>

<!-- Footer -->
<div class="footer">
  © 2025 Buddy Check Project · Designed by CS 410 Team at ODU
</div>

<footer style="text-align: center; font-size: 0.9rem; padding: 1rem 0; color: #444;">
  <a href="https://www.odu.edu/" target="_blank">Old Dominion University</a> |
  <a href="https://www.odu.edu/computer-science" target="_blank">ODU Computer Science Department</a>
</footer>
