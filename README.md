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
