![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:161b22&height=180&section=header&text=Yahia%20Mohamed%20Zakaria&fontSize=36&fontColor=e6edf3&animation=fadeIn&fontAlignY=35&desc=Backend%20Software%20Engineer&descSize=16&descColor=8b949e&descAlignY=55)

<div align="center">

<a href="https://yahia.website">
  <img src="https://img.shields.io/badge/Portfolio-yahia.website-0a0a0a?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio" />
</a>
<a href="https://www.linkedin.com/in/yahiamzakaria/">
  <img src="https://img.shields.io/badge/LinkedIn-yahiamzakaria-0a0a0a?style=flat-square&logo=linkedin&logoColor=0A66C2" alt="LinkedIn" />
</a>
<a href="mailto:devyahiazakaria@gmail.com">
  <img src="https://img.shields.io/badge/Email-devyahiazakaria-0a0a0a?style=flat-square&logo=gmail&logoColor=EA4335" alt="Email" />
</a>

<br/><br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3000&pause=1000&color=8b949e&center=true&vCenter=true&multiline=false&width=800&height=30&lines=Building+scalable+production+backend+systems;From+payment+pipelines+to+container+orchestration;Node.js+%7C+NestJS+%7C+PostgreSQL+%7C+Docker+%7C+AWS" alt="Typing SVG" />
</a>

</div>

---

I build backend systems, deploy them, and keep them running. My work spans production platforms handling real users and real money - from e-commerce with payment processing and video streaming, to cryptocurrency exchange bots on the TON blockchain, to security training platforms where each lab runs in its own isolated container. I care about the decisions that happen between the framework and the infrastructure: how data flows, how things fail, and how they recover.

Final-year Communication and Computer Engineering student at Mansoura University, graduating 2027.

---

### Tech Stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,nodejs,express,nestjs,py,fastapi&theme=dark&perline=6" alt="Backend" />
  </a>
</p>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=postgres,mongodb,prisma,redis&theme=dark&perline=4" alt="Databases" />
  </a>
</p>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=docker,aws,githubactions,linux,nginx,nextjs&theme=dark&perline=6" alt="Infrastructure" />
  </a>
</p>

---

### Engineers Arena
> Production e-commerce and manufacturing platform - private client work

Built the backend with NestJS, PostgreSQL, and Prisma. Handled video delivery via HLS streaming with AWS S3 for object storage. Implemented background job processing with BullMQ, an outbox pattern for reliable event delivery, and idempotency keys on payment flows. Deployed through a hardened Docker Compose setup with Caddy for TLS termination.

### Real World CTF
> Security training platform with live, isolated lab environments

Built the full platform: a Next.js frontend, PostgreSQL database via Prisma, session-based auth, and a scenario management system for admins. The core differentiator is the lab runner - a service that pulls private Docker images from GHCR on demand and launches them in strictly isolated containers (`--read-only`, `--cap-drop ALL`, `--no-new-privileges`) on a dedicated network, accessible only through an nginx reverse proxy behind Caddy. Each lab is a real vulnerable environment, not a simulation.

### ASTRA
> Telegram Stars to USDT exchange bot with Mini App - [github.com/devYahia/ASTRA](https://github.com/devYahia/ASTRA)

A production Telegram bot and React Mini App for converting Telegram Stars into USDT on the TON blockchain. Handles the full payment lifecycle: Telegram Stars payment processing, TON wallet integration (v4r2) for USDT Jetton transfers, a cashback rewards system, and an admin dashboard with refund management and audit trails. Python, FastAPI, PostgreSQL.

### InnoFab
> 3D printing e-commerce platform - [innofab.net](https://innofab.net)

Built the storefront and custom fabrication ordering system for a 3D printing business. Product catalog, category filtering, and a custom print request pipeline.

### Interna.work
> AI-powered internship simulator - [interna.work](https://interna.work)

Built the backend and database layer with FastAPI and PostgreSQL during a 3-day hackathon. Placed 14th out of 122 teams at GDG Hackathon 2026.

### First Word
> Arabic Sign Language translation on Meta Quest 3 - graduation project

Backend engineer handling the speech pipeline integration (speech-to-text and text-to-speech) feeding the Unity VR recognition layer.

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=devYahia&show_icons=true&theme=tokyonight_duo&hide_border=true&border_radius=0&card_width=400" alt="GitHub Stats" />

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=devYahia&layout=compact&theme=tokyonight&hide_border=true&border_radius=0&card_width=400&langs_count=6" alt="Top Languages" />

</div>

<br/>

<div align="center">
<sub>Open to software engineering roles, freelance system development, and AI data annotation work.</sub>
</div>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:161b22&height=100&section=footer)
