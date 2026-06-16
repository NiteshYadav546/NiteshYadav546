<h1 align="center">Hey 👋, I'm Nitesh Yadav</h1>

<p align="center">
🚀 Software Developer | ☕ Java DSA Enthusiast | 🌍 Building Modern Web Apps
</p>

<h1 align="center">
Open Source Contributor
</h1>

<hr>

<p align="center">
<img src="https://komarev.com/ghpvc/?username=NiteshYadav546&label=PROFILE+VIEWS&color=blue&style=for-the-badge" />
</p>

<hr>

<h2 align="center">✨ Let's Connect ✨</h2>

<p align="center">
<a href="#"><img src="https://img.shields.io/badge/PORTFOLIO-black?style=for-the-badge"></a>
<a href="#"><img src="https://img.shields.io/badge/GMAIL-red?style=for-the-badge"></a>
<a href="#"><img src="https://img.shields.io/badge/LINKEDIN-blue?style=for-the-badge"></a>
<a href="NiteshYadav546"><img src="https://img.shields.io/badge/GITHUB-black?style=for-the-badge"></a>
</p>

<hr>

# 🧠 About Me

```javascript
const nitesh = {
  role: "MERN Stack Developer",
  focus: ["React", "Node.js", "Java DSA"],
  currently_learning: ["Spring Boot", "System Design"],
  interests: ["AI", "Open Source", "Modern UI"],
  looking_for: "Software Developer Internship"
}
```

- 🎓 Final-Year B.Tech CSE Student
- 💻 Software Developer & Java DSA Enthusiast
- 🏆 Participant — Smart India Hackathon
- ⚡ Open Source Contributor
- 🚀 Passionate About Building Modern Web Applications

---

# 🚀 Featured Projects

## 🎓 University Resource & Collaboration System

- Developed a full-stack student collaboration platform
- Integrated AI Mentor
- Implemented real-time chat using Socket.io
- Added admin dashboard
- Responsive UI/UX

### 🛠 Tech Stack

`React.js` `Node.js` `Express.js` `MongoDB` `Socket.io`

🌐 Live Demo

---

## 🎥 Video Conferencing Platform

- Real-time Video Calling
- Chat & Screen Sharing
- JWT Authentication
- WebRTC Integration
- Responsive Design

### 🛠 Tech Stack

`React.js` `Node.js` `Express.js` `MongoDB` `WebRTC`

🌐 Live Demo

---

# 🛠 Tech Stack

## 👨‍💻 Languages

<p align="center">
<img src="https://skillicons.dev/icons?i=java,js" />
</p>

---

## 🌐 Frontend

<p align="center">
<img src="https://skillicons.dev/icons?i=html,css,react,tailwind" />
</p>

---

## ⚙️ Backend & Tools

<p align="center">
<img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,git,github,vscode" />
</p>

---

# 🏆 Achievements

- 🥇 Frontend Developer Intern
- 🏆 Smart India Hackathon Participant
- ⚡ Code Rush Participant
- 🌍 IAENG Member
- 🚀 Built MERN Stack Projects

---

# 📜 Certifications

- ☕ Java (Basic) Certification — HackerRank
- 📘 ADCA Certification
- 🏆 Smart India Hackathon Certificate
- ⚡ Code Rush Certificate

---

# 📊 GitHub Stats

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=NiteshYadav546&show_icons=true&theme=tokyonight"/>
</p>


---

# 📈 Contribution Graph

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=NiteshYadav546&theme=tokyo-night"/>
</p>

---

# 🐍 Contribution Snake

name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: NiteshYadav546
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
