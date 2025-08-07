---
title: Cervical Cancer Baseline Pipeline
repo: https://github.com/QTIM-Lab/cervical_cancer
description: End-to-end detection & classification baseline using imaging data.
layout: default
---

<div class="project-header">
  <h1>🔬 {{ page.title }}</h1>
  <p style="font-size: 1.2rem; opacity: 0.9; margin-bottom: 2rem;">{{ page.description }}</p>
  <a href="{{ page.repo }}" class="repo-link" target="_blank">
    📂 View on GitHub
  </a>
</div>

<div class="content-section">
  <h2>Overview</h2>
  <p>This project provides a comprehensive baseline pipeline for cervical cancer detection and classification using advanced imaging data processing techniques. The system is designed to work with various imaging modalities commonly used in cervical cancer screening.</p>
  
  <h3>Key Features</h3>
  <ul>
    <li><strong>Multi-modal imaging support</strong> - Compatible with various cervical imaging types</li>
    <li><strong>End-to-end pipeline</strong> - From raw image preprocessing to final classification</li>
    <li><strong>Baseline models</strong> - Well-established architectures for comparison studies</li>
    <li><strong>Reproducible results</strong> - Standardized evaluation metrics and protocols</li>
  </ul>
</div>

<div class="content-section">
  <h2>Technical Specifications</h2>
  <table>
    <tr>
      <th>Component</th>
      <th>Technology</th>
    </tr>
    <tr>
      <td>Deep Learning Framework</td>
      <td>PyTorch/TensorFlow</td>
    </tr>
    <tr>
      <td>Image Processing</td>
      <td>OpenCV, PIL</td>
    </tr>
    <tr>
      <td>Data Formats</td>
      <td>DICOM, JPEG, PNG</td>
    </tr>
    <tr>
      <td>Model Architectures</td>
      <td>ResNet, EfficientNet, Vision Transformer</td>
    </tr>
  </table>
</div>

<div class="content-section">
  <h2>Getting Started</h2>
  <p>To get started with this baseline pipeline:</p>
  
  <pre><code>git clone {{ page.repo }}
cd cervical_cancer
pip install -r requirements.txt
python train.py --config configs/baseline.yaml</code></pre>
  
  <p>For detailed documentation and usage examples, please visit the <a href="{{ page.repo }}" target="_blank">GitHub repository</a>.</p>
</div>