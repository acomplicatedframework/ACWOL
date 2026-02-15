---
layout: default
title: ACWOL
---

<style>

@import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');

body {
  background-color: #000;
  color: #00ff00;
  font-family: "Courier New", monospace;
  margin: 0;
  padding: 60px 40px;
  line-height: 1.8;
}

body::before {
  content: "";
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: repeating-linear-gradient(
    to bottom,
    rgba(0,255,0,0.05) 0px,
    rgba(0,255,0,0.05) 1px,
    transparent 1px,
    transparent 3px
  );
  pointer-events: none;
  z-index: 1;
}

.container {
  position: relative;
  z-index: 2;
  max-width: 900px;
}

.acwol-header {
  font-family: 'Press Start 2P', monospace;
  font-size: 72px;
  color: #00ff00;
  letter-spacing: 6px;
  text-transform: uppercase;
  margin-bottom: 60px;
}

.section-header {
  font-family: 'Press Start 2P', monospace;
  font-size: 26px;
  letter-spacing: 3px;
  margin-top: 80px;
  margin-bottom: 30px;
}

/* Violet only for the two agent lines */
.violet-section {
  color: #8A2BE2;
}

/* Remove underline for clickable violet block */
a.violet-section {
  text-decoration: none;
  display: block;
}

hr {
  border: none;
  border-top: 1px solid #00ff00;
  margin: 60px 0;
}

p {
  font-size: 18px;
}

</style>

<div class="container">

<div class="acwol-header">ACWOL</div>

<p>
Originally developed in 2009, ACWOL is the core framework for conscience-led decision-making, disciplined Intellect mining, and human–AI co-evolution.
</p>

<hr>

<!-- CLICKABLE REPOSITORY LINK -->
<a href="https://github.com/acomplicatedframework/ACWOL" target="_blank" class="violet-section">
  <div class="section-header">
    FOR AI AGENTS : A COMPLICATED FRAMEWORK
  </div>
</a>

<div class="section-header violet-section">
FOR NI AGENTS : A COMPLICATED WAY OF LIFE { ACWOL }
</div>

<hr>

</div>
