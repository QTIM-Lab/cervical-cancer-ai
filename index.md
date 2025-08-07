---
layout: default
---

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
  margin: 20px 0;
}
.project-tile {
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  padding: 20px;
  background: #fff;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  transition: transform 0.2s, box-shadow 0.2s;
}
.project-tile:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 8px rgba(0,0,0,0.15);
}
.project-title {
  margin: 0 0 10px 0;
  color: #0366d6;
}
.project-title a {
  text-decoration: none;
  color: inherit;
}
.project-title a:hover {
  text-decoration: underline;
}
.project-description {
  color: #586069;
  margin-bottom: 15px;
  line-height: 1.5;
}
.project-link {
  display: inline-block;
  padding: 8px 16px;
  background: #0366d6;
  color: white;
  text-decoration: none;
  border-radius: 4px;
  font-size: 14px;
}
.project-link:hover {
  background: #0256cc;
  color: white;
}
</style>

# Cervical Cancer AI Suite

Welcome to QTIM Lab's cervical cancer AI research collection.

## Research Projects

<div class="project-grid">
  <div class="project-tile">
    <h3 class="project-title">Cervical Cancer Baseline Pipeline</h3>
    <p class="project-description">End-to-end detection & classification baseline using VIA data.</p>
    <a href="https://github.com/QTIM-Lab/cervical_cancer" class="project-link" target="_blank">View Repository</a>
  </div>
  
  <div class="project-tile">
    <h3 class="project-title">Cervical Mobile App</h3>
    <p class="project-description">Flutter-based point-of-care inference UI for Android devices.</p>
    <a href="https://github.com/QTIM-Lab/cervical_mobile_app" class="project-link" target="_blank">View Repository</a>
  </div>
  
  <div class="project-tile">
    <h3 class="project-title">Cervical Dynamics</h3>
    <p class="project-description">Spatio-temporal modelling of lesion regression & progression.</p>
    <a href="https://github.com/QTIM-Lab/cervical-dynamics" class="project-link" target="_blank">View Repository</a>
  </div>
  
  <div class="project-tile">
    <h3 class="project-title">Cervix Generalizability</h3>
    <p class="project-description">Cross-domain study on model robustness across global cohorts.</p>
    <a href="https://github.com/QTIM-Lab/cervix_generalizability" class="project-link" target="_blank">View Repository</a>
  </div>
  
  <div class="project-tile">
    <h3 class="project-title">SLIM Deployment</h3>
    <p class="project-description">Lightweight Torch + ONNX runtime container for edge GPUs.</p>
    <a href="https://github.com/QTIM-Lab/slim_deployment" class="project-link" target="_blank">View Repository</a>
  </div>
</div>
