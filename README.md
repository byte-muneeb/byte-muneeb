# 👋 Hi, I'm Muneeb Ahmed Siddiqui

<p align="left">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/banner/dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./assets/banner/light.svg" />
    <img src="./assets/banner/dark.svg" alt="Animated profile banner for Muneeb Ahmed Siddiqui" width="100%" />
  </picture>
</p>

> ⚠️ **Banner placeholder mode:** `dark.svg` / `light.svg` are currently scaffold placeholders until your final portrait source is added.

---

## 👨‍💻 About Me
I’m a **Full-Stack Developer** on a specialized path toward **AI/ML Engineering**.  
I enjoy building products that connect robust backend systems with modern, polished user interfaces.

- 📍 **Location:** Karachi, Pakistan  
- 🎓 **Education:** BSSE — Bachelor of Science in Software Engineering *(in progress)*  
- ⚡ **Status:** `Do.Unique`

---

## 🧰 Core Stack

- **Core.Lang:** Python
- **Core.Frontend:** React
- **Core.Backend:** Python, Next.js
- **Core.Database:** MSSQL
- **Core.Infra/Tools:** Docker, Vercel, VS Code, Git, Figma, SQL

---

## 📊 GitHub Stats (Self-Hosted Setup)

> Public readme-stats instances are shared by thousands of users and often fail with API limit errors.
> For reliable cards, deploy your own fork and use your personal Vercel endpoint.

### 1) Create a GitHub Classic Token
Go to:
- **GitHub Settings → Developer settings → Personal access tokens → Tokens (classic)**
- Click **Generate new (classic)**
- Scope: **repo**
- Expiration: **No expiration**

⚠️ Copy it immediately and never expose it in public files, commits, screenshots, or README text.

### 2) Fork the stats repo
Fork: `anuraghazra/github-readme-stats`

### 3) Deploy fork to Vercel (Hobby/free)
- Sign in to Vercel with GitHub
- **Add New Project**
- Import your forked repository

### 4) Add env variable and deploy
In Vercel project settings:
- `PAT_1 = <your_github_classic_token>`

Deploy.

### 5) Replace `YOUR_VERCEL_INSTANCE`
After deploy, set your base URL below (example: `your-stats.vercel.app`):

```md
<p align="left">
  <img width="100%" src="https://streak-stats.demolab.com?user=byte-muneeb&theme=transparent&hide_border=true&ring=22D3EE&fire=10B981&currStreakLabel=22D3EE&sideLabels=A78BFA&dates=7C3AED" alt="GitHub Streak" />
</p>

<p align="left">
  <img width="49%" src="https://YOUR_VERCEL_INSTANCE/api?username=byte-muneeb&show_icons=true&hide_border=true&title_color=22D3EE&icon_color=10B981&text_color=A78BFA&bg_color=0A101F&hide_rank=true" alt="GitHub Stats" />
  <img width="49%" src="https://YOUR_VERCEL_INSTANCE/api/top-langs/?username=byte-muneeb&layout=compact&hide_border=true&title_color=22D3EE&text_color=A78BFA&bg_color=0A101F" alt="Top Languages" />
</p>