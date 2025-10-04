---
title: "Tasin Khan"
---

<!-- Hide the theme's blue site title + description -->
<style>
/* Minimal theme header override */
header h1, header h1 a, header p { display: none !important; }

/* Two-column layout */
.two-col {
  display: grid;
  grid-template-columns: 220px minmax(0, 1fr);
  gap: 28px;
  align-items: start;
}
@media (max-width: 720px) {
  .two-col { grid-template-columns: 1fr; }
}

/* Left column bits */
.left img { border-radius: 10px; display: block; margin-bottom: 16px; width: 220px; }
.contacts a { display: block; margin: 4px 0; }

/* Section divider */
hr { border: none; border-top: 1px solid #e5e7eb; margin: 20px 0; }
</style>

<div class="two-col">

  <!-- LEFT COLUMN -->
  <div class="left">
    <!-- Make sure the filename + case matches exactly in /assets -->
    <img src="/assets/profile.jpg" alt="Tasin Khan">
    <div class="contacts">
      <a href="mailto:tasinkhan2000@gmail.com">📧 Email</a>
      <a href="https://github.com/tasiinn" target="_blank">💻 GitHub</a>
      <a href="https://www.linkedin.com/in/tasinkhan" target="_blank">🔗 LinkedIn</a>
      <!-- Optional: <a href="/assets/Tasin_Khan_CV.pdf" target="_blank">📄 CV</a> -->
    </div>
  </div>

  <!-- RIGHT COLUMN -->
  <div class="right" markdown="1">

## Tasin Khan
I am a first-year Master's student at the University of Rochester. I am currently working with Professor Yukang Yan at the BEAR Lab. My research focuses on **human-centered AI systems** that help improve accessibility.  
Interests: _Human-Computer Interaction, Human-AI Interaction, Human-Centered Computing, Accessibility & Inclusion_

---

## Education

**M.S., Computer Science — University of Rochester**  
_2025–2026, Rochester, NY_  

**B.S., Computer Science & Engineering — North South University (GPA 3.91)**  
_2020–2024, Dhaka, Bangladesh_  

---

## Research Experience

### BEAR Lab, University of Rochester — Research Assistant _(Current)_
- Conducting HCI research at the intersection of accessibility and AI, focusing on inclusive design for blind and low-vision users in remote collaboration contexts.

### Human-Computer Interaction Lab, North South University — Research Assistant _(Dec 2023–Jul 2025)_
- Conducted HCI research on accessibility for people with disabilities, applying mixed-methods studies to uncover usability barriers and inform inclusive technology design.

---

## Projects (Selected)

**Mental Health of People with Disabilities in Bangladesh**  
- Mixed-methods study identifying accessibility barriers; proposed inclusive design guidelines and resource tools.  

**Regulated Smart Device for Children**  
- Participatory design with parents; prototyped an **ML-assisted content filtering** system emphasizing safety, usability, and transparency.  
- Highlighted design principles for balancing parental control with child autonomy.

---

## Contact
- **Email:** [tasinkhan2000@gmail.com](mailto:tasinkhan2000@gmail.com)  
- **GitHub:** [github.com/tasiinn](https://github.com/tasiinn)  
- **LinkedIn:** [/in/tasinkhan](https://www.linkedin.com/in/tasinkhan)

*Last updated:* {{ site.time | date: "%B %Y" }}

  </div>
</div>


