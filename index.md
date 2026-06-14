---
layout: default
---

<div class="main-buttons">
  <a class="main-button" href="{{ '/assets/cv/your-name-cv.pdf' | relative_url }}" target="_blank">CV</a>
  <a class="main-button" href="{{ '/life/' | relative_url }}">Life</a>
</div>

<style>
.main-buttons {
  margin-top: 28px;
  display: flex;
  justify-content: center;
  gap: 14px;
  flex-wrap: wrap;
}

.main-button {
  display: inline-block;
  min-width: 90px;
  padding: 12px 22px;
  border: 2px solid white;
  border-radius: 999px;
  color: white;
  text-decoration: none;
  font-family: Helvetica, Arial, sans-serif;
  font-size: 0.95rem;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  background: rgba(0, 0, 0, 0.15);
}

.main-button:hover {
  background: rgba(255, 255, 255, 0.18);
  transition: 300ms;
}
</style>
