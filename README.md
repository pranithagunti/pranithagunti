<h1 align="center">Hi there 👋, I'm Sai Pranitha Gunti</h1>
<h3 align="center">Aspiring Software Engineer | AI/ML Enthusiast | Lifelong Learner</h3>

---

### 💫 About Me
I'm a passionate and curious student who loves building impactful technology.
I specialize in AI, Machine Learning, and Full-Stack Web Development, with hands-on experience creating real-world projects such as an AI-Flood Management System, an Advanced Personal Finance Tracker, and intelligent web apps integrating Flask APIs, React UIs, and MongoDB backends.
I enjoy solving complex Data Structures and Algorithms (DSA) problems and applying that logic to build scalable, efficient systems.
My work spans across frontend, backend, and AI pipelines — from developing responsive interfaces in React / Next.js to training Deep Learning (CNN, NLP) models in Python.

### 🧠 Tech Stack Highlights

Languages: Python, Java, JavaScript,C.

Frameworks & Tools: React, Next.js, Flask, Spring Boot,Fast API.

Databases: MongoDB, MySQL

ML/AI: TensorFlow, scikit-learn, OpenCV

Version Control & Deployment: GitHub, Vercel, Netlify

When I’m not coding, I’m usually exploring new AI trends, contributing to open source, or attending developer community events.

I’m always eager to collaborate on projects that merge AI intelligence with real-world usability 🚀

---

### 🛠️ Tech Stack

![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
![Python](https://img.shields.io/badge/Python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Flask](https://img.shields.io/badge/Flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%2347A248.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VSCode-%23007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

### 📈 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=pranithagunti&show_icons=true&theme=radical" width="47%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=pranithagunti&theme=radical" width="47%" />
</div>

---

name: Generate Snake

on:
  workflow_dispatch:    # Allows manual trigger
  schedule:
    - cron: '0 */12 * * *'  # Optional: runs every 12 hours

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout repo
        uses: actions/checkout@v4

      - name: Generate snake SVG
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg

      - name: Push to output branch
        uses: actions/configure-pages@v4
        with:
          branch: output
          folder: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

---

### 🔗 Connect with Me

<p align="left">
  <a href="mailto:pranitha.gunti1609@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/sai-pranitha-gunti-4486772b3/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<!-- <a href="https://your-portfolio.com"><img src="https://img.shields.io/badge/Portfolio-000?style=for-the-badge&logo=firefox&logoColor=white" /></a> -->
</p>

---

<!---
pranithagunti/pranithagunti is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
