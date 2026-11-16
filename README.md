<!--
═══════════════════════════════════════════════════════════════
  COMO EDITAR ESTE README (comentários não aparecem no perfil)

  • Links dos projetos  → bloco "LINKS" no final do arquivo.
                          Quando a Trilha subir na Vercel, troque
                          só a linha [trilha-demo]: e pronto.
  • Imagens / arte      → pasta /assets. Para trocar uma imagem,
                          substitua o arquivo mantendo o mesmo nome.
  • Badges              → geradas em https://shields.io
  • Heatmap             → /assets/contributions.svg é um SNAPSHOT
                          estático. Regere e substitua quando quiser.
═══════════════════════════════════════════════════════════════
-->

<h1 align="center">Bernardo Guimarães</h1>

<p align="center">
  <b>Full-stack developer — TypeScript on the front, Python and Node on the back.</b><br>
  CS student at Atitus Educação · Rio Grande do Sul, Brazil · Open to remote internship &amp; junior roles
</p>

<p align="center">
  <a href="https://bernardoportfolio.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/bernardoguimaraesdev"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:bernardocfguima@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://komarev.com/ghpvc/?username=Bernardocfguimaraes&style=for-the-badge&color=0A66C2&label=Profile+views" alt="Profile views">
</p>

---

## About

I build web products end to end — Next.js interfaces, typed APIs, relational data models — and lately I've been wiring machine learning and LLMs **into** the product rather than bolting them on top.

- 🛠️ Currently building **[Trilha][trilha-repo]** — learning diagnostics for Brazilian elementary schools: scikit-learn risk models, BNCC skill tracking, and LLM-generated practice, with a voice interface for teachers.
- 🚀 Shipped **[EloPet][elopet-demo]** — a full-stack micro-SaaS with OAuth2, Stripe payments, and a Prisma/PostgreSQL data layer.
- 🧩 Comfortable owning a feature from schema to deploy: validation, auth, tests, CI, and the button the user actually clicks.
- 📍 Based in Sarandi, RS — looking for **remote** opportunities.

<details>
<summary><code>$ cat bernardo.png | ascii --render</code></summary>

<br>

<p align="center">
  <img src="https://raw.githubusercontent.com/Bernardocfguimaraes/Bernardocfguimaraes/main/assets/drawille-portrait.svg" alt="Braille-rendered portrait" width="860">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Bernardocfguimaraes/Bernardocfguimaraes/main/assets/ascii-portrait.svg" alt="RGB ASCII portrait" width="840">
</p>

</details>

---

## How I ship

```mermaid
flowchart LR
    A["🧠 Problem"] --> B["🗂️ Data model<br/>PostgreSQL · Prisma · SQLAlchemy"]
    B --> C["⚙️ Typed API<br/>FastAPI · Express · Spring Boot"]
    C --> D["🎨 Interface<br/>Next.js · Tailwind · shadcn/ui"]
    D --> E["✅ Tests & CI<br/>pytest · ESLint · GitHub Actions"]
    E --> F["☁️ Deploy<br/>Vercel · Render · Supabase"]
```

Schema first, types everywhere, and nothing reaches the UI that hasn't been validated at the edge (Zod / Pydantic).

---

## Featured projects

| Project | What it is | Stack | Live |
|---|---|---|---|
| **[Trilha][trilha-repo]** | Learning-diagnostic platform: per-skill student tracking, early-warning signals for teachers, AI-generated exercises and voice Q&A | Next.js 16 · React 19 · FastAPI · SQLAlchemy · scikit-learn · Groq · Supabase | *soon* |
| **[EloPet][elopet-repo]** | Micro-SaaS for pet rescue profiles and donations — OAuth2 login, image uploads, real payments | Next.js · TypeScript · Prisma · PostgreSQL · Auth.js · Zod · Stripe | [demo][elopet-demo] |
| **[HolyGames][holygames-repo]** | Game discovery platform with a cyber-minimalist UI, server actions, and per-game social metadata | Next.js 15 · React Server Components · Tailwind · Framer Motion | [demo][holygames-demo] |
| **[SearchDevs][searchdevs-repo]** | GitHub user search built as a company technical challenge | React · JavaScript · REST API | [demo][searchdevs-demo] |

---

## Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=postgresql&logoColor=white)

**Front-end**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer%20Motion-0055FF?style=flat-square&logo=framer&logoColor=white)

**Back-end &amp; data**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

**AI &amp; data science**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

**Tooling**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)
![Pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

---

<details>
<summary><b>Beyond the featured four</b> — coursework, experiments and older builds</summary>

<br>

- **Java / OOP** — [Rest-API-SpringBoot](https://github.com/Bernardocfguimaraes/Rest-API-SpringBoot), [Biblioteca-Java](https://github.com/Bernardocfguimaraes/Biblioteca-Java), [Zoo-Digital](https://github.com/Bernardocfguimaraes/Zoo-Digital)
- **Node APIs** — [CRUD-EXPRESS](https://github.com/Bernardocfguimaraes/CRUD-EXPRESS), [API-CRUD-em-Node](https://github.com/Bernardocfguimaraes/API-CRUD-em-Node)
- **Data analysis** — exploratory analysis of public crime data from Rio Grande do Sul (2021–2026) with pandas: cleaning, consolidation and descriptive statistics
- **Security &amp; networks** — penetration testing on a vulnerable VM with Kali Linux (enumeration, CMS and exposed-`.git` exploitation); multi-router Cisco topology with RIP v2, DHCP, DNS and HTTPS
- **Games &amp; practice** — [Power Rangers: The Last Fire](https://github.com/Bernardocfguimaraes/Power-Rangers---The-Last-Fire), [Jogos Mortais](https://github.com/Bernardocfguimaraes/Jogos-Mortais) (Python)
- **Real-world work** — billing automation and front-end improvements during an internship at Revista Spelho; a management system built from scratch for a local school's administration

</details>

---

## Stats

<p align="center">
  <img src="https://raw.githubusercontent.com/Bernardocfguimaraes/Bernardocfguimaraes/main/assets/contributions.svg" alt="Contribution heatmap" width="866">
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Bernardocfguimaraes&show_icons=true&hide_border=true&theme=tokyonight&include_all_commits=true">
    <img src="https://github-readme-stats.vercel.app/api?username=Bernardocfguimaraes&show_icons=true&hide_border=true&include_all_commits=true" height="165" alt="GitHub stats">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Bernardocfguimaraes&layout=compact&hide_border=true&theme=tokyonight&langs_count=8">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Bernardocfguimaraes&layout=compact&hide_border=true&langs_count=8" height="165" alt="Top languages">
  </picture>
</p>

---

<p align="center">
  <i>Open to remote internships and junior developer roles — in Portuguese or English.</i><br>
  <a href="mailto:bernardocfguima@gmail.com">bernardocfguima@gmail.com</a> ·
  <a href="https://www.linkedin.com/in/bernardoguimaraesdev">LinkedIn</a> ·
  <a href="https://bernardoportfolio.vercel.app">Portfolio</a>
</p>

<!-- ══════════════════ LINKS — edite só aqui ══════════════════ -->
<!-- TRILHA_DEMO: quando subir na Vercel, cole a URL em [trilha-demo]
     e troque o "*soon*" da tabela por [demo][trilha-demo] -->

[trilha-repo]: https://github.com/Bernardocfguimaraes/trilha
[trilha-demo]: https://github.com/Bernardocfguimaraes/trilha
[elopet-repo]: https://github.com/Bernardocfguimaraes/EloPet
[elopet-demo]: https://elo-pet.vercel.app
[holygames-repo]: https://github.com/Bernardocfguimaraes/holygames
[holygames-demo]: https://holygames.vercel.app
[searchdevs-repo]: https://github.com/Bernardocfguimaraes/SearchDevs-Petize
[searchdevs-demo]: https://search-devs-kappa.vercel.app
