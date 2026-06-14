---
layout: default
---

<div class="main-buttons">
  <a class="main-button" href="{{ '/assets/cv/your-name-cv.pdf' | relative_url }}" target="_blank">CV</a>
  <a class="main-button" href="{{ '/life/' | relative_url }}">Small Things</a>
</div>

<style>
.main-buttons {
  margin: 28px auto 0 auto;
  width: fit-content;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 14px;
  flex-wrap: wrap;

  position: relative;
  left: 50%;
  transform: translateX(-50%);
}

.main-button {
  display: flex;
  justify-content: center;
  align-items: center;

  width: 100px;
  height: 42px;

  border: 2px solid white;
  border-radius: 999px;

  color: white;
  text-decoration: none;
  font-family: Helvetica, Arial, sans-serif;
  font-size: 0.95rem;
  letter-spacing: 0.08em;
  text-transform: uppercase;

  background: rgba(0, 0, 0, 0.15);
  box-sizing: border-box;
}

.main-button:hover {
  background: rgba(255, 255, 255, 0.18);
  transition: 300ms;
}
</style>
