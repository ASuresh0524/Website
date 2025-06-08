---
layout: single
title: "Research"
permalink: /research/
author_profile: true
classes: wide
---

<div class="research-wrapper">
  <div class="research-intro">
    <p>
      My research focuses on applying machine learning and artificial intelligence to healthcare challenges,
      particularly in cancer research and medical data analysis. I work at the intersection of computer science
      and medicine, developing innovative solutions for complex healthcare problems.
    </p>
  </div>

  <div class="current-research">
    <h2>Current Research</h2>
    
    <div class="research-card">
      <h3>Ancestry-Aware Cancer Risk Classification</h3>
      <p class="institution">Memorial Sloan Kettering Cancer Center - Carrot-Zhang Lab</p>
      <p class="description">
        Developing machine learning models that account for genetic ancestry in cancer risk assessment,
        improving prediction accuracy across diverse populations by 32%.
      </p>
      <ul class="highlights">
        <li>Implementing LightGBM and SHAP for interpretable predictions</li>
        <li>Processing TCGA and GENIE datasets using advanced genomic pipelines</li>
        <li>Contributing to the QSURE Program research initiatives</li>
      </ul>
    </div>

    <div class="research-card">
      <h3>Intelligent Data Discovery Systems</h3>
      <p class="institution">T-Mobile</p>
      <p class="description">
        Building advanced data discovery pipelines that integrate RAG and agentic workflows,
        enhancing search accuracy and recommendations for enterprise data systems.
      </p>
      <ul class="highlights">
        <li>Improved table/column recommendations by 30%</li>
        <li>Enhanced search accuracy for 3500+ users</li>
        <li>Implemented enterprise-grade security measures</li>
      </ul>
    </div>
  </div>

  <div class="past-research">
    <h2>Past Research</h2>

    <div class="research-card">
      <h3>Breast Cancer Subtype Classification</h3>
      <p class="institution">National Science Foundation</p>
      <p class="description">
        Developed a 1D-CNN classification pipeline for rapid breast cancer subtype prediction,
        achieving 95% accuracy and significantly reducing identification time.
      </p>
      <ul class="highlights">
        <li>Published findings in peer-reviewed journals</li>
        <li>Presented at healthcare innovation conferences</li>
        <li>Implemented in clinical testing environments</li>
      </ul>
    </div>

    <div class="research-card">
      <h3>Lab Test Volume Prediction</h3>
      <p class="institution">Quest Diagnostics</p>
      <p class="description">
        Created time-series classification models to predict lab test volume trends,
        optimizing resource allocation and improving operational efficiency.
      </p>
      <ul class="highlights">
        <li>Built experiment logging infrastructure</li>
        <li>Improved test specificity by 25%</li>
        <li>Implemented proactive resource planning</li>
      </ul>
    </div>
  </div>
</div>

<style>
.research-wrapper {
  max-width: 900px;
  margin: 0 auto;
  padding: 20px;
}

.research-intro {
  font-size: 1.2em;
  line-height: 1.6;
  margin-bottom: 40px;
  color: #333;
}

.research-card {
  background: #fff;
  border-radius: 8px;
  padding: 25px;
  margin-bottom: 30px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.research-card h3 {
  margin: 0;
  color: #333;
}

.institution {
  color: #666;
  font-style: italic;
  margin: 10px 0;
}

.description {
  font-size: 1.1em;
  line-height: 1.6;
  margin: 15px 0;
}

.highlights {
  list-style-type: none;
  padding-left: 0;
  margin-top: 15px;
}

.highlights li {
  margin: 8px 0;
  padding-left: 20px;
  position: relative;
}

.highlights li:before {
  content: "•";
  color: #007bff;
  position: absolute;
  left: 0;
}

h2 {
  margin: 40px 0 20px;
  color: #333;
  border-bottom: 2px solid #eee;
  padding-bottom: 10px;
}
</style> 