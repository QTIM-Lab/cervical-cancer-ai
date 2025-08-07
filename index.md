---
layout: default
---

<style>
/* Modern base styling */
body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  line-height: 1.6;
  color: #333;
}

/* Hero section */
.hero {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 4rem 2rem;
  margin: -2rem -2rem 3rem -2rem;
  text-align: center;
  border-radius: 0 0 20px 20px;
}

.hero h1 {
  font-size: 2.5rem;
  font-weight: 700;
  margin-bottom: 1rem;
  text-shadow: 0 2px 4px rgba(0,0,0,0.3);
}

.hero-subtitle {
  font-size: 1.2rem;
  opacity: 0.9;
  max-width: 800px;
  margin: 0 auto;
}

/* Section styling */
.section {
  margin: 3rem 0;
  padding: 2rem;
  background: white;
  border-radius: 12px;
  box-shadow: 0 4px 20px rgba(0,0,0,0.08);
  border: 1px solid #f0f0f0;
}

.section h2 {
  color: #2c3e50;
  font-size: 1.8rem;
  font-weight: 600;
  margin-bottom: 1.5rem;
  padding-bottom: 0.5rem;
  border-bottom: 3px solid #667eea;
  display: inline-block;
}

/* Publications grid */
.publications-grid {
  display: grid;
  gap: 1.5rem;
  margin-top: 2rem;
}

.publication-card {
  background: #f8f9fa;
  border: 1px solid #e9ecef;
  border-radius: 10px;
  padding: 1.5rem;
  transition: all 0.3s ease;
  border-left: 4px solid #667eea;
}

.publication-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 25px rgba(0,0,0,0.12);
  border-left-color: #764ba2;
}

.publication-title {
  font-weight: 600;
  color: #2c3e50;
  margin-bottom: 0.5rem;
  line-height: 1.4;
}

.publication-journal {
  color: #667eea;
  font-style: italic;
  font-weight: 500;
  margin-bottom: 0.5rem;
}

.publication-year {
  background: #667eea;
  color: white;
  padding: 0.2rem 0.6rem;
  border-radius: 20px;
  font-size: 0.8rem;
  font-weight: 500;
  display: inline-block;
  margin-bottom: 0.5rem;
}

.pubmed-link {
  display: inline-flex;
  align-items: center;
  background: #28a745;
  color: white;
  padding: 0.4rem 0.8rem;
  border-radius: 6px;
  text-decoration: none;
  font-size: 0.85rem;
  font-weight: 500;
  transition: background 0.2s;
}

.pubmed-link:hover {
  background: #218838;
  color: white;
  text-decoration: none;
}

/* Research focus grid */
.focus-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
}

.focus-item {
  background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
  padding: 1.5rem;
  border-radius: 10px;
  text-align: center;
  border: 1px solid #dee2e6;
  transition: all 0.3s ease;
}

.focus-item:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 20px rgba(0,0,0,0.1);
}

.focus-icon {
  font-size: 2.5rem;
  margin-bottom: 1rem;
  display: block;
}

.focus-item h3 {
  color: #2c3e50;
  margin: 0;
  font-size: 1.1rem;
  font-weight: 600;
}

/* Project tiles */
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
}

.project-tile {
  background: white;
  border: 1px solid #e9ecef;
  border-radius: 12px;
  padding: 1.5rem;
  box-shadow: 0 4px 15px rgba(0,0,0,0.08);
  transition: all 0.3s ease;
  border-top: 4px solid #667eea;
}

.project-tile:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 25px rgba(0,0,0,0.15);
  border-top-color: #764ba2;
}

.project-title {
  margin: 0 0 1rem 0;
  color: #2c3e50;
  font-size: 1.2rem;
  font-weight: 600;
}

.project-title a {
  text-decoration: none;
  color: inherit;
}

.project-title a:hover {
  color: #667eea;
}

.project-description {
  color: #6c757d;
  margin-bottom: 1.5rem;
  line-height: 1.5;
}

.project-link {
  display: inline-flex;
  align-items: center;
  padding: 0.6rem 1.2rem;
  background: #667eea;
  color: white;
  text-decoration: none;
  border-radius: 8px;
  font-size: 0.9rem;
  font-weight: 500;
  transition: all 0.2s;
}

.project-link:hover {
  background: #5a6fd8;
  color: white;
  text-decoration: none;
  transform: translateY(-1px);
}

/* Stats section */
.stats-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.stat-card {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 2rem;
  border-radius: 12px;
  text-align: center;
  box-shadow: 0 4px 15px rgba(102, 126, 234, 0.3);
}

.stat-number {
  font-size: 2.5rem;
  font-weight: 700;
  display: block;
  margin-bottom: 0.5rem;
}

.stat-label {
  font-size: 0.9rem;
  opacity: 0.9;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

/* Webinar highlight */
.webinar-highlight {
  background: linear-gradient(135deg, #28a745 0%, #20c997 100%);
  color: white;
  padding: 1.5rem;
  border-radius: 10px;
  margin: 2rem 0;
  text-align: center;
}

.webinar-highlight a {
  color: white;
  font-weight: 600;
  text-decoration: underline;
}

.webinar-highlight a:hover {
  color: #e9ecef;
}

/* Responsive adjustments */
@media (max-width: 768px) {
  .hero {
    padding: 2rem 1rem;
    margin: -1rem -1rem 2rem -1rem;
  }
  
  .hero h1 {
    font-size: 2rem;
  }
  
  .section {
    margin: 2rem 0;
    padding: 1.5rem;
  }
  
  .focus-grid,
  .project-grid {
    grid-template-columns: 1fr;
  }
  
  .stats-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}
</style>

<div class="hero">
  <h1>🔬 Cervical Cancer AI Suite for PAVE</h1>
  <p class="hero-subtitle">Advanced AI solutions for cervical cancer detection, analysis, and treatment planning in resource-limited settings</p>
</div>

<div class="stats-grid">
  <div class="stat-card">
    <span class="stat-number">9</span>
    <span class="stat-label">Countries</span>
  </div>
  <div class="stat-card">
    <span class="stat-number">50K+</span>
    <span class="stat-label">Women Screened</span>
  </div>
  <div class="stat-card">
    <span class="stat-number">1,832</span>
    <span class="stat-label">HPV+ Participants</span>
  </div>
  <div class="stat-card">
    <span class="stat-number">25%+</span>
    <span class="stat-label">Risk Reduction</span>
  </div>
</div>

<div class="section">
  <h2>🎯 Background</h2>
  <p>The <strong>HPV-automated visual evaluation (PAVE) Study</strong> is an extensive, multinational initiative designed to advance cervical cancer prevention in resource-constrained regions. Cervical cancer disproportionally affects regions with limited access to preventive measures. PAVE aims to assess a novel screening-triage-treatment strategy integrating self-sampled HPV testing, deep-learning-based automated visual evaluation (AVE), and targeted therapies.</p>
</div>

<div class="section">
  <h2>🔬 Methods</h2>
  <p>Phase 1 of the PAVE effort involved screening up to 50,000 women aged 25-49 across nine countries, using self-collected vaginal samples for hierarchical HPV evaluation: HPV16, else HPV18/45, else HPV31/33/35/52/58, else HPV39/51/56/59/68 else negative. HPV-positive individuals undergo further evaluation, including pelvic exams, cervical imaging, and biopsies. AVE algorithms analyze images, assigning risk scores for precancer, validated against histologic high-grade precancer.</p>
</div>

<div class="section">
  <h2>📊 Results</h2>
  <p>Triage of positives combines HPV genotyping (four groups in order of cancer risk) and visual inspection assisted by automated cervical visual evaluation (AVE) that classifies cervical appearance as severe, indeterminate, or normal. Data from 1832 HPV-positive participants across nine clinical sites confirmed that HPV genotype and AVE classification each strongly and independently predict risk of histologic CIN3+, with <strong>&lt;1% risk for the lowest strata and &gt;25% for the highest risk strata</strong>.</p>
</div>

<div class="section">
  <h2>🚀 Next Steps</h2>
  <p>Additional studies will focus on further refining AI algorithms, deploying AVE software and HPV genotype data in real-time clinical decision-making, evaluating feasibility, acceptability, cost-effectiveness, and health communication of the PAVE strategy in practice.</p>
  
  <div class="webinar-highlight">
    <strong>📺 Learn more:</strong> <a href="https://www.youtube.com/watch?v=QV9N84BtcM8" target="_blank">PAVE Project Webinar</a> (co-sponsored by the American Cancer Society and Cervical Cancer Action for Elimination)
  </div>
</div>

<div class="section">
  <h2>📚 Publications</h2>
  <p>Our research has been published in leading medical and computer science journals:</p>
  
  <div class="publications-grid">
    <div class="publication-card">
      <div class="publication-year">2025</div>
      <div class="publication-title">Initial evaluation of a new cervical screening strategy combining human papillomavirus genotyping and automated visual evaluation: the Human Papillomavirus-Automated Visual Evaluation Consortium</div>
      <div class="publication-journal">J Natl Cancer Inst</div>
      <div><strong>Befano, B., Kalpathy-Cramer, J., Egemen, D.</strong>, et al.</div>
      <a href="https://pubmed.ncbi.nlm.nih.gov/40104876/" class="pubmed-link" target="_blank">🔗 PubMed</a>
    </div>
    
    <div class="publication-card">
      <div class="publication-year">2025</div>
      <div class="publication-title">Generalizable deep neural networks for image quality classification of cervical images</div>
      <div class="publication-journal">Sci Rep</div>
      <div><strong>Ahmed, S.R., Befano, B., Egemen, D.</strong>, et al.</div>
      <a href="https://pubmed.ncbi.nlm.nih.gov/39984572/" class="pubmed-link" target="_blank">🔗 PubMed</a>
    </div>
    
    <div class="publication-card">
      <div class="publication-year">2024</div>
      <div class="publication-title">Design of the HPV-automated visual evaluation (PAVE) study: Validating a novel cervical screening strategy</div>
      <div class="publication-journal">Elife</div>
      <div><strong>de Sanjosé, S., Perkins, R.B., Campos, N.</strong>, et al.</div>
      <a href="https://pubmed.ncbi.nlm.nih.gov/38224340/" class="pubmed-link" target="_blank">🔗 PubMed</a>
    </div>
    
    <div class="publication-card">
      <div class="publication-year">2024</div>
      <div class="publication-title">Artificial intelligence-based image analysis in clinical testing: lessons from cervical cancer screening</div>
      <div class="publication-journal">J Natl Cancer Inst</div>
      <div><strong>Egemen, D., Perkins, R.B., Cheung, L.C.</strong>, et al.</div>
      <a href="https://pubmed.ncbi.nlm.nih.gov/37758250/" class="pubmed-link" target="_blank">🔗 PubMed</a>
    </div>
    
    <div class="publication-card">
      <div class="publication-year">2023</div>
      <div class="publication-title">Reproducible and clinically translatable deep neural networks for cervical screening</div>
      <div class="publication-journal">Sci Rep</div>
      <div><strong>Ahmed, S.R., Befano, B., Lemay, A.</strong>, et al.</div>
      <a href="https://pubmed.ncbi.nlm.nih.gov/38066031/" class="pubmed-link" target="_blank">🔗 PubMed</a>
    </div>
    
    <div class="publication-card">
      <div class="publication-year">2023</div>
      <div class="publication-title">Use of risk-based cervical screening programs in resource-limited settings</div>
      <div class="publication-journal">Cancer Epidemiol</div>
      <div><strong>Perkins, R.B., Smith, D.L., Jeronimo, J.</strong>, et al.</div>
      <a href="https://pubmed.ncbi.nlm.nih.gov/37105017/" class="pubmed-link" target="_blank">🔗 PubMed</a>
    </div>
  </div>
  
  <p style="margin-top: 2rem; text-align: center; color: #6c757d;"><em>For a complete list of publications, please visit our <a href="https://qtim-lab.github.io/" target="_blank">lab website</a>.</em></p>
</div>

<div class="section">
  <h2>🎯 Our Research Focus</h2>
  <div class="focus-grid">
    <div class="focus-item">
      <span class="focus-icon">🔍</span>
      <h3>Cervical Cancer Detection & Diagnosis</h3>
    </div>
    <div class="focus-item">
      <span class="focus-icon">📱</span>
      <h3>Mobile Applications for Cervical Health</h3>
    </div>
    <div class="focus-item">
      <span class="focus-icon">🤖</span>
      <h3>AI Model Deployment & Optimization</h3>
    </div>
    <div class="focus-item">
      <span class="focus-icon">🌍</span>
      <h3>Generalizability Studies Across Populations</h3>
    </div>
    <div class="focus-item">
      <span class="focus-icon">📊</span>
      <h3>Cervical Dynamics Analysis</h3>
    </div>
  </div>
</div>

<div class="section">
  <h2>💻 Research Projects</h2>
  <div class="project-grid">
    {% for project in site.projects %}
    <div class="project-tile">
      <h3 class="project-title">
        <a href="{{ project.url | relative_url }}">{{ project.title }}</a>
      </h3>
      <p class="project-description">{{ project.description }}</p>
      {% if project.repo %}
      <a href="{{ project.repo }}" class="project-link" target="_blank">🔗 View Repository</a>
      {% endif %}
    </div>
    {% endfor %}
  </div>
</div>

<footer style="text-align: center; margin-top: 4rem; padding: 2rem; color: #6c757d; border-top: 1px solid #e9ecef;">
  <p><em>🏥 QTIM Lab - Quantitative Translational Imaging in Medicine</em></p>
</footer>