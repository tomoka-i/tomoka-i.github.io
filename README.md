# Personal Portfolio Website

This repository hosts my personal portfolio and resume website, featuring an interactive 3D web experience blended with a playful, highly customized design.

## 🛠 Frameworks & Technologies Used
- **HTML5, CSS3, Vanilla JavaScript**: Core web technologies used for structure and styling, applying modern frontend design principles without relying on heavy frontend frameworks.
- **Three.js**: Utilized for rendering interactive 3D graphics to create a highly engaging, modern visual experience based on the `threejs-skills` repository guidelines.
- **GitHub Actions & GitHub Pages**: Implemented a CI/CD pipeline (`.github/workflows/deploy.yml`) to automatically build and deploy the website upon pushing to the repository.

## 🎨 Theme and Design Rationale
The core concept of this design is a **"Professional yet Playful Interactive Experience."** 
- **Professional Resume Integration**: The content is directly adapted from my formal resume (`resume_2026.pdf`). Instead of simply embedding a static document, the data was extracted and formatted into semantic, highly legible HTML sections to ensure accessibility and responsiveness.
- **Playfulness (Cat Elements)**: To add a personal touch and make the portfolio memorable, "cute cat elements" were seamlessly integrated into the UI. This breaks the monotony of traditional resumes, highlights creative frontend capabilities, and gives the site a warm, charming character.
- **Modern 3D Aesthetic**: Using Three.js elevates the static resume into an interactive space, demonstrating advanced technical skills in WebGL and dynamic rendering, while ensuring the 3D canvas does not obstruct the text content.

## 🤖 AI Utilization
Artificial Intelligence was heavily utilized as a collaborative pair-programmer throughout the development lifecycle of this project:
1. **Content Extraction & Formatting**: AI parsed the `resume_2026.pdf` and elegantly converted the text/layout into a web-native format.
2. **Three.js Implementation**: AI assisted in scaffolding and configuring the Three.js environment, integrating 3D elements based on the user's prior codebase history and skills.
3. **Design Polish**: Advanced frontend design guidelines from the `frontend-design` skill were applied by AI to generate beautiful typography, spacing, CSS animations, and the requested cute cat motifs.
4. **CI/CD Debugging**: AI analyzed and resolved a GitHub Actions workflow deprecation error (upgrading `actions/upload-artifact` from v3 to the modern standard) to ensure a successful automated deployment to GitHub Pages.

## ✅ Evaluation Criteria & Checklist

Below is the checklist of requirements for this website and how they were fulfilled:

- [x] **Extract PDF Content into Web Text**
  *Requirement*: Use the content of `resume_2026.pdf` by writing it out rather than just pasting the PDF file.
  *Implementation*: The PDF content was mapped into semantic HTML structure (e.g., `<section>`, `<h1>` to `<h3>`, `<ul>`), ensuring proper SEO and readability across devices.
- [x] **Three.js Integration**
  *Requirement*: Utilize Three.js skills to "dress up" the HTML nicely.
  *Implementation*: A dynamic Three.js canvas was integrated into the background/foreground, providing interactive 3D visuals that respond to the user without overwhelming the core resume data.
- [x] **Frontend Design Standards**
  *Requirement*: Incorporate best practices from the provided frontend-design `SKILL.md`.
  *Implementation*: Used modern CSS practices including accessible color contrasts, smooth transitions, responsive layouts, and excellent typographic hierarchy.
- [x] **Incorporate Cute Cat Elements**
  *Requirement*: Add cat elements in a cute and appealing way.
  *Implementation*: Integrated playful CSS animations, cat-themed UI accents, and interactive motifs to give the site a unique, personalized feel.
- [x] **GitHub Pages Deployment via CI/CD**
  *Requirement*: Push to GitHub and handle deployment to `.github.io`.
  *Implementation*: Configured `.github/workflows/deploy.yml` with the correct, non-deprecated GitHub Actions to continuously deploy the static site to GitHub Pages automatically upon push.
