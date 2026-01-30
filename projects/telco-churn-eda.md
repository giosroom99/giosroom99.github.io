---
title: Telco Customer Churn EDA
---

<section class="hero">
  <h1 class="hero-title">Telco Customer Churn EDA</h1>
  <p class="hero-subtitle"><strong>Exploratory analysis of churn signals and risk segments.</strong></p>
  <div class="hero-actions">
    <a class="btn btn-primary" href="https://github.com/giosroom99/telco-churn-eda">Repository</a>
    <a class="btn btn-ghost" href="https://github.com/giosroom99/telco-churn-eda/blob/main/notebooks/01_telco_churn_eda.ipynb">Notebook</a>
  </div>
</section>

<section class="section">
  <h2 class="section-title">Project Summary</h2>
  <div class="panel">
    <p>
      This project explores the IBM Telco Customer Churn dataset to uncover the strongest churn
      signals across tenure, contract type, and service add-ons. The goal is to identify segments
      where retention efforts yield the highest impact.
    </p>
    <p>
      <strong>Skills:</strong> Python, Pandas, EDA, Data Cleaning, Statistical Testing, Visualization
    </p>
  </div>
</section>

<section class="section">
  <h2 class="section-title">Data</h2>
  <div class="grid">
    <div class="card">
      <strong>Source</strong>
      <p>IBM Telco Customer Churn dataset</p>
    </div>
    <div class="card">
      <strong>Rows / Columns</strong>
      <p>7,043 rows, 21 columns</p>
    </div>
    <div class="card">
      <strong>Target</strong>
      <p>Churn (Yes/No)</p>
    </div>
    <div class="card">
      <strong>Key Features</strong>
      <p>tenure, MonthlyCharges, TotalCharges, Contract, PaymentMethod</p>
    </div>
  </div>
</section>

<section class="section">
  <h2 class="section-title">Exploratory Analysis</h2>
  <div class="panel">
    <ul>
      <li>Target balance and churn rate distribution</li>
      <li>Numeric distributions for tenure and charges</li>
      <li>Churn rates by contract type and service bundle</li>
    </ul>
  </div>
</section>

<section class="section">
  <h2 class="section-title">Key Insights</h2>
  <div class="grid">
    <div class="card">
      <strong>Contract Sensitivity</strong>
      <p>Month-to-month customers churn at much higher rates than long-term contracts.</p>
    </div>
    <div class="card">
      <strong>Tenure Effects</strong>
      <p>Churn risk is concentrated early in customer tenure.</p>
    </div>
    <div class="card">
      <strong>Add-on Impact</strong>
      <p>Security and support add-ons are correlated with lower churn.</p>
    </div>
  </div>
</section>

<section class="section">
  <h2 class="section-title">Next Steps</h2>
  <div class="panel">
    <ul>
      <li>Build a baseline classifier and measure uplift</li>
      <li>Define cost-sensitive thresholds for retention actions</li>
      <li>Monitor churn rates by segment for drift</li>
    </ul>
  </div>
</section>
