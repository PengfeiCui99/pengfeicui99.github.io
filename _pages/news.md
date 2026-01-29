---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

<div class="news-page-wrapper">
<div class="notice--info" style="margin: 1.5em 0 0em 0; padding: 1em; background-color: #e3f2fd; border: 1px solid #2196f3; border-radius: 4px; display: flex; align-items: flex-start; gap: 0.5em;">
  <div style="flex-shrink: 0; width: 24px; height: 24px; background-color: #2196f3; border-radius: 50%; display: flex; align-items: center; justify-content: center; color: white; font-weight: bold; font-size: 1.0em;">i</div>
  <div style="flex: 1; font-size: 1.1em;">
    <strong>Pengfei Cui</strong> is a Lecturer at the College of Metropolitan Transportation, Beijing University of Technology.
    His research focuses on urban regeneration, integrated transportation–energy systems, and traffic safety.
    He welcomes collaboration on related research projects (Tel: +86-13722119206, Email: <a href="mailto:pengfeicui@bjut.edu.cn">pengfeicui@bjut.edu.cn</a>).
  </div>
</div>


  <div class="news-item">
    <span class="news-date"><strong>10/2025:</strong></span>
    <span class="news-text">New paper published at <em>Transportation Research Part C</em> that proposes a new <strong>Multiscale Geographical Random Forest</strong> for macro traffic safety spatial modeling integrating street-view semantic visual features. Check it <a href="https://www.sciencedirect.com/science/article/pii/S0968090X25003031" target="_blank" rel="noopener noreferrer">here</a>!</span>
  </div>

 <div class="news-item">
    <span class="news-date"><strong>10/2025:</strong></span>
    <span class="news-text">Corresponding-author paper in <em>Transportmetrica A: Transport Science</em> analyzing spatiotemporal disparities in macro‑ and microscopic properties of motorcycle injury levels.</span>
  </div>

<div class="news-scroll-container">
  <div class="news-item">
    <span class="news-date"><strong>07/2025:</strong></span>
    <span class="news-text">Joined the <strong>College of Metropolitan Transportation</strong> at <strong>Beijing University of Technology</strong> as a <strong>Lecturer</strong>, focusing on urban regeneration, integrated transportation–energy systems, and traffic safety.</span>
  </div>


  <div class="news-item">
    <span class="news-date"><strong>-04/2025:</strong></span>
    <span class="news-text">First-author paper published in <em>Transport Policy</em> examining how spatial inequality in socio‑demographic and commuting patterns affects traffic crash rates using interpretable machine learning and spatial statistical models.
    Check it <a href="https://doi.org/10.1016/j.tranpol.2025.03.033" target="_blank" rel="noopener noreferrer">here</a>!
    </span>
  </div>


  <div class="news-item">
    <span class="news-date"><strong>01/2025:</strong></span>
    <span class="news-text">First-author paper published in <em>Accident Analysis &amp; Prevention</em> quantifying spatial inequities in traffic injury rates through integrated urban road network measures and social vulnerability indices.
    Check it <a href="https://doi.org/10.1016/j.aap.2025.107916" target="_blank" rel="noopener noreferrer">here</a>!
    </span>
  </div>

  <div class="news-item">
    <span class="news-date"><strong>03/2024:</strong></span>
    <span class="news-text">First-author paper published in <em>Accident Analysis &amp; Prevention</em> proposing a sparse spatio‑temporal dynamic learning network for urban traffic accident risk forecasting.</span>
  </div>

</div>
</div>

<style>
/* Add right margin limit for News page (same as Home page) */
@media (min-width: 64em) {
  body .archive {
    max-width: calc(83.333% - 16.666%);
    margin-right: 16.666%;
  }
}

.news-scroll-container {
  margin-top: 0em;
  margin-bottom: 1.5em;
  max-height: calc(100vh - 290px);
  min-height: 600px;
  overflow-y: auto;
  overflow-x: hidden;
  border: 1px solid var(--global-border-color);
  border-radius: 4px;
  padding: 0.8em;
  background-color: var(--global-bg-color);
}

.news-scroll-container::-webkit-scrollbar {
  width: 8px;
}

.news-scroll-container::-webkit-scrollbar-track {
  background: var(--global-border-color);
  border-radius: 4px;
}

.news-scroll-container::-webkit-scrollbar-thumb {
  background: #2196f3;
  border-radius: 4px;
}

.news-scroll-container::-webkit-scrollbar-thumb:hover {
  background: #1976d2;
}

.news-item {
  display: flex;
  align-items: flex-start;
  padding: 0.8em 0.5em;
  margin: 0 -0.5em;
  border-bottom: 1px solid var(--global-border-color);
  border-left: 3px solid transparent;
  font-size: 1em;
  line-height: 1.6;
  transition: all 0.2s ease-in-out;
  cursor: default;
  color: var(--global-text-color);
  background-color: transparent;
}

.news-item:hover {
  background-color: rgba(33, 150, 243, 0.08);
  border-left-color: var(--global-link-color);
  border-radius: 4px;
  padding-left: 0.8em;
  box-shadow: 0 1px 4px rgba(0, 0, 0, 0.1);
  transform: translateX(2px);
}

html[data-theme="dark"] .news-item:hover {
  background-color: rgba(255, 255, 255, 0.05);
  box-shadow: 0 1px 4px rgba(0, 0, 0, 0.3);
}

.news-item:active {
  background-color: rgba(33, 150, 243, 0.12);
  border-left-color: var(--global-link-color);
}

html[data-theme="dark"] .news-item:active {
  background-color: rgba(255, 255, 255, 0.08);
}

.news-item:last-child {
  border-bottom: none;
}

.news-date {
  flex-shrink: 0;
  margin-right: 0.8em;
  min-width: 80px;
  color: var(--global-text-color);
  font-weight: 600;
}

.news-text {
  flex: 1;
  color: var(--global-text-color);
}

.news-text a {
  color: var(--global-link-color);
  text-decoration: none;
  border-bottom: 1px solid transparent;
  transition: all 0.2s ease-in-out;
}

.news-text a:hover {
  color: var(--global-link-color-hover);
  border-bottom-color: var(--global-link-color-hover);
}

.news-text strong {
  color: var(--global-text-color);
  font-weight: 600;
}

.news-text a strong {
  color: var(--global-link-color);
  font-weight: 600;
}

.news-text a:hover strong {
  color: var(--global-link-color-hover);
}
</style>

