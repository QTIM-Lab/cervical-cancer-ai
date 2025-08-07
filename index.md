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

# Cervical Cancer AI Suite for PAVE

Welcome to the PAVE project's AI research collection. This site showcases our projects focused on developing AI solutions for cervical cancer detection, analysis, and treatment planning.

## Background

The **HPV-automated visual evaluation (PAVE) Study** is an extensive, multinational initiative designed to advance cervical cancer prevention in resource-constrained regions. Cervical cancer disproportionally affects regions with limited access to preventive measures. PAVE aims to assess a novel screening-triage-treatment strategy integrating self-sampled HPV testing, deep-learning-based automated visual evaluation (AVE), and targeted therapies.

## Methods

Phase 1 of the PAVE effort involved screening up to 50,000 women aged 25-49 across nine countries, using self-collected vaginal samples for hierarchical HPV evaluation: HPV16, else HPV18/45, else HPV31/33/35/52/58, else HPV39/51/56/59/68 else negative. HPV-positive individuals undergo further evaluation, including pelvic exams, cervical imaging, and biopsies. AVE algorithms analyze images, assigning risk scores for precancer, validated against histologic high-grade precancer.

## Results

Triage of positives combines HPV genotyping (four groups in order of cancer risk) and visual inspection assisted by automated cervical visual evaluation (AVE) that classifies cervical appearance as severe, indeterminate, or normal. Data from 1832 HPV-positive participants across nine clinical sites confirmed that HPV genotype and AVE classification each strongly and independently predict risk of histologic CIN3+, with **<1% risk for the lowest strata and >25% for the highest risk strata**.

## Next Steps

Additional studies will focus on further refining AI algorithms, deploying AVE software and HPV genotype data in real-time clinical decision-making, evaluating feasibility, acceptability, cost-effectiveness, and health communication of the PAVE strategy in practice.

**Learn more**: [PAVE Project Webinar](https://www.youtube.com/watch?v=QV9N84BtcM8) (co-sponsored by the American Cancer Society and Cervical Cancer Action for Elimination)

## Publications

Our research has been published in leading medical and computer science journals:

- **Befano, B., Kalpathy-Cramer, J., Egemen, D.**, et al. (2025). "Initial evaluation of a new cervical screening strategy combining human papillomavirus genotyping and automated visual evaluation: the Human Papillomavirus-Automated Visual Evaluation Consortium." *J Natl Cancer Inst*, djaf054. [PMID: 40104876](https://pubmed.ncbi.nlm.nih.gov/40104876/)

- **Ahmed, S.R., Befano, B., Egemen, D.**, et al. (2025). "Generalizable deep neural networks for image quality classification of cervical images." *Sci Rep*, 15(1):6312. [PMID: 39984572](https://pubmed.ncbi.nlm.nih.gov/39984572/)

- **de Sanjosé, S., Perkins, R.B., Campos, N.**, et al. (2024). "Design of the HPV-automated visual evaluation (PAVE) study: Validating a novel cervical screening strategy." *Elife*, 12:RP91469. [PMID: 38224340](https://pubmed.ncbi.nlm.nih.gov/38224340/)

- **Ahmed, S.R., Befano, B., Lemay, A.**, et al. (2023). "Reproducible and clinically translatable deep neural networks for cervical screening." *Sci Rep*, 13(1):21772. [PMID: 38066031](https://pubmed.ncbi.nlm.nih.gov/38066031/)

- **Egemen, D., Perkins, R.B., Cheung, L.C.**, et al. (2024). "Artificial intelligence-based image analysis in clinical testing: lessons from cervical cancer screening." *J Natl Cancer Inst*, 116(1):26-33. [PMID: 37758250](https://pubmed.ncbi.nlm.nih.gov/37758250/)

- **Perkins, R.B., Smith, D.L., Jeronimo, J.**, et al. (2023). "Use of risk-based cervical screening programs in resource-limited settings." *Cancer Epidemiol*, 84:102369. [PMID: 37105017](https://pubmed.ncbi.nlm.nih.gov/37105017/)

*For a complete list of publications, please visit our [lab website](https://qtim-lab.github.io/).*

## Our Research Focus

- **Cervical cancer detection and diagnosis**
- **Mobile applications for cervical health**
- **AI model deployment and optimization**
- **Generalizability studies across populations**
- **Cervical dynamics analysis**

## Research Projects

{% for project in site.projects %}
- **[{{ project.title }}]({{ project.url | relative_url }})** - {{ project.description }}
  {% if project.repo %}[View Repository]({{ project.repo }}){% endif %}
{% endfor %}

---
*QTIM Lab - Quantitative Translational Imaging in Medicine*