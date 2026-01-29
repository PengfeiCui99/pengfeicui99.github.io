---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<style>
.cv-pdf-button {
  position: absolute;
  right: 0em;
  top: 50%;
  transform: translateY(-50%);
  display: inline-flex;
  align-items: center;
  gap: 0.25em;
  padding: 0.25em 0.5em;
  background-color: var(--global-link-color);
  color: white;
  text-decoration: none;
  border-radius: 3px;
  font-weight: 500;
  font-size: 0.75em;
  transition: all 0.3s ease;
  box-shadow: 0 2px 4px rgba(25, 118, 210, 0.2);
  z-index: 10;
  height: fit-content;
  line-height: 1.2;
  flex-shrink: 0;
}

.cv-pdf-button:hover {
  background-color: #1565c0;
  box-shadow: 0 4px 8px rgba(25, 118, 210, 0.3);
  transform: translateY(-50%);
  color: white;
  text-decoration: none;
}

.archive .page__title {
  position: relative;
  padding-right: 100px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  min-height: 1.2em;
  gap: 1em;
}

/* Add right margin limit for CV page only */
@media (min-width: 925px) {
  .archive {
    max-width: calc(83.333% - 16.666%);
    margin-right: 16.666%;
  }
}

.cv-card-container {
  display: flex;
  flex-direction: column;
  gap: 0.8em;
  margin-top: 1em;
}

.cv-card {
  background-color: var(--global-bg-color);
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
  padding: 1em 1.2em;
  transition: box-shadow 0.3s ease;
  border: 1px solid var(--global-border-color);
}

.cv-card:hover {
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
}

html[data-theme="dark"] .cv-card {
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.3);
}

html[data-theme="dark"] .cv-card:hover {
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.4);
}

.cv-card-title {
  font-size: 1.2em;
  font-weight: 600;
  margin-bottom: 1em;
  color: var(--global-text-color);
  border-bottom: 2px solid var(--global-link-color);
  padding-bottom: 0.5em;
}

/* Collapsible details styling */
.cv-card details {
  width: 100%;
}

.cv-card summary {
  font-size: 1.2em;
  font-weight: 600;
  margin-bottom: 0;
  color: var(--global-text-color);
  border-bottom: 2px solid var(--global-link-color);
  padding-bottom: 0.3em;
  cursor: pointer;
  list-style: none;
  position: relative;
  padding-right: 2em;
  user-select: none;
}

.cv-card summary::-webkit-details-marker {
  display: none;
}

.cv-card summary::before {
  content: '▶';
  position: absolute;
  right: 0;
  color: var(--global-link-color);
  font-size: 0.8em;
  transition: transform 0.3s ease;
  top: 50%;
  transform: translateY(-50%);
}

.cv-card details[open] summary::before {
  transform: translateY(-50%) rotate(90deg);
}

.cv-card details[open] summary {
  margin-bottom: 0.8em;
}

.cv-card-content {
  color: var(--global-text-color);
  line-height: 1.6;
}

.cv-card-content p {
  color: var(--global-text-color);
}

.cv-card-content span {
  color: var(--global-text-color);
}

.cv-card-content p {
  margin-bottom: 0.8em;
}

.cv-card-content p:last-of-type {
  margin-bottom: 0.3em;
}

.cv-card-content ul {
  margin: 0;
  padding-left: 1.5em;
}

.cv-card-content li {
  margin-bottom: 0em;
}

.cv-education-item {
  margin-bottom: 1.5em;
  display: flex;
  gap: 1.5em;
  align-items: flex-start;
}

.cv-education-logo {
  flex-shrink: 0;
  width: 80px;
  height: 80px;
  border-radius: 4px;
  object-fit: contain;
  display: block;
  transition: opacity 0.3s ease;
  background-color: var(--global-bg-color);
  padding: 4px;
  border: 1px solid var(--global-border-color);
}

/* Hide logo on mobile devices */
@media (max-width: 768px) {
  .cv-education-logo {
    display: none;
  }
  
  .cv-education-item a {
    display: none;
  }
  
  .cv-education-item {
    gap: 0;
  }
  
  .cv-education-content {
    padding-left: 0;
    border-left: none;
  }
}

.cv-education-item a {
  display: block;
  text-decoration: none;
}

.cv-education-item a:hover .cv-education-logo {
  opacity: 0.8;
}

.cv-education-content {
  flex: 1;
  padding-left: 1em;
  border-left: 3px solid var(--global-link-color);
}

.cv-education-item:last-child {
  margin-bottom: 0;
}

.cv-education-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 0.3em;
}

.cv-education-left {
  flex: 1;
}

.cv-education-degree {
  font-weight: 600;
  color: var(--global-link-color);
  margin-bottom: 0.2em;
}

.cv-education-university {
  font-weight: 600;
  color: var(--global-text-color);
  font-size: 0.95em;
}

.cv-education-meta {
  text-align: right;
  color: var(--global-text-color);
  font-size: 0.9em;
  white-space: nowrap;
  margin-left: 1em;
}

.cv-education-details {
  color: var(--global-text-color);
  font-size: 0.95em;
}

.cv-project-item {
  margin-bottom: 1.5em;
  padding-left: 1em;
  border-left: 3px solid var(--global-link-color);
}

.cv-project-item:last-child {
  margin-bottom: 0;
}

.cv-project-title {
  font-weight: 600;
  color: var(--global-link-color);
  margin-bottom: 0.3em;
}

.cv-project-title a {
  color: var(--global-link-color);
  text-decoration: none;
  transition: color 0.3s ease;
}

.cv-project-title a:hover {
  color: var(--global-link-color-hover);
  text-decoration: underline;
}

.cv-project-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 0.3em;
}

.cv-project-sponsor {
  font-weight: 600;
  color: var(--global-text-color);
  font-size: 0.95em;
  flex: 1;
}

.cv-project-meta {
  text-align: right;
  color: var(--global-text-color);
  font-size: 0.9em;
  white-space: nowrap;
  margin-left: 1em;
}

.cv-project-description {
  color: var(--global-text-color);
  font-size: 0.95em;
  margin-top: 0.5em;
}

.cv-project-description ul {
  margin: 0.5em 0;
  padding-left: 1.5em;
}

.cv-project-description li {
  margin-bottom: 0.3em;
}

.cv-project-section-title {
  font-size: 1em;
  font-weight: 600;
  color: var(--global-text-color);
  margin-top: 1.5em;
  margin-bottom: 1em;
}

.cv-project-section-title:first-child {
  margin-top: 0;
}

.cv-publication-year {
  font-size: 1em;
  font-weight: 600;
  color: var(--global-text-color);
  margin-top: 0.5em;
  margin-bottom: 0.3em;
}

.cv-publication-year:first-of-type {
  margin-top: 0;
}

.cv-service-section {
  margin-bottom: 1.5em;
}

.cv-service-section:last-child {
  margin-bottom: 0;
}

.cv-service-section-title {
  font-size: 1em;
  font-weight: 600;
  color: var(--global-text-color);
  margin-top: 0;
  margin-bottom: 0.8em;
  padding-bottom: 0.3em;
  border-bottom: 1px solid var(--global-border-color);
}

.cv-service-list {
  list-style: none;
  padding-left: 0;
  margin: 0;
}

.cv-service-list li {
  margin-bottom: 0.5em;
  padding-left: 1.2em;
  position: relative;
  color: var(--global-text-color);
}

.cv-service-list li:before {
  content: "•";
  position: absolute;
  left: 0;
  color: var(--global-link-color);
  font-weight: bold;
  font-size: 1.2em;
}

.cv-service-list li:last-child {
  margin-bottom: 0;
}

.cv-service-list li a {
  color: var(--global-link-color);
  text-decoration: none;
  transition: color 0.3s ease;
}

.cv-service-list li a:hover {
  color: var(--global-link-color-hover);
  text-decoration: underline;
}

.cv-reference-item {
  display: flex;
  gap: 1.5em;
  margin-bottom: 2em;
  align-items: flex-start;
}

.cv-reference-item:last-child {
  margin-bottom: 0;
}

.cv-reference-photo {
  flex-shrink: 0;
  width: 120px;
  height: 160px;
  border-radius: 4px;
  object-fit: cover;
  border: 2px solid var(--global-border-color);
  transition: opacity 0.3s ease, transform 0.3s ease;
  cursor: pointer;
}

.cv-reference-item a {
  display: block;
  text-decoration: none;
}

.cv-reference-item a:hover .cv-reference-photo {
  opacity: 0.8;
  transform: scale(1.02);
}

.cv-reference-content {
  flex: 1;
  min-width: 0;
}

.cv-reference-name {
  font-weight: 600;
  color: var(--global-link-color);
  font-size: 1.05em;
  margin-bottom: 0.3em;
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  gap: 1em;
}

.cv-reference-relationship {
  color: var(--global-text-color-light);
  font-size: 0.85em;
  font-style: italic;
  font-weight: normal;
  white-space: nowrap;
}

.cv-reference-email {
  color: var(--global-text-color);
  font-size: 0.9em;
  margin-bottom: 0.5em;
}

.cv-reference-details {
  color: var(--global-text-color);
  font-size: 0.95em;
  line-height: 1.6;
  margin-bottom: 0.3em;
}


@media (max-width: 768px) {
  .cv-reference-item {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }
  
  .cv-reference-photo {
    width: 100px;
    height: 130px;
  }
}

.cv-award-item {
  margin-bottom: 0.6em;
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  padding-left: 1.2em;
  position: relative;
}

.cv-award-item:before {
  content: "•";
  position: absolute;
  left: 0;
  color: var(--global-link-color);
  font-weight: bold;
  font-size: 1.2em;
}

.cv-award-item:last-child {
  margin-bottom: 0;
}

.cv-award-name {
  font-weight: 400;
  color: var(--global-text-color);
  flex: 1;
  padding-right: 1em;
}

.cv-award-name strong {
  font-weight: 600;
  color: var(--global-link-color);
}

.cv-award-name strong a {
  color: var(--global-link-color);
  text-decoration: none;
  transition: color 0.3s ease;
}

.cv-award-name strong a:hover {
  color: var(--global-link-color-hover);
  text-decoration: underline;
}

.cv-award-name em {
  font-weight: 400;
  font-style: italic;
  color: var(--global-text-color);
}

.cv-award-date {
  color: var(--global-text-color);
  font-size: 0.9em;
  white-space: nowrap;
  text-align: right;
}

@media (max-width: 768px) {
  .cv-pdf-button {
    position: static;
    margin-top: 1em;
    display: inline-flex;
  }
  
  .archive .page__title {
    padding-right: 0;
  }
  
  .cv-card {
    padding: 0.8em 1em;
  }
}
</style>

<div class="cv-card-container">

  <!-- Work Experience Card -->
  <div class="cv-card">
    <details open>
      <summary>Work Experience</summary>
      <div class="cv-card-content">
      <div class="cv-education-item">
        <a href="https://www.bjut.edu.cn/" target="_blank" rel="noopener noreferrer">
          <img src="/images/bjut-logo.png" alt="BJUT Logo" class="cv-education-logo">
        </a>
        <div class="cv-education-content">
          <div class="cv-education-header">
            <div class="cv-education-left">
              <div class="cv-education-degree">Lecturer</div>
              <div class="cv-education-university">Beijing University of Technology</div>
            </div>
            <div class="cv-education-meta">
              July 2025 - Present<br>
              Beijing, China
            </div>
          </div>
          <div class="cv-education-details">
            College of Metropolitan Transportation
          </div>
        </div>
      </div>
      </div>
    </details>
  </div>
  
  <!-- Education Card -->
  <div class="cv-card">
    <details open>
      <summary>Education</summary>
      <div class="cv-card-content">
      <div class="cv-education-item">
        <a href="https://www.bjtu.edu.cn/" target="_blank" rel="noopener noreferrer">
          <img src="/images/bjtu-logo.png" alt="BJTU Logo" class="cv-education-logo">
        </a>
        <div class="cv-education-content">
          <div class="cv-education-header">
            <div class="cv-education-left">
              <div class="cv-education-degree">Ph.D. in Systems Science</div>
              <div class="cv-education-university">Beijing Jiaotong University</div>
            </div>
            <div class="cv-education-meta">
              September 2021 - June 2025<br>
              Beijing, China
            </div>
          </div>
          <div class="cv-education-details">
            Advised by Prof. Xiaobao Yang<br>
            <em>Dissertation: Research on Key Technologies of Urban Road Traffic System Risk Evolution and Spatial-temporal Network Modeling</em>
          </div>
        </div>
      </div>
      <div class="cv-education-item">
        <a href="https://www.ucf.edu/" target="_blank" rel="noopener noreferrer">
          <img src="/images/ucf-logo.png" alt="UCF Logo" class="cv-education-logo">
        </a>
        <div class="cv-education-content">
          <div class="cv-education-header">
            <div class="cv-education-left">
              <div class="cv-education-degree">Visiting Scholar</div>
              <div class="cv-education-university">University of Central Florida</div>
            </div>
            <div class="cv-education-meta">
              November 2023 - November 2024<br>
              Orlando, USA
            </div>
          </div>
          <div class="cv-education-details">
            Advised by Prof. Mohamed Abdel-Aty<br>
            Smart & Safe Transportation Lab (SST Lab)
          </div>
        </div>
      </div>
      <div class="cv-education-item">
        <a href="https://www.bjtu.edu.cn/" target="_blank" rel="noopener noreferrer">
          <img src="/images/bjtu-logo.png" alt="BJTU Logo" class="cv-education-logo">
        </a>
        <div class="cv-education-content">
          <div class="cv-education-header">
            <div class="cv-education-left">
              <div class="cv-education-degree">M.S. in Transportation Planning and Management</div>
              <div class="cv-education-university">Beijing Jiaotong University</div>
            </div>
            <div class="cv-education-meta">
              September 2019 - June 2021<br>
              Beijing, China
            </div>
          </div>
          <div class="cv-education-details">
            Advised by Prof. Lu Ma<br>
            <em>Successive M.S.-Ph.D. Program</em>
          </div>
        </div>
      </div>
      <div class="cv-education-item">
        <a href="https://www.dlmu.edu.cn/" target="_blank" rel="noopener noreferrer">
          <img src="/images/dlmu-logo.png" alt="DLMU Logo" class="cv-education-logo">
        </a>
        <div class="cv-education-content">
          <div class="cv-education-header">
            <div class="cv-education-left">
              <div class="cv-education-degree">B.S. in Traffic Management</div>
              <div class="cv-education-university">Dalian Maritime University</div>
            </div>
            <div class="cv-education-meta">
              September 2015 - June 2019<br>
              Dalian, China
            </div>
          </div>
        </div>
      </div>
      </div>
    </details>
  </div>

  <!-- Research Interests Card -->
  <div class="cv-card">
    <details open>
      <summary>Research Interests</summary>
      <div class="cv-card-content">
      <p><strong>Research Areas</strong><br>
      Urban traffic system risk evolution; Spatiotemporal network modeling; Accident causation analysis; Visual semantic analysis.</p>
      
      <p><strong>Methodology</strong><br>
      Machine learning & deep learning; Spatial statistics; Econometric models; Computer vision.</p>
      
      <p><strong>Working Topics</strong></p>
      <ul>
        <li>Macro-level traffic safety modeling integrating street-view semantic visual features</li>
        <li>Spatial inequity analysis in traffic injury rates</li>
        <li>Crash frequency and severity modeling with heterogeneity</li>
      </ul>
      </div>
    </details>
  </div>

  <!-- Honors and Awards Card -->
  <div class="cv-card">
    <details open>
      <summary>Honors and Awards</summary>
      <div class="cv-card-content">
      <div class="cv-award-item">
        <span class="cv-award-name"><strong>ESI Highly Cited Paper (Top 1%)</strong>, 2 papers in Accident Analysis & Prevention</span>
        <span class="cv-award-date">2024-2025</span>
      </div>
      <div class="cv-award-item">
        <span class="cv-award-name"><strong>Outstanding Graduate Student</strong>, Beijing Jiaotong University</span>
        <span class="cv-award-date">2025</span>
      </div>
      <div class="cv-award-item">
        <span class="cv-award-name"><strong>China Scholarship Council (CSC) Award</strong>, for visiting research at UCF</span>
        <span class="cv-award-date">2023-2024</span>
      </div>
      </div>
    </details>
  </div>

  <!-- Publications Card -->
  <div class="cv-card">
    <details open>
      <summary>Publications</summary>
      <div class="cv-card-content">
      {% assign sorted_publications = site.publications | sort: 'year' | reverse %}
      {% assign current_year = '' %}
      {% for post in sorted_publications %}
        {% assign post_year = post.year %}
        {% unless post_year %}
          {% assign post_year = post.date | date: '%Y' %}
        {% endunless %}
        {% if post_year != current_year %}
          {% if current_year != '' %}
            </ul>
          {% endif %}
          <h3 class="cv-publication-year">{{ post_year }}</h3>
          <ul>
          {% assign current_year = post_year %}
        {% endif %}
    {% include archive-single-cv.html %}
      {% endfor %}
      </ul>
      </div>
    </details>
  </div>

  <!-- Academic Services Card -->
  <div class="cv-card">
    <details open>
      <summary>Academic Services</summary>
      <div class="cv-card-content">
      <div class="cv-service-section">
        <h3 class="cv-service-section-title">Journal Reviewer</h3>
        <ul class="cv-service-list">
          <li><a href="https://www.nature.com/ncomms/" target="_blank" rel="noopener noreferrer">Nature Communications</a> </li>
          <li><a href="https://www.journals.elsevier.com/transportation-research-part-c-emerging-technologies" target="_blank" rel="noopener noreferrer">Transportation Research Part C: Emerging Technologies</a> </li>
          <li><a href="https://www.journals.elsevier.com/accident-analysis-and-prevention" target="_blank" rel="noopener noreferrer">Accident Analysis & Prevention</a> </li>
          <li><a href="https://www.journals.elsevier.com/transport-policy" target="_blank" rel="noopener noreferrer">Transport Policy</a> </li>
          <li><a href="https://www.sciencedirect.com/journal/reliability-engineering-and-system-safety" target="_blank" rel="noopener noreferrer">Reliability Engineering & System Safety</a> </li>
        </ul>
      </div>
      </div>
    </details>
  </div>

  <!-- Skills Card -->
  <div class="cv-card">
    <details open>
      <summary>Skills</summary>
      <div class="cv-card-content">
      <ul>
        <li><strong>Programming:</strong> Python, R, STATA, LaTeX</li>
        <li><strong>Software & Tools:</strong> ArcGIS Pro, QGIS, VS Code, Cursor, RStudio, Zotero, Overleaf, Microsoft Office</li>
        <li><strong>Languages:</strong> Chinese (Native), English (Fluent)</li>
      </ul>
      </div>
    </details>
  </div>

  <!-- References Card -->
  <div class="cv-card">
    <details open>
      <summary>References</summary>
      <div class="cv-card-content">
      <div class="cv-reference-item">
        <a href="https://faculty.bjtu.edu.cn/8012/" target="_blank" rel="noopener noreferrer">
          <img src="/images/references/xiaobao-yang.jpg" alt="Prof. Xiaobao Yang" class="cv-reference-photo" onerror="this.style.display='none'">
        </a>
        <div class="cv-reference-content">
          <div class="cv-reference-name">
            <span>1. Prof. Xiaobao Yang</span>
            <span class="cv-reference-relationship">Ph.D. Advisor</span>
          </div>
          <div class="cv-reference-email">yangxb@bjtu.edu.cn</div>
          <div class="cv-reference-details">
            Professor at School of System Science, Beijing Jiaotong University
        
          </div>
        </div>
      </div>
      
      <div class="cv-reference-item">
        <a href="https://faculty.bjtu.edu.cn/8503/" target="_blank" rel="noopener noreferrer">
          <img src="/images/references/lu-ma.jpg" alt="Prof. Lu Ma" class="cv-reference-photo" onerror="this.style.display='none'">
        </a>
        <div class="cv-reference-content">
          <div class="cv-reference-name">
            <span>2. Prof. Lu Ma</span>
            <span class="cv-reference-relationship">M.S. Advisor</span>
          </div>
          <div class="cv-reference-email">lum@bjtu.edu.cn</div>
          <div class="cv-reference-details">
            Professor at School of Traffic and Transportation, Beijing Jiaotong University
          </div>
        </div>
      </div>
      
      <div class="cv-reference-item">
        <a href="https://www.cecs.ucf.edu/faculty/mohamed-abdel-aty/" target="_blank" rel="noopener noreferrer">
          <img src="/images/references/abdel-aty.jpg" alt="Prof. Mohamed Abdel-Aty" class="cv-reference-photo" onerror="this.style.display='none'">
        </a>
        <div class="cv-reference-content">
          <div class="cv-reference-name">
            <span>3. Prof. Mohamed Abdel-Aty</span>
            <span class="cv-reference-relationship">Visiting Advisor</span>
          </div>
          <div class="cv-reference-email">M.Aty@ucf.edu</div>
          <div class="cv-reference-details">
            Pegasus Professor, Trustee Endowed Chair & former Chair of CECE Department, UCF<br>
            Director of Smart & Safe Transportation Lab (SST Lab)<br>
            Editor Emeritus of Accident Analysis & Prevention
          </div>
        </div>
      </div>
      </div>
    </details>
  </div>

</div>

