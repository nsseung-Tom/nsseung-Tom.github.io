---
layout: single
title: "Projects"
permalink: /projects/
---

<p style="font-size: 1.1rem; color: #718096; margin-bottom: 2rem;">
A selection of <strong style="color: #1a365d;">data science</strong> and 
<strong style="color: #1a365d;">analytics projects</strong> from industry and coursework, 
demonstrating my expertise in causal inference, machine learning, and product analytics.
</p>

---

## Industry Projects

<div class="project-card">
  <h3>🚀 Financial Super App Expansion Analysis</h3>
  <p class="collaborators">Viva Republica (Toss) · Data Product Manager</p>
  <p class="description">
    Led the measurement of causal impact when Toss integrated banking and securities subsidiaries 
    into its main app ecosystem. This was a critical strategic initiative as Toss evolved from a 
    simple payment app into a comprehensive financial super app.
  </p>
  <p class="description">
    <strong>Challenge:</strong> Quantify the true engagement uplift from financial service integration, 
    separating it from organic growth and seasonal trends.
  </p>
  <p class="description">
    <strong>Approach:</strong> Designed a quasi-experimental framework using cohort-based analysis 
    and difference-in-differences methodology. Created synthetic control groups from users with 
    different adoption timing to estimate treatment effects.
  </p>
  <p class="description">
    <strong>Impact:</strong> Findings directly informed executive decisions on product integration 
    strategy and resource allocation across Toss's 20M+ user base.
  </p>
  <div class="tags">
    <span class="tag">Causal Inference</span>
    <span class="tag">DiD</span>
    <span class="tag">Product Analytics</span>
    <span class="tag">Python</span>
    <span class="tag">SQL</span>
  </div>
</div>

<div class="project-card">
  <h3>📊 DiD-Inspired Engagement Metric System</h3>
  <p class="collaborators">Viva Republica (Toss) · Data Product Manager</p>
  <p class="description">
    Traditional engagement metrics fail to capture each service's <em>causal contribution</em> to 
    overall app usage—they conflate correlation with causation. I designed a novel metric 
    framework inspired by econometric methods to solve this problem.
  </p>
  <p class="description">
    <strong>Innovation:</strong> Developed a Difference-in-Differences–based engagement metric 
    that estimates each service's incremental impact on total app usage by comparing users 
    before and after adopting specific features.
  </p>
  <p class="description">
    <strong>Deployment:</strong> The metric system was integrated into Toss's product decision 
    pipeline, enabling product managers to prioritize features based on true causal impact 
    rather than simple usage correlations.
  </p>
  <div class="tags">
    <span class="tag">Metric Design</span>
    <span class="tag">Causal Attribution</span>
    <span class="tag">A/B Testing</span>
    <span class="tag">Data Pipeline</span>
  </div>
</div>

---

## Academic Projects

<div class="project-card">
  <h3>🧠 Deep Learning for Inflation Forecasting</h3>
  <p class="collaborators">Course: Data Science for Economic Analysis · Grade: A+</p>
  <p class="description">
    Compared traditional econometric approaches (VAR models) with modern deep learning methods 
    for macroeconomic forecasting. The project explored whether neural networks can capture 
    complex, non-linear relationships in economic time series data.
  </p>
  <p class="description">
    <strong>Methods:</strong> Implemented Vector Autoregression (VAR), Bayesian LSTM, and 
    Transformer-based architectures. Used proper time-series cross-validation to prevent 
    data leakage and ensure fair comparison.
  </p>
  <p class="description">
    <strong>Findings:</strong> Bayesian LSTM showed improved uncertainty quantification compared 
    to point-estimate models, though VAR remained competitive for short-horizon forecasts.
  </p>
  <div class="tags">
    <span class="tag">LSTM</span>
    <span class="tag">Bayesian Deep Learning</span>
    <span class="tag">Time Series</span>
    <span class="tag">PyTorch</span>
    <span class="tag">Econometrics</span>
  </div>
</div>

<div class="project-card">
  <h3>🏀 NBA Undervalued Player Analysis</h3>
  <p class="collaborators">Course: Machine Learning Programming · Grade: A+</p>
  <p class="description">
    Inspired by the Moneyball approach, this project aimed to identify undervalued NBA players 
    using machine learning methods. The goal was to build a "fair salary" predictor and find 
    players whose market value exceeds their current compensation.
  </p>
  <p class="description">
    <strong>Methods:</strong> Engineered features from player statistics, team performance, 
    and market data. Trained Decision Tree, Random Forest, and Gradient Boosting models. 
    Used SHAP values for model interpretability.
  </p>
  <p class="description">
    <strong>Key Insight:</strong> Defensive metrics and advanced efficiency stats were 
    systematically underweighted by the market, creating opportunities to identify 
    value-add players overlooked by traditional scouting.
  </p>
  <div class="tags">
    <span class="tag">Decision Trees</span>
    <span class="tag">Random Forest</span>
    <span class="tag">Feature Engineering</span>
    <span class="tag">SHAP</span>
    <span class="tag">Sports Analytics</span>
  </div>
</div>

---

## Technical Skills

<div class="skills-grid">
  <div class="skill-category">
    <h4>🐍 Programming Languages</h4>
    <span class="tag">Python</span>
    <span class="tag">R</span>
    <span class="tag">SQL</span>
    <span class="tag">Stata</span>
  </div>
  
  <div class="skill-category">
    <h4>🤖 Machine Learning</h4>
    <span class="tag">scikit-learn</span>
    <span class="tag">PyTorch</span>
    <span class="tag">XGBoost</span>
    <span class="tag">LightGBM</span>
    <span class="tag">TensorFlow</span>
  </div>
  
  <div class="skill-category">
    <h4>📈 Data & Analytics</h4>
    <span class="tag">pandas</span>
    <span class="tag">NumPy</span>
    <span class="tag">tidyverse</span>
    <span class="tag">Matplotlib</span>
    <span class="tag">Tableau</span>
  </div>
  
  <div class="skill-category">
    <h4>🛠️ Tools & Infrastructure</h4>
    <span class="tag">Git</span>
    <span class="tag">Docker</span>
    <span class="tag">AWS</span>
    <span class="tag">Airflow</span>
    <span class="tag">Jupyter</span>
  </div>
</div>

---

<div class="card" style="background: linear-gradient(135deg, #1a365d, #2d5a8a); color: white; text-align: center; padding: 2rem;">
  <h3 style="color: white; border: none; margin-bottom: 1rem;">💡 Want to collaborate?</h3>
  <p style="margin-bottom: 1.5rem; opacity: 0.9;">
    I'm always interested in discussing data science projects and research opportunities.
  </p>
  <a href="mailto:thomas96124@gmail.com" class="btn" style="background: rgba(255,255,255,0.2); color: white; border: 2px solid rgba(255,255,255,0.5);">
    Get in Touch →
  </a>
</div>
