---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---
<style>
  .portfolio {
    font-family: Arial, sans-serif;
    max-width: 800px;
    margin: 0 auto;
  }

  h2 {
    text-align: left;
    margin-bottom: 40px;
    border-bottom: 1px solid #ccc; /* Adds a thin line */
  }

  .participation {
    display: flex;
    margin-bottom: 40px;
    align-items: flex-start;
    padding-bottom: 20px;
  }

  .participation-image {
    width: 160px;
    height: 160px;
    background-color: #f0f0f0;
    margin-right: 20px;
    flex-shrink: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }

.participation-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  image-rendering: -webkit-optimize-contrast; /* For webkit browsers */
  image-rendering: crisp-edges; /* For other browsers */
}

  .participation-content {
    flex: 1;
  }

  .participation h3 {
    margin-top: 0;
    margin-bottom: 10px;
    font-size: 18px; /* Smaller heading size */
  }

  .team-members {
    font-style: italic;
    margin-bottom: 10px;
    font-size: 14px; /* Smaller team members text */
  }

  .participation-content p {
    font-size: 14px; /* Smaller paragraph text */
    margin-bottom: 10px;
  }

  .view-presentation {
    color: #0066cc;
    text-decoration: none;
    font-size: 14px; /* Smaller link text */
  }

  .view-presentation:hover {
    text-decoration: underline;
  }
</style>

<div class="portfolio">
  <h2>Presentations and Awards</h2>

  <div class="participation">
    <div class="participation-image">
      <img src="https://emmett-peng.github.io/images/case_study_1.jpeg" alt="BCG Platinion Hackathon">
    </div>
    <div class="participation-content">
      <h3>Winner-Case Studies in Data Analysis Competition, SSC 2025</h3>
      <p class="team-members"> Jiahui Zhang, Yu Shi, Aoqi Xie, and Yiming (Emmett) Peng</p>
      <p>A Ranked Developed an end-to-end deep learning model combining TabTransformer, DeepHit, SHAP, and conformal prediction to improve the accuracy, interpretability, and uncertainty calibration of atrial fibrillation risk prediction.</p>
      <p><strong>Ranked 1st out of 16 teams in the 2025 SSC Case Study Competition (Case Study #1): Prediction of New Onset Atrial Fibrillation Using Routinely Reported 12-Lead ECG Variables and Electronic Health Data.</strong></p>
      <a href="https://emmett-peng.github.io/files/SSC_Case Study Poster 0523.pdf" target="_blank">[View Presentation]</a>
    </div>
  </div>

  <div class="participation">
    <div class="participation-image">
      <img src="https://abirharrasse.github.io/images/iot_challenge.png" alt="IoT&AI Challenge: Sehhatech">
    </div>
    <div class="participation-content">
      <h3>IoT&AI Challenge: Sehhatech</h3>
      <p class="team-members">Abir HARRASSE, Yassmine ED-DYB, Soufiane Dahimi</p>
      <p>Sehhatech is an AI medical assistant that gathers patient info, generates reports, and connects patients to the right specialists, enhancing healthcare efficiency.</p>
      <p><strong>Finalist at IoT&AI Challenge</strong></p>
      <a href="https://github.com/MoroccoAI/2023-GenAI-Hackathon/tree/main/SehhaTech" class="view-presentation" target="_blank">[Presentation and Code]</a>
    </div>
  </div>
    <h2>Relevant Projects</h2>
    <div class="participation">
    <div class="participation-image">
        <img src="https://abirharrasse.github.io/images/kg.png" alt="Knowledge Graph Construction Project">
    </div>
    <div class="participation-content">
        <h3>Knowledge Graph Construction with LLMs</h3>
        <p>This project explores methods for leveraging LLMs to construct Knowledge Graphs (KGs) and perform accurate Question Answering (QA). We focus on refining KG extraction techniques and evaluate the trade-offs between KGs and vector databases for knowledge storage and querying. Additionally, we investigate approaches for tracking the origin of facts used in KG creation.</p>
        <a href="https://github.com/abirharrasse/LLM-Powered-Knowledge-Graphs-for-Question-Answering" class="view-presentation" target="_blank">[Github Repo]</a>
    </div>
</div>

</div>
