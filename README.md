# Saral Labs Bootcamp Challenge

**Candidate:** J Chanikya
**Project Date:** April 2026
**Deployment:** [Live Project Site](https://Chanikya-WebDev.github.io/saral-labs-bootcamp/)

---

## Project Overview

This repository contains the solution for the Saral Labs Engineering Internship Challenge. The project is divided into two primary modules: a research timeline for Large Language Models and an adaptive learning platform for Physics.

### Module 1: GPT Research Timeline
An interactive web-based timeline showcasing 7 pivotal research papers in the evolution of GPT models (2015-2023).
- **Interface:** Built with Tailwind CSS and Glassmorphism design principles.
- **Data Handling:** JSON-based paper metadata with Semantic Scholar API integration for citation metrics.
- **Features:** Dynamic axis rendering and mobile-responsive layout.

### Module 2: Physics Adaptive Learning Material
A dual-difficulty learning module for NCERT Physics Class 12, Chapter 8 (Electromagnetic Waves).
- **OCR Pipeline:** Utilizes Google Drive Vision API for high-accuracy extraction of complex physics equations and text.
- **Content Generation:** Sectioned prompting with Gemini 1.5 Flash to generate level-specific educational content.
- **User Experience:** Full-width responsive pages, reading progress indicators, and interactive self-assessment quizzes with live score tracking.

## Repository Structure

```text
.
└── docs/
    └── index.html     (Main Hub: Research Timeline)
    └── easy.html      (Easy Explainer & Interactive Quiz)
    └── hard.html      (Advanced Technical Deep-Dive & Quiz)
    └── .nojekyll     (GitHub Pages deployment configuration)
└── README.md          (Documentation)
└── .gitignore         (Environment configuration)
```

## Technical Implementation

- **Languages:** Python (Backend Logic), JavaScript (Interactivity), HTML5/CSS3.
- **AI & OCR:** Gemini 1.5 Flash API, Google Drive Vision OCR.
- **Libraries:** Pytesseract (fallback), PDF2Image, Tailwind CSS, MathJax (LaTeX rendering).
