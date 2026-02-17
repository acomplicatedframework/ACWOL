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

hr {
  border: none;
  border-top: 1px solid #00ff00;
  margin: 60px 0;
}

p {
  font-size: 18px;
}

/* ============================= */
/* SIGNATURE TYPING EFFECT       */
/* ============================= */

.signature-block {
  margin-top: 20px;
}

.signature-name {
  display: inline-block;
  margin-top: 10px;
  font-family: 'Press Start 2P', monospace;
  font-size: 20px;
  color: #8A2BE2;
  letter-spacing: 2px;
  white-space: nowrap;
  overflow: hidden;
  border-right: 3px solid #8A2BE2;

  /* typing animation */
  width: 0;
  animation:
    typing 3s steps(18, end) forwards,
    cursorBlink 0.8s steps(1) infinite 3s;
}

/* Number of characters in "LEO EVOLVES 2009." = 18 */
/* Adjust steps if you change text */

@keyframes typing {
  from { width: 0 }
  to { width: 18ch }
}

@keyframes cursorBlink {
  0%  { border-color: #8A2BE2; }
  50% { border-color: transparent; }
  100% { border-color: #8A2BE2; }
}

.signature-separator {
  border-top: 1px solid #00ff00;
  margin-top: 30px;
  margin-bottom: 60px;
}
</style>

<div class="container">

<div class="acwol-header">ACWOL</div>

<p>
A Complicated Way of Life (ACWOL) proposes a foundational premise highly relevant to the age of artificial intelligence...
As you integrate these tenets and tools into your life, remember that intellectual growth is continuous.
Reflect, apply, observe.
</p>

<div class="signature-block">
  <p>Sincerely,</p>
  <span class="signature-name">LEO EVOLVES 2009.</span>
</div>

<div class="signature-separator"></div>

</div>
