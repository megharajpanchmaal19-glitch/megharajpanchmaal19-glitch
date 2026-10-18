<!-- Profile README for github.com/megharajpanchmaal19-glitch -->
<!-- Save as README.md in a PUBLIC repo named exactly: megharajpanchmaal19-glitch -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=210&color=0:0d1117,55:0e7490,100:6d28d9&text=Megharaj%20Panchmaal&fontColor=e6edf3&fontSize=44&fontAlignY=38&desc=Tinkering%20with%20abstractions%2C%20decoding%20complexity%20%26%20chasing%20ubiquity.&descSize=15&descAlignY=60&animation=fadeIn" alt="Megharaj Panchmaal banner" />

<a href="https://github.com/megharajpanchmaal19-glitch">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=17&pause=1400&color=22D3EE&center=true&vCenter=true&width=640&height=30&lines=MCA+student+%C2%B7+Aspiring+software+developer;Python+%C2%B7+Django+%C2%B7+Flask+%C2%B7+React+%C2%B7+MySQL;Turning+logic+into+working+systems" alt="Typing animation" />
</a>

</div>

<br />

## About me

I'm an **MCA student and aspiring software developer** who likes taking an idea from a blank folder to a running system: a Django or Flask backend, a clean frontend, and a database that holds up under the features. My public projects so far include a Dockerised fuel-booking platform, a graph-database demo for financial-network analysis, and two Django + MySQL web apps.

I'm currently working on getting stronger in **data structures and algorithms**, and exploring **Java with Spring Boot** and **AWS** as the next step beyond my Python and JavaScript work.

<br />

## Tech stack

| | |
|---|---|
| **Languages** | <img src="https://skillicons.dev/icons?i=python,js,html,css&theme=dark" alt="Python, JavaScript, HTML, CSS" /> |
| **Frontend** | <img src="https://skillicons.dev/icons?i=react,vite,tailwind,html,css&theme=dark" alt="React, Vite, Tailwind CSS, HTML, CSS" /> |
| **Backend** | <img src="https://skillicons.dev/icons?i=django,flask,fastapi,nodejs&theme=dark" alt="Django, Flask, FastAPI, Node.js" /> |
| **Databases** | <img src="https://skillicons.dev/icons?i=mysql,neo4j&theme=dark" alt="MySQL, Neo4j" /> |
| **DevOps** | <img src="https://skillicons.dev/icons?i=docker,nginx,jenkins&theme=dark" alt="Docker, Nginx, Jenkins" /> |
| **Tools** | <img src="https://skillicons.dev/icons?i=git,github,postman,vscode&theme=dark" alt="Git, GitHub, Postman, VS Code" /> |
| **Learning next** | <img src="https://skillicons.dev/icons?i=java,spring,aws&theme=dark" alt="Java, Spring Boot, AWS" /> |

<br />

## Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/megharajpanchmaal19-glitch/e-fuel">E-Fuel</a></h3>
      <b>Online fuel booking system</b><br /><br />
      Customers browse fuel types and stations and place delivery or pickup orders; admins manage users, fuels, stations and bookings.<br /><br />
      <b>Stack:</b> React, Vite, Tailwind CSS, Flask, SQLAlchemy, MySQL, Nginx, Docker Compose, Jenkins<br /><br />
      <b>Highlights:</b> JWT-based auth, role-based admin area, Postman collection, Jenkins pipeline
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/megharajpanchmaal19-glitch/trace-room-preview">Trace Room</a></h3>
      <b>Financial-network analysis demo</b><br /><br />
      A browser UI for exploring cases, entities, transactions and evidence as a graph. Uses synthetic Indian-context data only.<br /><br />
      <b>Stack:</b> JavaScript, FastAPI, Neo4j<br /><br />
      <b>Highlights:</b> persists to a local Neo4j database through an API, and falls back to a local preview mode when the API is offline
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/megharajpanchmaal19-glitch/codealpha_smartbot">SmartBot</a></h3>
      <b>Rule-based chatbot web app</b><br /><br />
      A Django chatbot with keyword and intent matching, per-visitor conversation history stored in MySQL, and a responsive chat UI.<br /><br />
      <b>Stack:</b> Python, Django, MySQL (XAMPP), HTML, CSS, JavaScript<br /><br />
      <b>Highlights:</b> session-isolated history, REST endpoints, server-side validation, CSRF protection, unit tests
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/megharajpanchmaal19-glitch/codealpha_stockportfolio">Stock Portfolio Tracker</a></h3>
      <b>Simulated portfolio manager</b><br /><br />
      Add, edit and remove holdings and see total investment, calculated server-side. Uses fixed sample prices, not live market data.<br /><br />
      <b>Stack:</b> Python, Django, MySQL, HTML, CSS, JavaScript, GitHub Actions<br /><br />
      <b>Highlights:</b> JSON API, CSV export, backend input validation, automated tests
    </td>
  </tr>
</table>

<details>
<summary><b>How to run each project</b></summary>

<br />

**E-Fuel** (Docker)

```bash
git clone https://github.com/megharajpanchmaal19-glitch/e-fuel.git
cd e-fuel
cp .env.example .env
docker compose up --build -d
# open http://localhost
```

**Trace Room** (Neo4j Desktop + Python + Node)

```bash
# 1. Start a local DBMS in Neo4j Desktop
# 2. API
cd backend && python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload --port 8000
# 3. Frontend (project root, second terminal)
npm start
```

Set the Neo4j and admin environment variables first. The repository README lists them.

**SmartBot** (Django + MySQL via XAMPP)

```bash
git clone https://github.com/megharajpanchmaal19-glitch/codealpha_smartbot.git
cd codealpha_smartbot
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
# start MySQL in XAMPP and create a database named smartbot_db
python manage.py migrate
python manage.py runserver
```

**Stock Portfolio Tracker** (Django + MySQL via XAMPP)

```bash
git clone https://github.com/megharajpanchmaal19-glitch/codealpha_stockportfolio.git
cd codealpha_stockportfolio
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
# start MySQL in XAMPP and create a database named stockportfolio
cd config
python manage.py migrate
python manage.py runserver
```

</details>

<br />

## GitHub stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=megharajpanchmaal19-glitch&show_icons=true&hide_border=true&bg_color=0d1117&title_color=22d3ee&icon_color=a78bfa&text_color=c9d1d9" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=megharajpanchmaal19-glitch&layout=compact&hide_border=true&bg_color=0d1117&title_color=22d3ee&text_color=c9d1d9" alt="Most used languages" />

<img src="https://streak-stats.demolab.com?user=megharajpanchmaal19-glitch&hide_border=true&background=0d1117&ring=22d3ee&fire=a78bfa&currStreakLabel=22d3ee&sideLabels=c9d1d9&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=8b949e" alt="Contribution streak" />

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=megharajpanchmaal19-glitch&hide_border=true&bg_color=0d1117&color=22d3ee&line=a78bfa&point=ffffff&area=true&area_color=22d3ee" alt="Contribution activity graph" />

</div>

<br />

## Coding philosophy

```js
while (curious) { learn(); build(); debug(); repeat(); }
```

<br />

## Connect with me

<a href="https://github.com/megharajpanchmaal19-glitch"><img src="https://img.shields.io/badge/GitHub-megharajpanchmaal19--glitch-0d1117?style=for-the-badge&logo=github&logoColor=22d3ee" alt="GitHub" /></a>
<!--
Add your own links below, then delete these comment markers.
Replace YOUR-LINKEDIN-ID and YOUR-EMAIL with your real details.

<a href="https://www.linkedin.com/in/YOUR-LINKEDIN-ID"><img src="https://img.shields.io/badge/LinkedIn-Connect-0d1117?style=for-the-badge&logo=linkedin&logoColor=22d3ee" alt="LinkedIn" /></a>
<a href="mailto:YOUR-EMAIL"><img src="https://img.shields.io/badge/Email-Contact-0d1117?style=for-the-badge&logo=gmail&logoColor=a78bfa" alt="Email" /></a>
-->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=90&color=0:6d28d9,45:0e7490,100:0d1117&section=footer" alt="" />
