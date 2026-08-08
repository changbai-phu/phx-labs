---
title: Projects
icon: fas fa-folder
order: 1
---


<div class="project-grid">
  <div class="project-card">
    <h3>Research Compass</h3>
    <p>A Modular AI Platform for Literature Retrieval, Evaluation, and Research Assistance.(In Progress) </p>
    <div class="tags-container">
      <div class="tags">
        <a href="/tags/ai/" class="post-tag">AI</a>
        <a href="/tags/rag/" class="post-tag">RAG</a>
        <a href="/tags/llm/" class="post-tag">LLM</a>
      </div>
      <a href="https://github.com/changbai-phu/ResearchCompass" class="btn">View Project</a>
    </div>
  </div>
  <div class="project-card">
    <h3>Research Notes</h3>
    <p>A structured repo documenting my study, paper reviews, and technical notes on quantum computing and related research. (In Progress) </p>
    <div class="tags-container">
      <div class="tags">
        <a href="/tags/quantum-computing/" class="post-tag">Quantum Computing</a>
        <a href="/tags/research/" class="post-tag">Research</a>
      </div>
      <a href="https://github.com/changbai-phu/ResearchNotes" class="btn">View Project</a>
    </div>
  </div>
  <div class="project-card">
    <h3>Claw Morning</h3>
    <p>A CLI tool that generates automated daily research briefings by aggregating updates from multiple research and developer sources into a structured HTML report delivered to Feishu on a schedule.</p>
    <div class="tags-container">
      <div class="tags">
        <a href="/tags/scripts/" class="post-tag">Scripts</a>
        <a href="/tags/scheduled/" class="post-tag">Scheduled</a>
        <a href="/tags/openclaw/" class="post-tag">OpenClaw</a>
      </div>
      <a href="https://github.com/changbai-phu/claw-morning-local" class="btn">View Project</a>
    </div>
  </div>
  <div class="project-card">
    <h3>News Trend Analyzer</h3>
    <p>A production-style news analysis pipeline that ingests RSS feeds, performs sentiment and topic analysis, and visualizes trends in a real-time dashboard.</p>
    <div class="tags-container">
      <div class="tags">
        <a href="/tags/python/" class="post-tag">Python</a>
        <a href="/tags/docker/" class="post-tag">Docker</a>
        <a href="/tags/airflow/" class="post-tag">Airflow</a>
        <a href="/tags/cicd/" class="post-tag">CI/CD</a>
      </div>
      <a href="https://github.com/changbai-phu/news-trend-analyzer" class="btn">View Project</a>
    </div>
  </div>
  <div class="project-card">
    <h3>SimEQ</h3>
    <p>A GenAI-powered system designed to simulate realistic earthquake scenarios and generate actionable response plans from real-world disaster reports, aiming to support and enhance disaster management efforts.</p>
    <div class="tags-container">
      <div class="tags">
        <a href="/tags/genai/" class="post-tag">GenAI</a>
        <a href="/tags/rag/" class="post-tag">RAG</a>
        <a href="/tags/prompting/" class="post-tag">Prompting</a>
      </div>
      <a href="https://github.com/changbai-phu/SimEQ" class="btn">View Project</a>
    </div>
  </div>
</div>

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.project-card {
  border: 1px solid #eaeaea;
  border-radius: 8px;
  padding: 1.5rem;
  background: white;
  box-shadow: 0 2px 10px rgba(0,0,0,0.05);
  transition: transform 0.2s, box-shadow 0.2s;
  display: flex;
  flex-direction: column;
  height: 100%;
  min-height: 200px; /* Ensure minimum height for consistent layout */
}

.project-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 20px rgba(0,0,0,0.1);
}

.tags-container {
  display: flex;
  flex-direction: column;
  margin-top: auto;
  width: 100%;
}

.tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-bottom: 0.5rem; /* Reduced margin to minimize space */
  align-items: center;
  justify-content: flex-start; /* Align content to start */
}

.btn {
  display: inline-block;
  background: #2a7ae2;
  color: white;
  padding: 0.5rem 1rem;
  border-radius: 4px;
  text-decoration: none;
  font-weight: bold;
  align-self: flex-start; /* Align button to the start */
  margin-top: 0.25rem; /* Small margin between tags and button */
}

.btn:hover {
  background: #54a3ec;
  color: white;
}

.post-tag {
  display: inline-block;
  background: #f8f9fa; /* Light grayish-white background */
  color: #6c757d; /* Gray text */
  padding: 0.25rem 0.75rem;
  border-radius: 1rem;
  font-size: 0.8rem;
  text-decoration: none;
  transition: all 0.2s ease;
  border: 1px solid #dee2e6; /* Subtle border */
}

.post-tag:hover {
  background: #e9ecef; /* Slightly darker on hover */
  color: #495057; /* Darker gray text on hover */
  text-decoration: none;
}
</style>