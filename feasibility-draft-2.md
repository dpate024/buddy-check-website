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

  .hero {
    background: linear-gradient(to right, #1e5799, #2ecc71);
    padding: 2rem 1rem;
    text-align: center;
    border-radius: 0 0 10px 10px;
  }

  .hero h1 {
    color: white;
    margin-bottom: 0.5rem;
  }

  .hero p {
    font-size: 1.1rem;
    color: white;
    margin-top: 0;
  }

  .content {
    max-width: 900px;
    margin: 2rem auto;
    padding: 0 1.2rem;
    line-height: 1.7;
  }

  .footer {
    background-color: #0d1b2a;
    color: #e0e0e0;
    padding: 1rem 2rem;
    text-align: center;
    font-size: 0.9rem;
    margin-top: 3rem;
  }

  @media screen and (max-width: 600px) {
    .navbar {
      flex-direction: column;
      gap: 0.5rem;
    }

    .dropdown-content {
      position: static;
      box-shadow: none;
    }
  }

  .download-btn {
  background-color: #007acc;
  color: white;
  padding: 0.85rem 1.6rem;
  border-radius: 8px;
  text-decoration: none;
  font-weight: bold;
  font-size: 1rem;
  display: inline-block;
  transition: background-color 0.3s ease, transform 0.2s ease;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
}

.download-btn:hover {
  background-color: #005c99;
  transform: translateY(-2px);
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

<!-- HERO HEADER -->
<div class="hero">
  <h1>Feasibility Draft 2</h1>
  <p>Second feasibility analysis of the Buddy Check project.</p>
</div>

<!-- MAIN CONTENT -->
<div class="content">
  <p><iframe src="https://docs.google.com/presentation/d/e/2PACX-1vT9JoQXGtSToKjLOgTPSfT29IVtt7S7wScsznDWXCG0vrG5cRRyNLgzWE4JAAfg9rql1tjiSj-xnF0t/pubembed?start=true&loop=true&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe></p>

<div style="text-align: center; margin-top: 2rem;">
  <a href="https://docs.google.com/presentation/d/1BmO0iu5L7p1UXrzCHyQddvEzBTz09p5gBOFI5MHoiBg/edit?usp=sharing" target="_blank" class="download-btn">
  ⬇️ Download Feasibility Draft 2 (PPTX)
</a>
</div>
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

