---
layout: default
title: Home
---

<!-- Navigation Bar -->
<nav style="position: sticky; top: 0; background-color: #2f4f4f; padding: 10px; z-index: 1000;">
  <a href="#home" style="color: white; margin-right: 20px;">Home</a>
  <a href="#projects" style="color: white; margin-right: 20px;">Projects</a>
  <a href="#experience" style="color: white; margin-right: 20px;">Experience</a>
  <a href="#education" style="color: white; margin-right: 20px;">Education</a>
  <a href="#about" style="color: white; margin-right: 20px;">About</a>
  <a href="#contact" style="color: white;">Contact</a>
</nav>

<!-- Home Section -->
<section id="home" style="padding: 100px 20px;">
# Welcome to My Portfolio 🚀

Hi, I’m [Your Name]! This is my homepage.
</section>

<!-- Projects Section -->
<section id="projects" style="padding: 100px 20px;">
# Projects ⚡

- 🚀 Rocket Design  
- 🤖 Robotics Arm  
- ⚡ Electronics Automation
</section>

<!-- Experience Section -->
<section id="experience" style="padding: 100px 20px;">
# Experience 💼

- Company A – Software Engineer (2022–Present)  
- Company B – Intern (2021–2022)
</section>

<!-- Education Section -->
<section id="education" style="padding: 100px 20px;">
# Education 🎓

- University XYZ – B.Sc. in Mechanical Engineering (2018–2022)  
- High School ABC – Graduated 2018
</section>

<!-- About Section -->
<section id="about" style="padding: 100px 20px;">
# About Me 👋

I’m an engineer passionate about robotics, electronics, and design.
</section>

<!-- Contact Section -->
<section id="contact" style="padding: 100px 20px;">
# Contact 📬

Email: your.email@example.com  
LinkedIn: [your-linkedin](https://linkedin.com)
</section>

<!-- Smooth Scroll -->
<script>
  document.querySelectorAll('nav a').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
      e.preventDefault();
      document.querySelector(this.getAttribute('href')).scrollIntoView({
        behavior: 'smooth'
      });
    });
  });
</script>
