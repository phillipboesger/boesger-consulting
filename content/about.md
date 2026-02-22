---
author: Phillip Bösger
title: 👋 About Me
date: 2025-05-17
description:
keywords: ["boesger", "about-us", "about-me", "contact"]
type: about
---

<style>
  .about-flex {
    display: flex;
    align-items: center; /* vertikal zentriert */
    gap: 2rem;
    margin-bottom: 2rem;
  }
  .about-image-round {
    width: 200px !important;
    height: 200px !important;
    border-radius: 50% !important;
    object-fit: cover !important;
    object-position: center 20% !important;
    display: block;
    margin: 0 0 0 0 !important;
  }
  @media (max-width: 600px) {
    .about-flex {
      flex-direction: column;
      align-items: center;
      gap: 1rem;
    }
    .about-image-round {
      width: 160px !important;
      height: 160px !important;
      object-position: center 15% !important;
    }
  }
  @media (max-width: 480px) {
    .about-image-round {
      width: 140px !important;
      height: 140px !important;
      object-position: center 10% !important;
    }
  }
  @media (max-width: 700px) {
    .cta-white, .text-4xl.text-center.text-white { font-size: 1.75rem !important; }
    .cta-white a, .text-5xl.text-blue-400 { font-size: 2.25rem !important; }
  }
</style>

<div class="about-flex">
  <img src="/images/about-image.webp" alt="Phillip Bösgers Portrait" class="about-image-round" loading="eager" fetchpriority="high" decoding="async">
  <div style="display: flex; align-items: center;">
    <span>
      Hi, I'm <strong>Phillip</strong>, a passionate Senior Software Developer specializing in <strong>Polarion consulting and plugin development</strong>. With extensive expertise in Java, HTML, JavaScript, and Velocity, I provide tailored solutions to streamline development processes and enhance team productivity. <br> Since 2024, I've also intensified my focus on GitHub automations, leveraging AI in daily workflows, and optimizing processes using AI Agents.
    </span>
  </div>
</div>

## 🚀 Professional Skills

- **Polarion ALM:** Deep expertise in consulting, plugin development, customization, and integration.
- **Fullstack Development:** Extensive experience across front-end and back-end technologies, continuously exploring innovative approaches.
- **GitHub & CI/CD Automation:** Skilled in building efficient workflows, automating processes, and ensuring continuous integration and delivery.
- **AI & Automation:** Leveraging AI to create efficient automation solutions, from simple scripts to advanced AI agents—exploring and expanding my skills continually.

## 🌍 Digital Nomad & Lifestyle

Originally from Germany <span title="Germany" style="font-size:1.2em;">🇩🇪</span>, I'm a digital nomad, traveling the globe while seamlessly integrating my passion for technology, sports, and photography. My lifestyle fuels creativity, meticulous planning, and sharp attention to detail, ensuring every project aligns with my motto:

> Nothing is impossible—it's only a question of time and budget.

## 📸 Beyond Work

Outside of coding and consulting, you'll find me capturing moments through photography—visit my photography website at [photography.boesger.com](https://photography.boesger.com)—engaging in various sports, or exploring new destinations around the world. I firmly believe in balancing professional dedication with personal growth and experiences.

I also run a blog at [polarion.boesger.com](https://polarion.boesger.com), where I share **updates, practical tips, and hands-on knowledge** around **Polarion ALM** and the **use of AI in everyday development work**. You'll find best practices, real-world examples, and ideas on how to combine Polarion, automation, and AI to get even more out of your engineering processes.

## 🎯 My Mission

Delivering **high-quality, cost-effective solutions** tailored precisely to client needs. I'm committed to finding the optimal path to achieve your project's goals.

---

<section class="my-16 max-w-2xl mx-auto">
  <div class="text-4xl font-bold text-center text-white">
    Let's connect and build something great together!
    <br />
    <br />
    <a class="contact-cta-link" href="mailto:{{< param authorEmail >}}">Let's chat 📨</a>
  </div>
</section>
