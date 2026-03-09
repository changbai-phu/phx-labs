---
title: Projects
icon: fas fa-folder
order: 1
---


<div class="project-grid">
  <div class="project-card">
    <h3>AI Digest</h3>
    <p>Multi-agent workflow for curating and analyzing AI research papers with GPT-4 integration.</p>
    <div class="tags">
      <span class="tag">Python</span>
      <span class="tag">LangGraph</span>
      <span class="tag">GPT-4</span>
    </div>
    <a href="#" class="btn">View Project</a>
  </div>
  <div class="project-card">
    <h3>News Trend Analysis</h3>
    <p>Real-time news aggregation and trend analysis system using NLP and sentiment analysis.</p>
    <div class="tags">
      <span class="tag">JavaScript</span>
      <span class="tag">NLP</span>
      <span class="tag">APIs</span>
    </div>
    <a href="#" class="btn">View Project</a>
  </div>
  <div class="project-card">
    <h3>Earthquake Monitor</h3>
    <p>Global earthquake monitoring system with real-time alerts and visualization dashboard.</p>
    <div class="tags">
      <span class="tag">Python</span>
      <span class="tag">APIs</span>
      <span class="tag">Dashboard</span>
    </div>
    <a href="#" class="btn">View Project</a>
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
}

.project-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 20px rgba(0,0,0,0.1);
}

.tags {
  margin: 1rem 0;
}

.tag {
  display: inline-block;
  background: #f0f0f0;
  padding: 0.25rem 0.75rem;
  border-radius: 20px;
  font-size: 0.8rem;
  margin-right: 0.5rem;
  color: #555;
}

.btn {
  display: inline-block;
  background: #2a7ae2;
  color: white;
  padding: 0.5rem 1rem;
  border-radius: 4px;
  text-decoration: none;
  font-weight: bold;
}

.btn:hover {
  background: #54a3ec;
  color: white;
}
</style>