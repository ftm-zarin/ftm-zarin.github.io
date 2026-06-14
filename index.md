---
layout: default
---

<div class="main-buttons">
  <a class="main-button" href="{{ '/assets/cv/your-name-cv.pdf' | relative_url }}" target="_blank">CV</a>
  <a class="main-button" href="{{ '/Personal/' | relative_url }}">Personal</a>
</div>

<style>
/* Background only behind name and description */
body > h1,
body > h3 {
  background: rgba(0, 0, 0, 0.38);
  width: fit-content;
  max-width: 85%;
  margin-left: auto;
  margin-right: auto;
  padding-left: 18px;
  padding-right: 18px;
  backdrop-filter: blur(4px);
}

body > h1 {
  padding-top: 12px;
  padding-bottom: 4px;
  margin-bottom: 0;
  border-radius: 18px 18px 0 0;
}

body > h3 {
  padding-top: 4px;
  padding-bottom: 12px;
  margin-top: 0;
  border-radius: 0 0 18px 18px;
}

/* CV and Life buttons */
.main-buttons {
  margin-top: 28px;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 14px;
  flex-wrap: wrap;
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

  background: rgba(0, 0, 0, 0.25);
  box-sizing: border-box;
}

.main-button:hover {
  background: rgba(255, 255, 255, 0.18);
  transition: 300ms;
}
</style>
