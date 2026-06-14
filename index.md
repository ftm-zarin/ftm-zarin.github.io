---
layout: default
---

<div class="main-buttons">
  <a class="main-button" href="{{ '/assets/cv/your-name-cv.pdf' | relative_url }}" target="_blank">CV</a>
  <a class="main-button" href="{{ '/Personal/' | relative_url }}">Personal</a>
</div>

<style>
html,
body {
  min-height: 100%;
  margin: 0;
}

body {
  text-align: center;
}

.page-shell {
  min-height: 100vh;
  width: 100%;
  box-sizing: border-box;

  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

  padding: 6vh 20px;
}

/* Avatar like the original template */
.avatar {
  display: block;
  width: 200px;
  height: 200px;

  border-radius: 50%;
  object-fit: cover;
  object-position: center;

  border: 3px solid white;
  box-sizing: border-box;

  margin: 0 auto 28px auto !important;
}

/* One soft box behind only name + description */
.title-card {
  width: fit-content;
  max-width: 85vw;

  margin: 0 auto 22px auto;
  padding: 22px 34px;

  background: rgba(0, 0, 0, 0.42);
  border-radius: 26px;

  backdrop-filter: blur(6px);
  -webkit-backdrop-filter: blur(6px);

  box-sizing: border-box;
  text-align: center;
}

.title-card h1,
.title-card h3 {
  background: transparent !important;
  margin-left: 0 !important;
  margin-right: 0 !important;
  padding: 0 !important;
  border-radius: 0 !important;
}

.title-card h1 {
  margin-top: 0;
  margin-bottom: 12px;
}

.title-card h3 {
  margin-top: 0;
  margin-bottom: 0;
  line-height: 1.35;
}

/* CV and Life buttons */
.main-buttons {
  margin-top: 24px;
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

  width: 140px;
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
