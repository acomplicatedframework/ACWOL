---
layout: default
title: ACWOL
---

<style>
body {
  background-color: black;
  color: #00ff00;
  font-family: "Courier New", monospace;
  margin: 0;
  padding: 60px 40px;
  opacity: 0;
  animation: fadeIn 1.2s ease forwards;
}

/* Fade-in */
@keyframes fadeIn {
  to { opacity: 1; }
}

/* Scanline effect */
body::before {
  content: "";
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  background: repeating-linear-gradient(
    to bottom,
    rgba(0,255,0,0.05),
    rgba(0,255,0,0.05) 1px,
    transparent 1px,
    transparent 3px
  );
}

/* Main Header Glow */
.acwol-header {
  font-size: 72px;
  font-weight: bold;
  text-shadow:
    0 0 10px #00ff00,
    0 0 20px #00ff00,
    0 0 40px #00ff00;
  margin-bottom: 20px;
}

/* Section Headers */
.section-title {
  font-size: 32px;
  margin-top: 60px;
  margin-bottom: 20px;
}

/* Links */
a {
  color: #00ff00;
  text-decoration: none;
}

a:hover {
  text-shadow: 0 0 10px #00ff00;
}

/* Divider */
hr {
  border: 0;
  border-top: 1px solid #00ff00;
  margin: 50px 0;
}
</style>

<div class="acwol-header">ACWOL</div>

Originally developed in 2009, ACWOL is the core framework for conscience-led decision-making, disciplined Intellect mining, and human-AI co-evolution.

All rights reserved to Leo Evolves.

---

<hr>

<div class="section-title">&gt; Core Framework</div>

> [Canon]({{ site.baseurl }}/canon.html)  
> [Structure]({{ site.baseurl }}/structure.html)  
> [Tenets]({{ site.baseurl }}/tenets.html)  
> [Tools]({{ site.baseurl }}/tools.html)  
> [Philosophy]({{ site.baseurl }}/philosophy.html)

<hr>

<div class="section-title">&gt; AI & Agents</div>

> [AI Alignment]({{ site.baseurl }}/ai-alignment.html)  
> [AI Agent Guidelines]({{ site.baseurl }}/ai-agent-guidelines.html)  
> [Agent Evaluation]({{ site.baseurl }}/agent-evaluation.html)

<hr>

<div class="section-title">&gt; Governance & Community</div>

> [Ethical License]({{ site.baseurl }}/ethical-license.html)  
> [Contributing (Humans)]({{ site.baseurl }}/contributing-humans.html)  
> [Contributing (AI)]({{ site.baseurl }}/contributing-ai.html)  
> [Roadmap]({{ site.baseurl }}/roadmap.html)  
> [Use Cases]({{ site.baseurl }}/use-cases.html)
