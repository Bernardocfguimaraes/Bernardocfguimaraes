<!--
═══════════════════════════════════════════════════════════════
  COMO EDITAR ESTE README (comentários não aparecem no perfil)

  • Links dos projetos  → bloco "LINKS" no final do arquivo.
                          Quando a Trilha subir na Vercel, troque
                          só a linha [trilha-demo]: e pronto.
  • Imagens / arte      → pasta /assets. Para trocar uma imagem,
                          substitua o arquivo mantendo o mesmo nome.
  • Badges              → geradas em https://shields.io
═══════════════════════════════════════════════════════════════
-->

<h1 align="center">Bernardo Guimarães</h1>

<p align="center">
  <b>Full-stack developer — Next.js · TypeScript · Node.js · Python</b><br>
  CS student at Atitus Educação · Sarandi, Rio Grande do Sul, Brazil · Open to remote internship &amp; junior roles
</p>

<p align="center">
  <a href="https://bernardoportfolio.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/bernardoguimaraesdev"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:bernardocfguima@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://komarev.com/ghpvc/?username=Bernardocfguimaraes&style=for-the-badge&color=0A66C2&label=Profile+views" alt="Profile views">
</p>

---

## About

I build web products end to end — Next.js interfaces, typed APIs, relational data models — with two apps in production and real client systems built from scratch. Lately I've been wiring machine learning and LLMs **into** the product rather than bolting them on top.

- 🛠️ Currently building **[Trilha][trilha-repo]** — learning diagnostics for Brazilian elementary schools: scikit-learn risk models, BNCC skill tracking, and LLM-generated practice, with a voice interface for teachers.
- 🚀 Shipped **[EloPet][elopet-demo]** — a micro-SaaS with OAuth2, Stripe payments, and a Prisma/PostgreSQL data layer.
- 🧩 Comfortable owning a feature from schema to deploy: validation, auth, tests, CI, and the button the user actually clicks.
- 🎓 AWS Academy Graduate — Cloud Foundations.

---

## How I ship

```mermaid
flowchart LR
    A["🧠 Problem"] --> B["🗂️ Data model<br/>PostgreSQL · Prisma · SQLAlchemy"]
    B --> C["⚙️ Typed API<br/>Server Actions · FastAPI · Express"]
    C --> D["🎨 Interface<br/>Next.js · Tailwind · Framer Motion"]
    D --> E["✅ Tests & CI<br/>pytest · ESLint · GitHub Actions"]
    E --> F["☁️ Deploy<br/>Vercel · Render · Supabase"]
```

Schema first, types end to end, and nothing reaches the UI that hasn't been validated at the edge (Zod / Pydantic).

---

## Featured projects

| Project | What it is | Stack | Live |
|---|---|---|---|
| **[Trilha][trilha-repo]** | Learning diagnostics with ML + LLMs: per-skill tracking against the BNCC curriculum, early-warning signals for teachers, AI-generated practice and voice Q&A about the class | `Next.js 16` `React 19` `FastAPI` `SQLAlchemy` `scikit-learn` `Groq` `Supabase` | *soon* |
| **[EloPet][elopet-repo]** | Micro-SaaS for pet rescue profiles and online donations. TypeScript end to end with typed Server Actions, removing intermediate REST endpoints | `Next.js (App Router)` `TypeScript` `OAuth2` `Stripe` `PostgreSQL` `Prisma` `Zod` | [live][elopet-demo] |
| **[HolyGames][holygames-repo]** | Game discovery platform: React Server Components for optimized rendering and indexing, skeleton loading states, dynamic SEO via Open Graph and per-route meta tags | `Next.js 15` `React Server Components` `Tailwind CSS` `Framer Motion` | [live][holygames-demo] |
| **[GitHub Profile Explorer][searchdevs-repo]** | Technical challenge (Petize): infinite scroll with Intersection Observer, PT-BR/EN-US i18n, dynamic metadata per profile, CacheProvider against hydration mismatch in SSR | `Next.js` `TypeScript` `generateMetadata` `SSR` | [live][searchdevs-demo] |

---

## Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=postgresql&logoColor=white)

**Front-end**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer%20Motion-0055FF?style=flat-square&logo=framer&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Back-end &amp; data**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)

**AI &amp; data**

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
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

---

## Experience

**Revista Spelho** — Technical Support &amp; Media Intern · *Mar 2025 – Feb 2026*
Automated the billing control spreadsheets, removing manual payment-status updates and cutting operational errors. Shipped front-end improvements to the company site and handled client support and digital channels.

**Secretaria Escola Sarandi** — Media Assistant · *Jan 2024 – Feb 2025*
Built a database-backed web system to manage the school office's records, replacing manual processes, plus an internal management module for the student union.

---

## Education &amp; certifications

**BSc in Computer Science** — Atitus Educação, Passo Fundo/RS · 3rd semester, expected Dec 2028

**[AWS Academy Graduate — Cloud Foundations][aws-cert]** — Amazon Web Services, Jun 2026

**Languages** — Portuguese (native) · Spanish (advanced) · English (intermediate)

---

## `$ ./render --me`

<p align="center">
  <img src="assets/drawille-portrait.svg" alt="Braille-rendered portrait" width="860">
</p>

<p align="center">
  <img src="assets/ascii-portrait.svg" alt="RGB ASCII portrait" width="840">
</p>

---

<p align="center">
  <i>Open to remote internships and junior developer roles — in Portuguese, Spanish or English.</i><br>
  <a href="mailto:bernardocfguima@gmail.com">bernardocfguima@gmail.com</a> ·
  <a href="https://www.linkedin.com/in/bernardoguimaraesdev">LinkedIn</a> ·
  <a href="https://bernardoportfolio.vercel.app">Portfolio</a>
</p>

<!-- ══════════════════ LINKS — edite só aqui ══════════════════ -->
<!-- TRILHA_DEMO: quando subir na Vercel, cole a URL em [trilha-demo]
     e troque o "*soon*" da tabela por [live][trilha-demo] -->

[trilha-repo]: https://github.com/Bernardocfguimaraes/trilha
[trilha-demo]: https://github.com/Bernardocfguimaraes/trilha
[elopet-repo]: https://github.com/Bernardocfguimaraes/EloPet
[elopet-demo]: https://elo-pet.vercel.app
[holygames-repo]: https://github.com/Bernardocfguimaraes/holygames
[holygames-demo]: https://holygames.vercel.app
[searchdevs-repo]: https://github.com/Bernardocfguimaraes/SearchDevs-Petize
[searchdevs-demo]: https://search-devs-kappa.vercel.app
[aws-cert]: https://www.credly.com/go/MbXhNnrD
