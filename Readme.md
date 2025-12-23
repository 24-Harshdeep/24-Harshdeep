<!--
  Professional README for Harshdeep
  - Visual-first layout with guidance for images that don't render on GitHub
  - Keep this file at repo root as `Readme.md`
-->

# Harshdeep — Full-Stack Developer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-linkedin)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/users/your-discord-id)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:youremail@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://your-portfolio.com)

A pragmatic Full-Stack developer focusing on building scalable web applications and quality user experiences.

---

## 📊 GitHub Analytics & Activity

<div align="center">
  
  ![Profile Views](https://komarev.com/ghpvc/?username=HARSHDEEP24&color=blueviolet&style=for-the-badge&label=PROFILE+VIEWS)
  
</div>

### 📈 Contribution Graph
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=HARSHDEEP24&theme=react-dark&hide_border=true&area=true" width="100%"/>
</p>

### 🔥 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=HARSHDEEP24&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" width="49%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=HARSHDEEP24&theme=tokyonight&hide_border=true" width="49%" />
</p>

### 💻 Most Used Languages
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=HARSHDEEP24&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" width="49%"/>
  <img src="https://github-readme-stats.vercel.app/api/wakatime?username=HARSHDEEP24&theme=tokyonight&hide_border=true&layout=compact" width="49%"/>
</p>

### 🏆 GitHub Trophies
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=HARSHDEEP24&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7" width="100%"/>
</p>

---

## What this repository contains

- A collection of web projects and demos built with React, Node.js and MongoDB.
- Clean, approachable README with visuals, badges, and troubleshooting tips for images.

## Key Features

- Responsive UI and RESTful APIs
- Authentication & role-based access (when applicable)
- Deploy-ready Docker / CI hints

## 🛠️ Tech Stack & Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,nodejs,express,mongodb,postgres,python,django,git,github,docker,vscode,figma,tailwind" />
</p>

### Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

### DevOps & Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## Quick start

1. Clone the repo

   git clone https://github.com/<your-user>/<your-repo>.git

2. Install and run (example for a Node + React monorepo)

   # from repo root
   cd project-folder
   npm install
   npm run dev

3. Open http://localhost:3000 (or as configured)

---

## How to add visuals (best practice)

1. Create a directory to store visuals inside the repo: `docs/images/` or `.github/assets/`.
2. Add images (PNG/JPG) and small GIFs for demos. Keep GIFs under ~5–10 MB for fast loading.
3. Reference them with a relative path in the README:

   ```markdown
   ![Alt text](docs/images/screenshot.png)
   ```

4. Commit the image files to the same branch as the README so GitHub can render them.

---

## Troubleshooting: Images not visible on GitHub (common causes & fixes)

If images in your README are not appearing, check the following (in order):

1. Wrong path or filename
   - GitHub is case-sensitive. `Images/Screenshot.png` ≠ `images/screenshot.png`.
   - Use the exact relative path from the README location. If README is at repo root and image is in `docs/images/`, use `docs/images/foo.png`.

2. Image not committed / on different branch
   - Ensure the image is added and pushed to the same branch as the README.
   - Run `git status` and `git ls-files | grep docs/images` to confirm the file is tracked.

3. Using a non-raw GitHub URL
   - Browser-visible preview links (like repository HTML pages) won't always work; for raw file links use:

   https://raw.githubusercontent.com/<user>/<repo>/<branch>/docs/images/screenshot.png

   - But prefer relative paths inside README for portability.

4. External image blocked / mixed content
   - If linking to an external HTTP image from an HTTPS page, the image will be blocked. Use HTTPS.
   - Some services block hotlinking or require CORS; host images in your repo or use a CDN.

5. File size too large / LFS required
   - GitHub has limits for file size. Very large images or videos should be stored using Git LFS or a CDN.

6. Adblockers or corporate proxies
   - Some badges or analytics images can be blocked by adblockers. Test in a different browser or incognito.

7. Branch name mismatch for raw URLs
   - If you hard-coded `main` but your default branch is `master` (or vice versa), raw links will 404. Use relative paths instead.
---
 
---

## 📁 Featured Projects

<div align="center">

| Project | Description | Tech Stack | Links |
|---------|-------------|------------|-------|
| 🤖 **Adaptive Chatbot** | Full-stack chatbot with task management & conversation organization | React, Node.js, MongoDB, Express | [Code](https://github.com/24-Harshdeep/adaptuitive-chatbot) • [Demo](#) |
| 🍜 **Zaika Hub** | Recipe discovery & sharing platform with search filters | React, CSS3, REST API | [Code](https://github.com/24-Harshdeep/zaika-hub) • [Demo](#) |

</div>

## 🎯 Current Focus

```mermaid
graph LR
    A[Learning] --> B[TypeScript]
    A --> C[Next.js 14]
    A --> D[Docker & K8s]
    B --> E[Full-Stack Projects]
    C --> E
    D --> E
    E --> F[Production Deployment]
```

## 📚 Certifications

<details>
<summary>🎓 Click to view certifications</summary>

- ✅ Prompt Engineering for ChatGPT – Coursera
- ✅ Learning to Prompt – Coursera  
- ✅ Introduction to Git and GitHub – Coursera
- ✅ Version Control – Coursera
- ✅ MongoDB & Backend Development – MongoDB University

</details>

---

## Contributing

- Fork, create a feature branch, add tests, and open a PR.
- Read `CONTRIBUTING.md` (if present) for coding and commit guidelines.

---

## License & Contact

MIT · For business or collaboration inquiries: youremail@gmail.com

---

_If you'd like, I can add a sample screenshot file (placeholder) into `docs/images/` so you can see how it renders and to remove the "missing image" problem while you replace it with real screenshots._
