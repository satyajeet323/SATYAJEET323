import pypandoc, os

readme = r'''<div align="center">

# Hi there, I'm Satyajeet S. Desai 👋

### Software Developer · Java & Python · MERN Stack · Data Analytics & Engineering

<p>
  <a href="https://satyajeetdesai.vercel.app"><img src="https://img.shields.io/badge/Portfolio-Visit-111827?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="mailto:satyajeet.s.desai@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/SATYAJEET323"><img src="https://img.shields.io/badge/GitHub-SATYAJEET323-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rounded&color=0:0F172A,50:1D4ED8,100:06B6D4&height=4&section=header" width="100%" alt="Decorative banner">

</div>

## 👨‍💻 About Me

I'm a **Computer Engineering graduate (PCE, 2026)** interested in building useful software, developing full-stack applications, and turning data into meaningful insights. I have hands-on experience maintaining and enhancing web applications, building responsive interfaces, integrating APIs, working with databases, and deploying websites.

- 💻 **Development:** Java, Python, JavaScript, SQL, and the MERN stack
- 🌐 **Full-stack:** React, Node.js, Express.js, MongoDB, Next.js, and REST APIs
- 📊 **Data & AI:** Data analysis, data science, machine learning, and demand forecasting
- 🧰 **Tools:** Git, GitHub, Docker, Postman, DVC, and CI/CD
- 🧠 **Foundations:** OOP, Data Structures & Algorithms, DBMS, debugging, and problem-solving
- 🎯 **Open to:** Software Developer, Java Developer, Python Developer, MERN/Full Stack Developer, Data Analyst, and Data Engineer roles

I enjoy learning by building projects, exploring new technologies, and collaborating on practical solutions.

## 🛠️ Tech Stack

### Languages
<p>
  <img src="https://skillicons.dev/icons?i=java,python,js,sql&perline=8" alt="Java, Python, JavaScript, SQL">
</p>

### Full-Stack Development
<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,express,mongodb,mysql,html,css,tailwind&perline=9" alt="React, Next.js, Node.js, Express, MongoDB, MySQL, HTML, CSS, Tailwind CSS">
</p>

### Data, AI & Developer Tools
<p>
  <img src="https://skillicons.dev/icons?i=python,sklearn,docker,git,github,postman,vscode&perline=8" alt="Python, scikit-learn, Docker, Git, GitHub, Postman, VS Code">
</p>

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🤖 Intelli GD Bot</h3>
      <p>An AI-powered group discussion practice platform for students and professionals. It combines real-time discussion, AI-generated feedback, performance evaluation, and peer assessment.</p>
      <p><strong>Focus:</strong> MERN Stack · AI/LLM integration · Real-time communication</p>
    </td>
    <td width="50%" valign="top">
      <h3>📈 Seafood Demand Forecasting</h3>
      <p>A data-driven demand forecasting and inventory management system that uses historical sales data, feature engineering, and regression models to support demand planning.</p>
      <p><strong>Focus:</strong> Python · Data Science · Machine Learning · Forecasting</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🎓 EduBot</h3>
      <p>An AI-powered personalized learning platform featuring chatbot assistance, secure authentication, performance tracking, an SQL playground, learning modules, and an in-browser code editor.</p>
      <p><strong>Focus:</strong> MERN Stack · AI/ML · Learning tools · Dashboards</p>
    </td>
    <td width="50%" valign="top">
      <h3>🧩 What I'm Exploring</h3>
      <p>Building reliable backend services, improving my Java and Python development skills, and applying analytics and data engineering concepts to practical applications.</p>
      <p><strong>Focus:</strong> APIs · Databases · Data workflows · Clean code</p>
    </td>
  </tr>
</table>

## 📊 GitHub Activity

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=SATYAJEET323&show_icons=true&hide_border=true&rank_icon=github&theme=tokyonight" alt="GitHub statistics">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SATYAJEET323&layout=compact&hide_border=true&theme=tokyonight" alt="Most-used languages">
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=SATYAJEET323&theme=tokyonight&hide_border=true" alt="GitHub contribution streak">
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=SATYAJEET323&theme=tokyo-night&hide_border=true&area=true" width="100%" alt="GitHub contribution activity graph">
</div>

## 🌱 Currently Focused On

- Strengthening problem-solving and core programming skills in **Java and Python**
- Building maintainable full-stack applications with the **MERN stack**
- Practising SQL and exploring **data analysis and data engineering workflows**
- Learning through projects, experimentation, and continuous improvement

## 🤝 Let's Connect

I'm open to entry-level opportunities, internships, and collaborative projects across software development and data-focused roles.

<p>
  <a href="https://satyajeetdesai.vercel.app"><img src="https://img.shields.io/badge/Portfolio-Explore-2563EB?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="mailto:satyajeet.s.desai@gmail.com"><img src="https://img.shields.io/badge/Email-satyajeet.s.desai%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/SATYAJEET323"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
</p>

<div align="center">
  <i>“Build with curiosity. Improve with every iteration.”</i>
  <br><br>
  <img src="https://komarev.com/ghpvc/?username=SATYAJEET323&style=flat-square&color=2563EB" alt="Profile views">
</div>
'''

out = "/mnt/data/README.md"
pypandoc.convert_text(readme, "md", format="md", outputfile=out, extra_args=["--standalone"])
print(f"Created: {out}")
print(f"File size: {os.path.getsize(out)} bytes")
