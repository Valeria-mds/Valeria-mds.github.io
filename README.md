<style>
  * {
    box-sizing: border-box;
  }

  body {
    margin: 0;
  }

  button {
    padding: 8px 14px;
    border-radius: 6px;
    border: 1px solid #555;
    background-color: white;
    cursor: pointer;
    font-size: 14px;
  }

  button:hover {
    background-color: #f0f0f0;
  }

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

  .project-buttons {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
    margin-top: 10px;
  }

  @media (max-width: 800px) {
    .portfolio-container {
      flex-direction: column;
    }

    .sidebar,
    .main-content {
      width: 100%;
    }
  }
</style>

<div class="portfolio-container">

  <div class="sidebar">

    <img src="assets/images/profile.jpg" class="profile-img">

    <h1>Valeria Siciliano</h1>

    <p>Master of Data Science Student at UBC</p>

    <div class="button-row">

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

    <h2>Projects</h2>

    <h3>MedDRA Autocoder</h3>

    <p>
      Developing an NLP-assisted clinical terminology coding system in collaboration with BC Children’s Hospital Research Institute.
      The project focuses on transforming free-text clinical descriptions into standardized MedDRA terminology using rule-based matching,
      fuzzy matching, and machine learning approaches.
    </p>

    <p>
      Due to confidentiality and data privacy agreements, the source code and datasets are not publicly available.
    </p>

    <p>
      <strong>Skills:</strong> Python, NLP, Clinical Data Processing, Fuzzy Matching, Machine Learning, Data Pipelines
    </p>

    <hr>

    <h3>Foodlytics Dashboard</h3>

    <p>
      Interactive data analysis and visualization project exploring food-related datasets through statistical analysis and dashboard development.
      The project was originally developed in Python and later adapted in R to explore cross-language implementation.
    </p>

    <p>
      <strong>Skills:</strong> Python, R, Data Visualization, Statistical Analysis, Dashboards
    </p>

    <div class="project-buttons">

      <a href="https://github.com/UBC-MDS/DSCI-532_2026_23_foodlytics" target="_blank">
        <button>Python Version</button>
      </a>

      <a href="https://github.com/Valeria-mds/foodlytics-R" target="_blank">
        <button>R Version</button>
      </a>

    </div>

    <hr>

    <h3>Amazon Reviews RAG Pipeline</h3>
    
    <p>
      Hybrid retrieval and retrieval-augmented generation pipeline using BM25, FAISS, and transformer embeddings to retrieve and summarize
      product review information.
    </p>
    
    <p>
      <strong>Skills:</strong> Python, FAISS, BM25, LangChain, Hugging Face, NLP
    </p>
    
    <div class="project-buttons">
    
      <a href="https://github.com/UBC-MDS/DSCI_575_project_nguye106_valerias" target="_blank">
        <button>GitHub Repository</button>
      </a>
    
    </div>
    

  </div>

</div>

