---
title: Cervical Mobile App
repo: https://github.com/QTIM-Lab/cervical_mobile_app
description: Point-of-care inference UI for Android devices.
layout: default
---

<div class="project-header">
  <h1>📱 {{ page.title }}</h1>
  <p style="font-size: 1.2rem; opacity: 0.9; margin-bottom: 2rem;">{{ page.description }}</p>
  <a href="{{ page.repo }}" class="repo-link" target="_blank">
    📂 View on GitHub
  </a>
</div>

<div class="content-section">
  <h2>Overview</h2>
  <p>A mobile application designed for point-of-care cervical cancer screening in resource-limited settings. The app provides an intuitive interface for healthcare workers to capture, analyze, and interpret cervical images using AI-powered automated visual evaluation.</p>
  
  <h3>Key Features</h3>
  <ul>
    <li><strong>Real-time AI analysis</strong> - Instant cervical image classification</li>
    <li><strong>Offline capability</strong> - Works without internet connectivity</li>
    <li><strong>User-friendly interface</strong> - Designed for healthcare workers with minimal training</li>
    <li><strong>Secure data handling</strong> - Patient privacy and data protection built-in</li>
    <li><strong>Integration ready</strong> - Compatible with existing healthcare systems</li>
  </ul>
</div>

<div class="content-section">
  <h2>Technical Specifications</h2>
  <table>
    <tr>
      <th>Platform</th>
      <th>Details</th>
    </tr>
    <tr>
      <td>Operating System</td>
      <td>Android 7.0+ (API level 24+)</td>
    </tr>
    <tr>
      <td>AI Framework</td>
      <td>TensorFlow Lite</td>
    </tr>
    <tr>
      <td>Camera API</td>
      <td>Camera2 API with advanced controls</td>
    </tr>
    <tr>
      <td>Storage</td>
      <td>Encrypted local storage with optional cloud sync</td>
    </tr>
    <tr>
      <td>Minimum RAM</td>
      <td>3GB (recommended: 4GB+)</td>
    </tr>
  </table>
</div>

<div class="content-section">
  <h2>Installation & Setup</h2>
  <p>To build and deploy the mobile application:</p>
  
  <pre><code>git clone {{ page.repo }}
cd cervical_mobile_app
flutter pub get
flutter build apk --release</code></pre>
  
  <blockquote>
    <strong>Note:</strong> This application is designed for use by trained healthcare professionals only. Proper training and certification are required before deployment in clinical settings.
  </blockquote>
  
  <p>For complete setup instructions and deployment guidelines, visit the <a href="{{ page.repo }}" target="_blank">GitHub repository</a>.</p>
</div>