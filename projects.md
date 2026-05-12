<style>
  body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    background-color: #ffffff;
  }

  .projects-page {
    max-width: 900px;
    margin: auto;
    padding: 50px;
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

  .project-buttons {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
    margin-top: 10px;
  }
</style>

<div class="projects-page">

  <a href="/">
    <button>← Back Home</button>
  </a>

  <h1>Projects</h1>

  <p>
    Selected projects from my Master of Data Science program and applied data science work.
  </p>

  <h2>MedDRA Autocoder</h2>

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

  <h2>Foodlytics Dashboard</h2>

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

  <h2>Amazon Reviews RAG Pipeline</h2>

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
