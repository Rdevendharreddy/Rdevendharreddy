<h1 align="center">Hi 👋, I'm R. Devendhar Reddy</h1>

<h3 align="center">
Data Analytics • Python Developer • AI & Automation
</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=6A5ACD&center=true&vCenter=true&width=950&lines=AI+%26+ML+Student;Python+Developer;Full+Stack+Developer;AI+Enthusiast;Python+%7C+HTML+%7C+CSS+%7C+JavaScript;Pandas+%7C+NumPy+%7C+Matplotlib;APIs+%7C+SQL+%7C+MongoDB;GitHub+%7C+Docker+%7C+Power+BI" alt="Typing SVG"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Rdevendharreddy&label=Profile%20Views&color=6A5ACD&style=for-the-badge"/>
</p>

---

## 🙋‍♂️ About Me

- 🎓 AI & ML Student passionate about building real-world intelligent systems
- 💻 Focused on Python, Full Stack Development, AI Automation & Data Analytics
- 🚀 Exploring Artificial Intelligence, APIs, Cloud & Emerging Technologies
- 📊 Skilled in React, SQL, MongoDB, Power BI & Data Visualization
- ⚡ Love turning complex ideas into clean and user-friendly solutions

---

## 📫 Connect With Me

<p align="center">

<a href="mailto:reddygariganeshreddy@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/Rdevendharreddy">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</p>

---

## 🛠 Tech Stack

<p align="center">

<img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>

</p>

---

## 📈 GitHub Stats

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Rdevendharreddy&show_icons=true&theme=tokyonight"/>

  <img height="180em" src="https://github-readme-streak-stats.herokuapp.com/?user=Rdevendharreddy&theme=tokyonight"/>
</p>

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rdevendharreddy&layout=compact&theme=tokyonight"/>
</p>

---

---

## 🐍 Contribution Graph

<p align="center">
  <img src="https://raw.githubusercontent.com/Rdevendharreddy/Rdevendharreddy/output/github-contribution-grid-snake.svg" alt="Snake animation" />
</p>

name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: Rdevendharreddy
          outputs: dist/github-contribution-grid-snake.svg
          
      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


