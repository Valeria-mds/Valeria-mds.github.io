<style>
  * { box-sizing: border-box; }

  body { margin: 0; }

  button {
    padding: 8px 14px;
    border-radius: 6px;
    border: 1px solid #555;
    background-color: white;
    cursor: pointer;
    font-size: 14px;
  }

  button:hover { background-color: #f0f0f0; }

  .portfolio-container {
    display: flex;
    min-height: 100vh;
    font-family: Arial, sans-serif;
  }

  .sidebar {
    width: 32%;
    background-color: #f3eee8;
    padding: 40px;
    text-align: center;
  }

  .main-content {
    width: 68%;
    background-color: white;
    padding: 50px;
    line-height: 1.6;
  }

  .profile-img {
    width: 220px;
    border-radius: 12px;
    margin-bottom: 20px;
  }

  .button-row {
    display: flex;
    gap: 10px;
    justify-content: center;
    flex-wrap: wrap;
    margin-top: 20px;
  }

  @media (max-width: 800px) {
    .portfolio-container { flex-direction: column; }
    .sidebar, .main-content { width: 100%; }
  }
</style>

<div class="portfolio-container">

  <div class="sidebar">

    <img src="assets/images/profile.jpg" class="profile-img" alt="Profile photo of Valeria Siciliano">

    <h1>Valeria Siciliano</h1>

    <p>Master of Data Science Student at UBC</p>

    <div class="button-row">

      <a href="/projects">
        <button>Projects</button>
      </a>

      <a href="https://www.linkedin.com/in/valeria-siciliano-/" target="_blank">
        <button>LinkedIn</button>
      </a>

      <a href="https://github.com/Valeria-mds" target="_blank">
        <button>GitHub</button>
      </a>

      <a href="mailto:valeriasic002@gmail.com">
        <button>Email Me</button>
      </a>

    </div>

  </div>

  <div class="main-content">

    <h1>Hi, I’m Valeria</h1>

    <p>
      I am a Master of Data Science student at UBC with a background in pharmaceutical technology and analytical chemistry.
      I am interested in applying machine learning, NLP, and data-driven solutions to healthcare and clinical problems.
    </p>

    <p>
      My work focuses on building practical and interpretable solutions that connect healthcare, clinical terminology, and data science.
    </p>

    <h2>What I’m interested in</h2>

    <p>
      Healthcare NLP, machine learning, clinical data processing, data visualization, and reproducible data science workflows.
    </p>

    <h2>Featured Work</h2>

    <p>
      I have worked on projects involving clinical terminology standardization, retrieval-augmented generation, and interactive dashboards.
    </p>

    <a href="/projects">
      <button>View Projects</button>
    </a>

  </div>

</div>
