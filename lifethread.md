---
layout: page
title: Life Thread
permalink: /lifethread/
---

<style>
.timeline {
  position: relative;
  padding: 20px 0;
  max-width: 800px;
  margin: 0 auto;
}

.timeline:before {
  content: '';
  position: absolute;
  left: 30px;
  top: 0;
  bottom: 0;
  width: 3px;
  background: linear-gradient(to bottom, #007acc, #28a745);
}

.timeline-item {
  position: relative;
  margin-bottom: 50px;
  padding-left: 80px;
}

.timeline-item:last-child {
  margin-bottom: 0;
}

.timeline-marker {
  position: absolute;
  left: -80px;
  top: 5px;
  width: 24px;
  height: 24px;
  border-radius: 50%;
  border: 4px solid #fff;
  box-shadow: 0 0 0 4px #e0e0e0;
  z-index: 2;
}

.timeline-marker.education {
  background: #28a745;
}

.timeline-marker.work {
  background: #007acc;
}

.timeline-marker.project {
  background: #ffc107;
}

.timeline-marker.achievement {
  background: #dc3545;
}

.timeline-content {
  background: #f8f9fa;
  border-radius: 12px;
  padding: 25px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  border-left: 4px solid #007acc;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.timeline-content:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 12px rgba(0,0,0,0.15);
}

.timeline-date {
  font-size: 0.9em;
  color: #6c757d;
  font-weight: 700;
  margin-bottom: 8px;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

.timeline-title {
  margin: 0 0 8px 0;
  color: #333;
  font-size: 1.3em;
  font-weight: 600;
}

.timeline-organization {
  font-weight: 600;
  color: #007acc;
  margin-bottom: 4px;
  font-size: 1.1em;
}

.timeline-location {
  font-size: 0.9em;
  color: #6c757d;
  margin-bottom: 15px;
  font-style: italic;
}

.timeline-description {
  margin: 0;
  line-height: 1.6;
  color: #555;
}

.timeline-skills {
  margin-top: 15px;
}

.skill-tag {
  display: inline-block;
  background: #e3f2fd;
  color: #1976d2;
  padding: 4px 12px;
  border-radius: 20px;
  font-size: 0.8em;
  margin: 2px 4px 2px 0;
  font-weight: 500;
}

@media (max-width: 768px) {
  .timeline:before {
    left: 20px;
  }
  
  .timeline-item {
    padding-left: 60px;
  }
  
  .timeline-marker {
    left: -60px;
    width: 20px;
    height: 20px;
  }
  
  .timeline-content {
    padding: 20px;
  }
}
</style>

<div class="timeline">
  
  <div class="timeline-item">
    <div class="timeline-marker education"></div>
    <div class="timeline-content">
      <div class="timeline-date">2025 - Present</div>
      <h3 class="timeline-title">Master's Thesis</h3>
      <div class="timeline-organization">National University of Singapore (NUS)</div>
      <div class="timeline-location">Singapore</div>
      <p class="timeline-description">
        Currently completing my Applied Mathematics Master's thesis, focusing on the intersection of quantitative finance and AI. Exploring advanced applications of machine learning in financial modeling and risk assessment.
      </p>
      <div class="timeline-skills">
        <span class="skill-tag">Quantitative Finance</span>
        <span class="skill-tag">Machine Learning</span>
        <span class="skill-tag">Research</span>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-marker education"></div>
    <div class="timeline-content">
      <div class="timeline-date">2023 - 2025</div>
      <h3 class="timeline-title">Master's in Applied Mathematics</h3>
      <div class="timeline-organization">ETH Zurich</div>
      <div class="timeline-location">Zurich, Switzerland</div>
      <p class="timeline-description">
        Specialized in quantitative finance, AI, and machine learning with particular focus on generative AI and large language models (LLMs). Developed expertise in mathematical modeling, statistical analysis, and computational methods.
      </p>
      <div class="timeline-skills">
        <span class="skill-tag">Applied Mathematics</span>
        <span class="skill-tag">AI/ML</span>
        <span class="skill-tag">LLMs</span>
        <span class="skill-tag">Python</span>
        <span class="skill-tag">Statistical Analysis</span>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-marker project"></div>
    <div class="timeline-content">
      <div class="timeline-date">2024</div>
      <h3 class="timeline-title">LLM Fine-tuning Project</h3>
      <div class="timeline-organization">Personal Research</div>
      <div class="timeline-location">Remote</div>
      <p class="timeline-description">
        Developed and fine-tuned large language models to discover hidden patterns in financial data. Implemented novel approaches to improve model performance and interpretability in quantitative analysis.
      </p>
      <div class="timeline-skills">
        <span class="skill-tag">Deep Learning</span>
        <span class="skill-tag">NLP</span>
        <span class="skill-tag">Data Analysis</span>
        <span class="skill-tag">PyTorch</span>
      </div>
    </div>
  </div>

  <!-- Add your earlier education/work experiences here -->
  <div class="timeline-item">
    <div class="timeline-marker education"></div>
    <div class="timeline-content">
      <div class="timeline-date">2020 - 2023</div>
      <h3 class="timeline-title">Bachelor's Degree</h3>
      <div class="timeline-organization">Your Previous University</div>
      <div class="timeline-location">Location</div>
      <p class="timeline-description">
        Foundation in mathematics and computer science. Developed strong analytical