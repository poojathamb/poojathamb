<div align="center">

<!-- ============ RESPONSIVE BANNER (LIGHT/DARK) ============ -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:2D0A1F,50:EF93C4,100:FF69B4&height=260&section=header&text=Welcome%20To%20My%20Profile&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Explore%20my%20work%2C%20projects%20%26%20passions&descAlignY=58&descSize=18">
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:FFF0F5,50:F8BBD0,100:EF93C4&height=260&section=header&text=Welcome%20To%20My%20Profile&fontSize=42&fontColor=4A154B&animation=fadeIn&fontAlignY=38&desc=Explore%20my%20work%2C%20projects%20%26%20passions&descAlignY=58&descSize=18">
  <img alt="Profile banner" src="https://capsule-render.vercel.app/api?type=waving&color=0:F8BBD0,50:EF93C4,100:FF69B4&height=260&section=header&text=Welcome%20To%20My%20Profile&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Explore%20my%20work%2C%20projects%20%26%20passions&descAlignY=58&descSize=18" width="100%">
</picture>

<!-- ============ TITLE ============ -->
<h1 align="center">Hey there, I'm <span style="color:#EF93C4">[Pooja]</span> 👋</h1>

<!-- ============ ANIMATED TYPING TEXT ============ -->

<!-- ============ SOCIAL / STAT BADGES ============ -->
<p align="center">
  <img src="https://img.shields.io/github/followers/[poojathamb]?label=Followers&style=for-the-badge&color=EF93C4&labelColor=1a1a1a" alt="GitHub followers"/>
  <img src="https://img.shields.io/github/stars/[poojathamb]?label=Stars&style=for-the-badge&color=F8BBD0&labelColor=1a1a1a" alt="GitHub stars"/>
  <img src="https://komarev.com/ghpvc/?username=[poojathamb]&label=Profile%20Views&style=for-the-badge&color=FF69B4&labelColor=1a1a1a" alt="Profile views"/>
</p>

<br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F8BBD0,100:EF93C4&height=3&width=1000" alt="divider">

</div>

<br>

## 💫 About Me

<table>
<tr>
<td width="65%" valign="top">

- 🔭 I'm currently working on **[Project Name]**
- 🌱 I'm currently learning **[Skill / Technology]**
- 👯 I'm looking to collaborate on **[Type of Project]**
- 💬 Ask me about **[Your Expertise / Topics]**
- 📫 How to reach me: **[your.email@example.com]**
- ⚡ Fun fact: **[A fun fact about you]**
- 🎯 Goal for [2026]: **[Your goal here]**

</td>
<td width="35%" valign="top" align="center">
<img src="[YOUR_ABOUT_ME_IMAGE_OR_GIF_URL]" width="100%" alt="About me visual"/>
</td>
</tr>
</table>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F8BBD0,100:EF93C4&height=3&width=1000" alt="divider">

## 🛠️ Tech Stack

<br>

<img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,nodejs,express,mongodb,postgres,python,git,github,figma,docker,aws,linux,vscode&theme=light" alt="Tech Stack"/>

<br><br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F8BBD0,100:EF93C4&height=3&width=1000" alt="divider">

## 📊 GitHub Stats

<br>

<img src="https://streak-stats.demolab.com/?user=[poojathamb]&theme=default&hide_border=true&background=0D1117&ring=EF93C4&fire=FF69B4&currStreakLabel=F8BBD0&sideLabels=EF93C4&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=F8BBD0" alt="GitHub Streak Stats" width="48%"/>
<img src="https://github-readme-stats.vercel.app/api?username=[poojathamb]&show_icons=true&hide_border=true&theme=default&bg_color=0D1117&title_color=EF93C4&icon_color=FF69B4&text_color=FFFFFF&ring_color=F8BBD0" alt="GitHub Stats" width="48%"/>

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=[poojathamb]&theme=react-dark&bg_color=0D1117&color=F8BBD0&line=EF93C4&point=FF69B4&area=true&hide_border=true" alt="GitHub Activity Graph" width="97%"/>

<br><br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F8BBD0,100:EF93C4&height=3&width=1000" alt="divider">

## 🐍 Contribution Snake

<br>

<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/poojathamb/poojathamb/output/pink-snake-dark.svg">
<source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/poojathamb/poojathamb/output/pink-snake.svg">
<img alt="Contribution Snake animation" src="https://raw.githubusercontent.com/poojathamb/poojathamb/output/pink-snake.svg" width="97%">
</picture>

<br><br>

<details>
<summary>⚙️ GitHub Action used to generate this snake (click to expand)</summary>

```yaml
# .github/workflows/snake.yml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"   # runs daily at midnight
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - name: Generate pink-themed snake animation
        uses: Platane/snk@v3
        with:
          github_user_name: [poojathamb]
          outputs: |
            dist/pink-snake.svg
            dist/pink-snake-dark.svg?palette=github-dark&color_snake=#FF69B4&color_dots=F8BBD0,F8BBD0,EF93C4,EF93C4,FF69B4

      - name: Push generated files to the "output" branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>

<br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F8BBD0,100:EF93C4&height=3&width=1000" alt="divider">

## 🤝 Connect With Me

<br>

<p align="center">
  <a href="https://linkedin.com/in/[your-linkedin]" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-EF93C4?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://instagram.com/[your-instagram]" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-F8BBD0?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/>
  </a>
  <a href="mailto:[your.email@example.com]" target="_blank">
    <img src="https://img.shields.io/badge/Email-FF69B4?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F8BBD0,50:EF93C4,100:FF69B4&height=150&section=footer" width="100%" alt="Footer wave">

<sub>✨ Thanks for stopping by — feel free to explore my pinned repositories below! ✨</sub>

</div>
