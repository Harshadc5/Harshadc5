from pathlib import Path
import pypandoc

md = r"""<div align="center">

# Harshad Chaudhari

<img src="https://readme-typing-svg.demolab.com?font=Space+Mono&weight=700&size=28&pause=1200&center=true&vCenter=true&width=900&lines=AI+Engineer;Full-Stack+Developer;Building+Intelligent+Products;Machine+Learning+%7C+Automation+%7C+Cloud;Open+Source+Contributor" />

### Building software that solves real-world problems with AI.

<p>
<a href="https://rtfolio-three-beige-2l8e4l9ouk.vercel.app"><img src="https://img.shields.io/badge/🌐Portfolio-Visit-2563EB?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/harshad05"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin"/></a>
<a href="mailto:harshadchaudhari2005@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/Harshadc5"><img src="https://img.shields.io/github/followers/Harshadc5?style=for-the-badge"/></a>
</p>

</div>

---

# 👨‍💻 About

I build **AI-powered applications, intelligent automation, and full-stack software** with an emphasis on usability, maintainability, and measurable impact.

My interests include:

- Artificial Intelligence & Machine Learning
- Full-Stack Engineering
- Developer Tooling
- Analytics Platforms
- Cloud-native Applications

Currently pursuing **B.Tech in Computer Science Engineering (AI & ML)** at **VIT Bhopal University**.

---

# 🚀 Featured Work

| Project | Overview |
|---|---|
| 🧠 JavaScript Analytics Platform | Privacy-conscious analytics for e-commerce websites |
| 🌿 Potato Disease Classification | Deep-learning based crop disease detection |
| 🔊 InsightVoice | OCR + multilingual text/image-to-speech platform |
| 🏫 School Management System | Student records & document generation |
| 🚜 ShetiPump | Agriculture-focused software |

---

# 📈 GitHub Snapshot

<p align="center">
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Harshadc5&theme=github_dark"/>
</p>

<p align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api?username=Harshadc5&show_icons=true&theme=github_dark&hide_border=true"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Harshadc5&layout=compact&theme=github_dark&hide_border=true"/>
</p>

<p align="center">
<img src="https://streak-stats.demolab.com?user=Harshadc5&theme=github-dark-blue&hide_border=true"/>
</p>

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Harshadc5&theme=github-dark&hide_border=true"/>
</p>

---

# 🛠 Technology

### Languages
Python • JavaScript • Java • C++

### AI / ML
TensorFlow • NumPy • Pandas • OpenCV

### Frontend
React • HTML • CSS • Bootstrap

### Backend
FastAPI • Flask • Node.js

### Database
MongoDB • MySQL

### Cloud
AWS • Docker • Git • Linux

---

# 🏅 Highlights

- 💡 AI & ML focused engineering
- 🚀 Portfolio of end-to-end software projects
- 🌱 Continuous learner
- 🤝 Open to collaboration and internships
- 📚 Active in open-source and practical software development

---

# 🗺 Roadmap

- [ ] AI Agents
- [ ] Production-grade SaaS
- [ ] Cloud certifications
- [ ] System Design
- [ ] Open-source contributions

---

# 🌐 Connect

| Platform | Link |
|---|---|
| Portfolio | https://rtfolio-three-beige-2l8e4l9ouk.vercel.app |
| LinkedIn | https://www.linkedin.com/in/harshad05 |
| GitHub | https://github.com/Harshadc5 |
| Email | harshadchaudhari2005@gmail.com |

---

<div align="center">

### "Build things people genuinely enjoy using."

⭐ Thanks for visiting my profile.

</div>
"""
out="/mnt/data/GitHub_Profile_README_V4.md"
Path(out).write_text(md,encoding="utf-8")
print(out)
