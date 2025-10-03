---
layout: default
title: Home
---

<link rel="stylesheet" href="assets/style.css">

<!-- Navigation Bar -->
<nav id="navbar">
  <a href="#home" class="active">Home</a>
  <a href="#projects">Projects</a>
  <a href="#experience">Experience</a>
  <a href="#education">Education</a>
  <a href="#about">About</a>
  <a href="#contact">Contact</a>
</nav>

<!-- Sections -->
<section id="home">
# Welcome to My Portfolio 🚀

Hi, I’m [Your Name]! Explore my work below.
</section>

<section id="projects">
# Projects ⚡

- 🚀 Rocket Design  
- 🤖 Robotics Arm  
- ⚡ Electronics Automation
</section>

<section id="experience">
# Experience 💼

- Company A – Software Engineer (2022–Present)  
- Company B – Intern (2021–2022)
</section>

<section id="education">
# Education 🎓

- University XYZ – B.Sc. in Mechanical Engineering (2018–2022)  
- High School ABC – Graduated 2018
</section>

<section id="about">
# About Me 👋

I’m an engineer passionate about robotics, electronics, and design.
</section>

<section id="contact">
# Contact 📬

Email: your.email@example.com  
LinkedIn: [your-linkedin](https://linkedin.com)
</section>

<!-- JavaScript for active tab highlighting -->
<script>
const sections = document.querySelectorAll("section");
const navLinks = document.querySelectorAll("nav a");

window.addEventListener("scroll", () => {
  let current = "";
  sections.forEach(section => {
    const sectionTop = section.offsetTop - 120;
    if (pageYOffset >= sectionTop) {
      current = section.getAttribute("id");
    }
  });

  navLinks.forEach(link => {
    link.classList.remove("active");
    if (link.getAttribute("href") === "#" + current) {
      link.classList.add("active");
    }
  });
});
</script>
