from pathlib import Path

readme = '''<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0B1020,50:151A3D,100:273C75&height=190&section=header&text=TolhaXnDev&fontSize=56&fontColor=FFFFFF&fontAlignY=42&desc=Vibe%20Coder%20%C3%97%20Developer%20%3C%2F%3E&descSize=18&descAlignY=68&animation=fadeIn" width="100%" alt="TolhaXnDev developer banner"/>

### Building ideas into digital experiences.

**AI-Assisted Development · Web Experiences · Telegram Bots · UI Concepts**

[![GitHub](https://img.shields.io/badge/GitHub-TolhaXnDev-111827?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TolhaXnDev)

</div>

---

## About

I'm **TolhaXnDev** — a Vibe Coder × Developer interested in turning ideas into useful, polished digital experiences.

- Building and experimenting with modern websites and interfaces.
- Exploring AI-assisted workflows to prototype, improve, and ship projects.
- Creating Telegram bot concepts, interactive demos, and web experiences.
- Focused on clean presentation, usability, and continuous learning.

> I use AI as a tool in my workflow, while learning, reviewing, and refining the work I build.

## What I Build

<table>
<tr>
<td width="50%" valign="top">

### 🌐 Web Experiences
Responsive websites, landing pages, and interactive front-end experiences.

</td>
<td width="50%" valign="top">

### 🤖 Telegram Bots
Bot concepts, automation experiments, and useful Telegram-based tools.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎨 UI & Web Design
Modern layouts, visual concepts, and user-focused interface experiments.

</td>
<td width="50%" valign="top">

### ⚡ Interactive Demos
Chat demos, animations, prototypes, and small experiments that bring ideas to life.

</td>
</tr>
</table>

## Tech Stack

> Keep only the technologies you genuinely use or are actively learning.

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

## Featured Projects

<!-- Replace these general categories with your real project names and live links. -->
<table>
<tr>
<td width="50%" valign="top">

### 🌐 Website Projects
Responsive websites and landing pages with a focus on visual quality and usability.

**[Explore repositories →](https://github.com/TolhaXnDev?tab=repositories)**

</td>
<td width="50%" valign="top">

### 🤖 Telegram Bots
Telegram bot projects, experiments, and automation ideas.

**[Explore repositories →](https://github.com/TolhaXnDev?tab=repositories)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎨 UI / Design Concepts
Interface explorations, polished layouts, and front-end prototypes.

**[Explore repositories →](https://github.com/TolhaXnDev?tab=repositories)**

</td>
<td width="50%" valign="top">

### 💬 Interactive Demos
Chat interfaces, animations, and experimental web features.

**[Explore repositories →](https://github.com/TolhaXnDev?tab=repositories)**

</td>
</tr>
</table>

## GitHub Overview

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=TolhaXnDev&show_icons=true&hide_border=true&bg_color=0B1020&title_color=60A5FA&icon_color=A78BFA&text_color=E5E7EB&rank_icon=github" alt="GitHub profile statistics"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TolhaXnDev&layout=compact&hide_border=true&bg_color=0B1020&title_color=60A5FA&text_color=E5E7EB" alt="Most used languages"/>

<img src="https://streak-stats.demolab.com?user=TolhaXnDev&hide_border=true&background=0B1020&ring=60A5FA&fire=A78BFA&currStreakLabel=E5E7EB&sideLabels=E5E7EB&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=9CA3AF" alt="GitHub contribution streak"/>

</div>

## Connect

<div align="center">

**Have an idea, project, or collaboration in mind?**

[![GitHub](https://img.shields.io/badge/GitHub-Follow%20my%20work-111827?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TolhaXnDev)

<!-- Add your real public links when ready:
[![Website](https://img.shields.io/badge/Website-Visit-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white)](YOUR_WEBSITE_URL)
[![Facebook](https://img.shields.io/badge/Facebook-Connect-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](YOUR_FACEBOOK_URL)
[![TikTok](https://img.shields.io/badge/TikTok-Follow-111827?style=for-the-badge&logo=tiktok&logoColor=white)](YOUR_TIKTOK_URL)
[![Telegram](https://img.shields.io/badge/Telegram-Message-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](YOUR_TELEGRAM_URL)
-->

</div>

---

<div align="center">

*Learning continuously. Building thoughtfully. Shipping one idea at a time.*

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:273C75,100:0B1020&height=70&section=footer" width="100%" alt="Footer banner"/>

</div>
'''
path = Path("/mnt/data/README.md")
path.write_text(readme, encoding="utf-8")
print(f"Created: {path} ({path.stat().st_size} bytes)")
