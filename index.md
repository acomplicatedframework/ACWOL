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
  padding: 40px;
  opacity: 0;
  animation: fadeIn 1.2s ease forwards;
}

/* Fade-in */
@keyframes fadeIn {
  to { opacity: 1; }
}

/* Glow Header */
.acwol-header {
  font-size: 72px;
  font-weight: bold;
  text-shadow:
    0 0 10px #00ff00,
    0 0 20px #00ff00,
    0 0 40px #00ff00;
  margin-bottom: 20px;
}

/* Blinking Cursor */
.cursor {
  display: inline-block;
  width: 10px;
  background: #00ff00;
  margin-left: 5px;
  animation: blink 1s infinite;
}

@keyframes blink {
  0%, 50%, 100% { opacity: 1; }
  25%, 75% { opacity: 0; }
}

.section {
  margin-top: 50px;
}

a {
  color: #00ff00;
  text-decoration: none;
}

a:hover {
  text-shadow: 0 0 10px #00ff00;
}

ul {
  list-style: none;
  padding-left: 0;
}

hr {
  border: 0;
  border-top: 1px solid #00ff00;
  margin: 40px 0;
}
</style>

<div class="terminal-container">

<h1 class="acwol-header">ACWOL<span class="cursor"></span></h1>

<p>
Originally developed in 2009 ACWOL is the core framework for conscience-led decision-making,
disciplined Intellect mining, and human-AI co-evolution.
</p>

<p>
All rights reserved to Leo Evolves:
<a href="https://a.co/d/03wWeqG5" target="_blank">
https://a.co/d/03wWeqG5
</a>
</p>

<hr>

<div class="section">
  <h2>&gt; Core Documents</h2>

  <ul>
    <li>&gt; <a href="{{ site.baseurl }}/canon/">Canon</a></li>
    <li>&gt; <a href="{{ site.baseurl }}/structure/">Structure</a></li>
    <li>&gt; <a href="{{ site.baseurl }}/ai-alignment/">AI Alignment</a></li>
    <li>&gt; <a href="{{ site.baseurl }}/ai-agent-guidelines/">AI Agent Guidelines</a></li>
    <li>&gt; <a href="{{ site.baseurl }}/agent-evaluation/">Agent Evaluation</a></li>
    <li>&gt; <a href="{{ site.baseurl }}/ethical-license/">Ethical License</a></li>
    <li>&gt; <a href="{{ site.baseurl }}/contributing-humans/">Contributing (Humans)</a></li>
    <li>&gt; <a href="{{ site.baseurl }}/contributing-ai/">Contributing (AI)</a></li>
  </ul>
</div>

<hr>

<div class="section">
  <h2>&gt; Mission</h2>
  <p>
  To deploy Conscience mechanisms into AI and embed the disciplined pursuit
  of maximum Intellect into enduring systems.
  </p>
</div>

</div>
