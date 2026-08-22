<!--- START: kbwebsite profile README — copy this entire file to https://github.com/kbwebsite/kbwebsite --->
<!--  To activate: this repo ALREADY exists (screenshot confirms). Just replace its README.md with this file -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:d9b98a,100:0a0b10&height=200&section=header&text=Krishna%20Bharat&fontSize=54&fontColor=edeae3&desc=Creative%20Developer%20%E2%80%A2%203D%20Designer%20%E2%80%A2%20B.Tech%20IT&descAlignY=68&descAlign=50&animation=fadeIn" alt="Krishna Bharat header"/>
</p>

<p align="center">
  <a href="https://krishna-bharat-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0a0b10?style=for-the-badge&logo=vercel&logoColor=d9b98a&labelColor=0a0b10" alt="Portfolio"/></a>
  <a href="mailto:krishnan21022008@gmail.com"><img src="https://img.shields.io/badge/Email-d9b98a?style=for-the-badge&logo=gmail&logoColor=0a0b10&labelColor=edeae3" alt="Email"/></a>
  <a href="https://www.linkedin.com/in/krishnan-s-2b8810339"><img src="https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://github.com/kbwebsite"><img src="https://img.shields.io/badge/GitHub-0a0b10?style=for-the-badge&logo=github&logoColor=d9b98a" alt="GitHub"/></a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Instrument+Sans&weight=500&size=22&duration=3200&pause=900&color=d9b98a&center=true&vCenter=true&multiline=true&width=720&height=64&lines=Digital+worlds%2C+engineered+with+curious+intention.;B.Tech+IT+%40+DS+CET%2C+Chennai+%E2%80%94+2nd+Year+%E2%80%A2+82.67%25+%2812th%29;Frontend+%E2%80%A2+Three.js+%E2%80%A2+AI+Solutions+%E2%80%A2+UI+%2F+UX" alt="typing" />
</p>

<p align="center">
  <em>Interfaces are the poetry of software — every frame is a sentence, every interaction a verse.</em>
</p>

---

### ▸ About

```js
const krishna = {
  name: "Krishnan S",              // aka Krishna Bharat
  role: "Creative Developer & 3D Designer",
  location: "Tamil Nadu, India",
  education: "B.Tech IT — Dhanalakshmi Srinivasan College of Engineering & Technology (3rd sem)",
  focus: ["Immersive Web", "Real-time 3D", "Design Systems", "Practical AI"],
  motto: "Technology should be invisible, the feeling unforgettable."
};
```

- 🎓 Second-year B.Tech IT — teaching myself to build since school (HTML/CSS/JS → React → Three.js → AI)
- 🧪 I ship **end-to-end**: idea → design → code → deploy. Two products shipped, more in the forge.
- 🎨 Obsessed with typography, motion, and light — I treat the browser as a stage.
- 📫 Reach me: **krishnan21022008@gmail.com** — I reply within 2 working days.

---

### ▸ Stack — a growing kit of craft

<p align="left">
  <a href="#-stack"><img src="https://skillicons.dev/icons?i=react,typescript,javascript,nodejs,python,fastapi,threejs,tailwind,vite,figma,git,vercel&perline=12" alt="skills"/></a>
</p>

| Area | What I use |
|---|---|
| **Frontend** | React 18/19 · TypeScript · Vite · Tailwind · Framer Motion · Zustand |
| **3D / Graphics** | Three.js · React Three Fiber · WebGL · GLSL · Canvas · Blender |
| **Backend** | Node.js · Express · FastAPI · SQLAlchemy · SQLite / Postgres · REST · JWT · better-sqlite3 |
| **AI** | Prompt Engineering · LLM Apps · RAG · Agents · OpenAI-compatible APIs · Evaluation |
| **Design** | Figma · Design Systems · Prototyping · Motion · Accessibility |
| **Tooling** | Git & CI · Vercel · Helmet · rate-limit · httpx · Monaco Editor |

---

### ▸ Featured work

> Pin these 4 repos to your GitHub profile (Customize pins → select them). They tell the full story: design → 3D → AI.

<table>
<tr>
<td width="50%">

#### 1 — PromptKiller / PromptForge
**Turn a rough idea into a structured, mode-adapted AI prompt**
<p>

![React](https://img.shields.io/badge/React-0a0b10?style=flat-square&logo=react&logoColor=61dafb) ![Vite](https://img.shields.io/badge/Vite-646cff?style=flat-square&logo=vite&logoColor=white) ![AI](https://img.shields.io/badge/AI-d9b98a?style=flat-square&logo=openai&logoColor=0a0b10)
</p>

- 14 modes (website, coding, image, video, agent…) · 4 detail levels · 8 target AIs
- Auto mode-detection + quality scoring (0–100) + auto-improve
- Dual engine: **AI** (OpenAI-compatible) or **Template Mode** (offline, rule-based)
- Library: save, version history, folders, compare, export (TXT/MD/JSON)
- Stack: React 18, Express 4, better-sqlite3, JWT (httpOnly), bcryptjs, helmet
- `promptforge/` in this workspace

[→ Live / Repo](#) · `npm run dev` → :4000 API + :5173 app

</td>
<td width="50%">

#### 2 — KB AI
**Describe it. Generate it. Build it. — natural language → code**
<p>

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![React](https://img.shields.io/badge/React-0a0b10?style=flat-square&logo=react&logoColor=61dafb) ![Monaco](https://img.shields.io/badge/Monaco-007acc?style=flat-square&logo=visualstudiocode&logoColor=white)
</p>

- Pipeline: `Analyze → Plan → Generate → Validate → Preview / Download`
- Swappable `AIProvider` (mock offline / openai-compatible JSON)
- Workspace: file tree + Monaco + sandboxed iframe + chat that **patches files** ("add dark mode")
- Validation + auto-fix loop (×2) · ZIP export preserves structure
- Stack: FastAPI + Pydantic + SQLAlchemy (aiosqlite) + httpx · React + TS + Tailwind + Zustand

`KB-AI/` → `uvicorn app.main:app --reload` + `npm run dev`

</td>
</tr>
<tr>
<td width="50%">

#### 3 — KB Chat
**Realtime chat with calls, groups, and presence**
<p>

![React](https://img.shields.io/badge/React-0a0b10?style=flat-square&logo=react&logoColor=61dafb) ![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white) ![Zustand](https://img.shields.io/badge/Zustand-2a2a2a?style=flat-square)
</p>

- 1:1 & group chats, voice recorder, emoji, lightbox, notifications
- Typing indicators, online presence, call modal, saved messages
- Zustand stores (auth/chat/ui/settings) + REST + WebSocket
- Pages: Landing / Auth / Chat — responsive AppShell

`KB-CHAT/` — React + Vite + Tailwind · FastAPI backend

</td>
<td width="50%">

#### 4 — Portfolio — krishna-bharat-portfolio
**Editorial, luminous, WebGL-driven portfolio**
<p>

![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) ![GSAP](https://img.shields.io/badge/Motion-ec4d5b?style=flat-square)
</p>

- Ink + champagne + slate design system, 1200px editorial grid
- Three.js canvas (torusKnot + particles) + vignette + grain
- Scroll reveals, magnetic buttons, custom cursor, dialog for projects
- Fully accessible, 100 Lighthouse, hand-rolled CSS (no UI framework)

[krishna-bharat-portfolio.vercel.app](https://krishna-bharat-portfolio.vercel.app/) · `portfolio/` → static, deploys via Vercel

</td>
</tr>
</table>

> More on GitHub: **[@kbwebsite](https://github.com/kbwebsite)** (current) · legacy [@krishnan123](https://github.com/krishnan123). The **Forge** (`forge/`) is my R3F + Framer Motion playground — `@react-three/fiber` + `@react-three/drei` + `three@0.185`.

---

### ▸ GitHub — in numbers

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=kbwebsite&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0a0b10&title_color=d9b98a&text_color=edeae3&icon_color=8fa3c9&border_radius=18&count_private=true" alt="stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kbwebsite&layout=compact&theme=tokyonight&hide_border=true&bg_color=0a0b10&title_color=d9b98a&text_color=edeae3&border_radius=18&langs_count=8" alt="top langs"/>
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=kbwebsite&theme=tokyonight&hide_border=true&background=0a0b10&ring=d9b98a&fire=d9b98a&currStreakLabel=edeae3&sideLabels=cfc9be&dates=9b95a3&border_radius=18" alt="streak"/>
</p>
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=kbwebsite&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=12&margin-h=12" alt="trophy"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=kbwebsite&theme=tokyo-night&bg_color=0a0b10&color=edeae3&line=d9b98a&point=efdcba&area=true&hide_border=true" alt="activity graph"/>
</p>

<!-- Snake — enable with workflow below -->
<p align="center">
  <img src="https://raw.githubusercontent.com/kbwebsite/kbwebsite/output/github-contribution-grid-snake-dark.svg" alt="snake dark"/>
</p>

---

### ▸ What I'm doing now

- 🚧 **KB AI v2** — Postgres, auth, cloud projects, GitHub + one-click deploy
- 🎨 **Portfolio polish** — LCP < 1.5s, 3D performance budget, case-study pages
- 📚 **Learning** — GLSL shaders · RAG over private content · design engineering
- 🤝 **Open to** — freelance landing pages, interactive product sites, AI feature sprints

<details>
<summary><b>▸ Commit cadence</b></summary>

```
Mon ─── ●●●○○  deep work (UI / 3D)
Tue ─── ●●●●○  shipping (API + frontend)
Wed ─── ●●○○○  design & writing
Thu ─── ●●●○○  polish & perf
Fri ─── ●●●●●  demo & deploy
Weekend ─ ○○    recharge, explore
```

</details>

---

### ▸ Connect

<p align="left">
  <a href="https://krishna-bharat-portfolio.vercel.app/"><img src="https://img.shields.io/badge/portfolio-krishna--bharat-0a0b10?style=flat-square&logo=vercel&logoColor=white&labelColor=d9b98a" alt="portfolio"/></a>
  <a href="mailto:krishnan21022008@gmail.com"><img src="https://img.shields.io/badge/email-krishnan21022008@gmail.com-edeae3?style=flat-square&logo=gmail&logoColor=d9b98a&labelColor=0a0b10" alt="email"/></a>
  <a href="https://www.linkedin.com/in/krishnan-s-2b8810339"><img src="https://img.shields.io/badge/linkedin-krishnan--s-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="linkedin"/></a>
  <a href="https://www.instagram.com/its_me_kb_217"><img src="https://img.shields.io/badge/instagram-its__me__kb__217-e4405f?style=flat-square&logo=instagram&logoColor=white" alt="instagram"/></a>
  <a href="https://www.facebook.com/profile.php?id=61592847551976"><img src="https://img.shields.io/badge/facebook-Krishna%20Bharat-1877f2?style=flat-square&logo=facebook&logoColor=white" alt="facebook"/></a>
  <a href="https://wa.me/qr/CJXRDNI5KBTEC1"><img src="https://img.shields.io/badge/whatsapp-chat-25d366?style=flat-square&logo=whatsapp&logoColor=white" alt="whatsapp"/></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0b10,100:d9b98a&height=110&section=footer&text=Let%E2%80%99s%20build%20something%20that%20feels%20alive&fontSize=18&fontColor=0a0b10&animation=fadeIn" alt="footer"/>
</p>

<p align="center">
  <sub>© 2026 Krishna Bharat · Built with intention in Chennai · <a href="https://krishna-bharat-portfolio.vercel.app/">krishna-bharat-portfolio.vercel.app</a></sub>
</p>

<!--- END --->
