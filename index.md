---
layout: default
---
<div class="main-buttons">
  <a class="main-button" href="{{ '/assets/cv/CV_Fatemeh.pdf' | relative_url }}" target="_blank">CV</a>
  <a class="main-button" href="{{ '/research/' | relative_url }}">Research</a>
  <a class="main-button" href="{{ '/personal/' | relative_url }}">Personal</a>
</div>

<style>
  /* @import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600&family=Inter:wght@300;400;500&display=swap'); */
  @import url('https://fonts.googleapis.com/css2?family=Lora:wght@400;500;600&family=Inter:wght@300;400;500&display=swap');
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

  transform: translateY(40px);
}

/* Avatar like the original template */
.avatar {
  display: block;
  width: 200px;
  height: 200px;

  border-radius: 50%;
  object-fit: cover;
  object-position: center;

  border: 2px solid white;
  box-sizing: border-box;

  margin: 60px auto 28px auto !important;
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
  margin-bottom: 18px;

  /* font-family: 'Cormorant Garamond', serif; */
  font-family: 'Lora', serif;
  font-size: clamp(3.2rem, 7vw, 6rem);
  font-weight: 500;
  letter-spacing: 0.03em;
  line-height: 1;
}

.title-card h3 {
  margin-top: 0;
  margin-bottom: 0;

  font-family: 'Inter', sans-serif;
  font-size: clamp(0.82rem, 1.15vw, 1.05rem);
  font-weight: 400;
  line-height: 1.35;
  letter-spacing: 0.005em;
}
  
/* CV and Life buttons */

  .main-buttons {
  margin-top: 24px;
  margin-bottom: 28px;
  width: 100%;

  display: flex;
  justify-content: center;
  align-items: center;
  gap: 18px;
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
  /* Force visual order: title → buttons → icons */
body,
.page-shell {
  display: flex !important;
  flex-direction: column !important;
  align-items: center !important;
}

/* Avatar first */
.avatar {
  order: 1;
}

/* Name + description second */
.title-card {
  order: 2;
}

/* CV / Personal buttons third */
.main-buttons {
  order: 3;
  margin-top: 24px;
  margin-bottom: 26px;
}

/* GitHub / email icons fourth */
body > ul,
.page-shell > ul {
  order: 4;
}
</style>
