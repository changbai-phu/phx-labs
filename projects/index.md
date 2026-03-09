---
layout: page
title: Projects
icon: fas fa-folder
---

<div class="projects-grid">
  <div class="project-card">
    <h3><a href="/projects/ai-digest/">AI Workflow & Multi-Agent Experimentation</a></h3>
    <p>Multi-agent AI workflow generating daily research/news briefings in customized topics such as quantum computing and AI, integrating multiple LLMs and feedback loops.</p>
    <div class="tags">
      <span class="tag">AI</span>
      <span class="tag">Multi-Agent</span>
      <span class="tag">LLM</span>
    </div>
  </div>

  <div class="project-card">
    <h3><a href="/projects/news-trend/">News Trend Analyzer</a></h3>
    <p>E2E pipeline fetching, analyzing, and visualizing trending news topics using Docker & Airflow.</p>
    <div class="tags">
      <span class="tag">Docker</span>
      <span class="tag">Airflow</span>
      <span class="tag">Data Pipeline</span>
    </div>
  </div>

  <div class="project-card">
    <h3><a href="/projects/earthquake/">GenAI Earthquake Simulation</a></h3>
    <p>Capstone project exploring disaster response simulation using GenAI.</p>
    <div class="tags">
      <span class="tag">GenAI</span>
      <span class="tag">Simulation</span>
    </div>
  </div>
</div>

<style>
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 1.5rem;
  padding: 1rem 0;
}

.project-card {
  background: var(--card-bg);
  border-radius: 0.5rem;
  padding: 1.5rem;
  border: 1px solid var(--main-border-color);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.project-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.project-card h3 {
  margin-top: 0;
  margin-bottom: 0.75rem;
}

.project-card h3 a {
  color: var(--text-color);
  text-decoration: none;
}

.project-card h3 a:hover {
  color: var(--primary-color);
}

.project-card p {
  color: var(--text-muted-color);
  font-size: 0.95rem;
  line-height: 1.6;
  margin-bottom: 1rem;
}

.project-card .tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.project-card .tag {
  background: var(--main-border-color);
  color: var(--text-muted-color);
  padding: 0.25rem 0.75rem;
  border-radius: 1rem;
  font-size: 0.8rem;
}
</style>