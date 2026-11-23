<div align="center">

# Vinayak Sharma — Personal Portfolio Website
### Engineering Portfolio, Interactive Project Showcases & Full-Stack Architecture

[![Netlify](https://img.shields.io/badge/Netlify-Live%20Demo-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://vinayakportfoliofullstack.netlify.app/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-Semantic%20Architecture-E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Modern%20Animations%20%26%20Grid-1572B6.svg?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

<p align="center">
  <b>A modern, responsive personal portfolio website engineered to showcase verified AI/ML implementations, robotics systems, and full-stack software applications.</b><br>
  Built with pure semantic web standards, fluid responsive typography, AOS scroll animations, dynamic theme toggling, and integrated communication APIs.
</p>

<p align="center">
  <a href="https://vinayakportfoliofullstack.netlify.app/" target="_blank">
    <img src="https://img.shields.io/badge/Netlify-Live%20Demo-00C7B7?style=for-the-badge&logo=netlify&logoColor=white" alt="Live Demo">
  </a>
  <br><br>
  <b>🚀 Live Interactive Portfolio:</b> <a href="https://vinayakportfoliofullstack.netlify.app/">https://vinayakportfoliofullstack.netlify.app/</a>
</p>

---

</div>

## Executive Summary

Traditional static resumes fail to convey interactive design mastery, responsive UI behavior, and real-time frontend engineering competencies. 

The **Vinayak Sharma Personal Portfolio** is an end-to-end digital engineering showcase built to demonstrate technical depth across Artificial Intelligence, Machine Learning, Robotics, and Full-Stack Web Development. Rather than relying on generic website templates, this portfolio is architected from foundational HTML5, CSS3, and modern JavaScript, incorporating performant scroll transitions, dark/light theme ergonomics, interactive project previews, and an integrated Formspree contact delivery pipeline.

---

## 🎥 Interactive Video Demonstration & UI Flow

<div align="center">

<video src="https://github.com/vsbeginner/Vinayak-Sharma-Personal-Portfolio-Website/raw/main/Portfolio%20Demo.mp4" controls="controls" width="100%"></video>

<sub><b>Interactive Walkthrough:</b> Full responsive navigation, dynamic section transitions, interactive 3D skill visualization, and verified project repository showcases.</sub>

</div>

---

## Architectural Taxonomy & Navigation Routing

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                                CLIENT VIEWPORT & BROWSER                               │
└────────────────────────────────────────────────────────────────────────────────────────┘
                                    │
                                    ▼
                       ┌─────────────────────────┐
                       │   Hero Landing Stage    │ ◄── Dynamic Theme Guard
                       │  (Personal Branding)    │
                       └─────────────────────────┘
                                    │
       ┌────────────────────────────┼────────────────────────────┐
       ▼                            ▼                            ▼
┌──────────────┐             ┌──────────────┐             ┌──────────────┐
│  About Me    │             │ Skills Matrix│             │ Project Deck │
│ Professional │             │ Frontend, AI │             │ Repos, Demos │
│ Background   │             │ & Robotics   │             │ & Benchmarks │
└──────────────┘             └──────────────┘             └──────────────┘
       │                            │                            │
       └────────────────────────────┼────────────────────────────┘
                                    │
                                    ▼
                       ┌─────────────────────────┐
                       │ Education & Milestones  │
                       │ Department of CSE (MCA) │
                       └─────────────────────────┘
                                    │
                                    ▼
                       ┌─────────────────────────┐
                       │  Formspree API Gateway  │ ──► Direct Email Delivery
                       │  (Contact & Collab)     │
                       └─────────────────────────┘
```

---

## Core Technical Features

| Feature Module | Technical Implementation | Engineering Impact |
|:---|:---|:---|
| **Responsive Grid & Flexbox** | Pure CSS3 fluid layout calculations across desktop, tablet, and mobile breakpoints. | Zero layout shifts; seamless cross-device compatibility. |
| **Ergonomic Theme Engine** | CSS Custom Properties (Variables) switched via reactive DOM manipulation. | High-contrast readability in both ambient dark and daytime light settings. |
| **AOS Scroll Telemetry** | Micro-interaction triggers configured with non-blocking hardware-accelerated transitions. | Polished visual storytelling without computational jank or frame drops. |
| **API-Driven Contact Tunnel** | Asynchronous AJAX submission wired to Formspree backend endpoints. | Instant recruiter communication with client-side form validation. |
| **Asset & Media Optimization** | Compressed WebP imagery and hardware-accelerated video containers. | High PageSpeed scoring and optimized Time to Interactive (TTI). |

---

## Visual Design & UI/UX Gallery

<table width="100%">
  <thead>
    <tr>
      <th width="50%" align="center"><b>About & Hero Profile Section</b></th>
      <th width="50%" align="center"><b>Interactive Skills & Architecture</b></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">
        <img src="assets/images/about.jpg" alt="About Section UI" width="95%"><br>
        <sub><b>About Me UI:</b> Personal branding, career philosophy, and background.</sub>
      </td>
      <td align="center">
        <img src="assets/images/skills-illustration.jpg" alt="Technical Skills Visualization" width="95%"><br>
        <sub><b>Skills Matrix:</b> Multi-disciplinary technical proficiencies across frontend, backend, and AI.</sub>
      </td>
    </tr>
    <tr>
      <th width="50%" align="center"><b>Featured Project: Nature Grid Layout</b></th>
      <th width="50%" align="center"><b>Featured Project: Weather Forecasting App</b></th>
    </tr>
    <tr>
      <td align="center">
        <img src="assets/images/grid-layout.jpg" alt="Grid Layout Project" width="95%"><br>
        <sub><b>Grid Project Card:</b> Responsive CSS Grid architecture and fluid media cards.</sub>
      </td>
      <td align="center">
        <img src="assets/images/weather-app.jpg" alt="Weather Application Project" width="95%"><br>
        <sub><b>Weather App Card:</b> Real-time API telemetry and dynamic weather dashboards.</sub>
      </td>
    </tr>
  </tbody>
</table>

---

## Technical Specifications & Stack

- **Markup & Semantics**: Semantic HTML5 with accessibility tags
- **Styling Architecture**: Modern CSS3 (Grid, Flexbox, Custom Properties, Media Queries)
- **Scripting & Interactivity**: Vanilla JavaScript (ES6+), Event Listeners, Asynchronous Fetch API
- **Motion & Transitions**: AOS (Animate on Scroll) v2.3.1
- **Icons & Typography**: FontAwesome 6.x & Inter / Poppins Google Fonts
- **Deployment & Hosting**: Netlify Continuous Deployment (Git-integrated webhook)

---

## Quickstart & Local Reproduction

```bash
# Clone the repository
git clone https://github.com/vsbeginner/Vinayak-Sharma-Personal-Portfolio-Website.git
cd Vinayak-Sharma-Personal-Portfolio-Website

# Option 1: Open directly in your default browser
start index.html

# Option 2: Serve via local HTTP server
python -m http.server 3000
# Navigate to: http://localhost:3000
```

---

## Candidate Profile & Institutional Details

- **Candidate Name**: Vinayak Sharma
- **Enrollment / Roll No**: 2501940012
- **GitHub Profile**: [@vsbeginner](https://github.com/vsbeginner)
- **LinkedIn Profile**: [Vinayak Sharma](https://www.linkedin.com/in/vinayak-sharma-24a8aa384/)
- **Email Contact**: vsbeginner14@gmail.com
- **Degree Program**: Master of Computer Applications (MCA)
- **Institution**: Department of Computer Science & Engineering, K.R. Mangalam University

---

<div align="center">
  <sub>Developed for academic excellence and technical portfolio showcase. Licensed under the <a href="LICENSE">MIT License</a>.</sub>
</div>
