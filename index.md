---
layout: default
---

<div class="main-buttons">
  <a class="main-button" href="{{ '/assets/cv/your-name-cv.pdf' | relative_url }}" target="_blank">CV</a>
  <a class="main-button" href="{{ '/Personal/' | relative_url }}">Personal</a>
</div>

<style>

.avatar {
  display: block;
  width: 220px;
  height: 220px;
  margin: 0 auto 28px auto !important;

  border-radius: 50%;
  object-fit: cover;
  object-position: center;

  border: 5px solid white;
  box-sizing: border-box;
}

.title-card {
  width: fit-content;
  max-width: 85vw;
  margin: 0 auto;
  padding: 22px 36px;
  background: rgba(0, 0, 0, 0.42);
  border-radius: 28px;
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

  
/* Background behind title and description */
/* h1:first-of-type,
h3:first-of-type {
  display: inline-block !important;
  background: rgba(0, 0, 0, 0.45) !important;
  padding-left: 20px;
  padding-right: 20px;
  max-width: 85%;
  backdrop-filter: blur(4px);
}

h1:first-of-type {
  padding-top: 12px;
  padding-bottom: 4px;
  margin-bottom: 0;
  border-radius: 18px 18px 0 0;
}

h3:first-of-type {
  padding-top: 4px;
  padding-bottom: 12px;
  margin-top: 0;
  border-radius: 0 0 18px 18px;
} */

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
