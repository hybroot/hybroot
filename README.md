<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d0d,50:1a1a2e,100:00b4d8&height=160&section=header&text=HYBROOT&fontSize=58&fontColor=00b4d8&fontAlignY=40&animation=fadeIn&desc=Android%20Engineer%20·%20HYBROOT%20Company&descSize=15&descAlignY=62&descColor=8892a4" alt="HYBROOT Banner"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=1000&color=00B4D8&center=true&vCenter=true&repeat=true&width=600&lines=Learning+Android+development+from+first+principles.;Architecture+before+code.+Quality+before+speed.;Building+toward+HYBROOT+Company.)](https://git.io/typing-svg)

<br/>

<a href="https://github.com/YourUsername?tab=followers">
  <img src="https://img.shields.io/github/followers/YourUsername?label=Followers&style=flat-square&color=00b4d8&labelColor=0d1117&logo=github&logoColor=ffffff"/>
</a>
&nbsp;
<img src="https://komarev.com/ghpvc/?username=YourUsername&style=flat-square&color=00b4d8&labelColor=0d1117&label=Profile+Views"/>
&nbsp;
<a href="https://github.com/YourUsername?tab=repositories&sort=stargazers">
  <img src="https://img.shields.io/github/stars/YourUsername?style=flat-square&color=00b4d8&labelColor=0d1117&logo=github&logoColor=ffffff&label=Stars"/>
</a>

</div>

---

<br/>

## HYBROOT

**Android Developer · HYBROOT Company**

Learning Android development with a structured, architecture-first approach. Currently building a portfolio of documented, well-structured projects before a Play Store launch.

My focus is on understanding systems before shipping them.

<br/>

---

<br/>

## ▸ Now

| | |
|---|---|
| **Learning** | Kotlin, Jetpack Compose, Clean Architecture |
| **Building** | Pet Project #1 — [coming soon] |
| **Reading** | Android documentation, architectural patterns |
| **Challenge** | Maintaining consistency across the full learning arc |

<br/>

---

<br/>

## ▸ About

```kotlin
object HYBROOT {

    val status   = "Junior Android Developer (in progress)"
    val company  = "HYBROOT Company"
    val approach = listOf("Architecture first", "Understand before ship", "Document everything")
    val goal     = "Three portfolio projects → Play Store → Sustainable product"
    val horizon  = "10–20 year compounding mindset"
}
```

<br/>

I approach software development as an engineering discipline. Before writing code, I define the architecture. Before releasing, I document. Every repository I publish follows a consistent standard — README, architecture diagram, planned roadmap.

I am at an early stage. The work being done here is honest: learning, building, and iterating in public.

<br/>

---

<br/>

## ▸ Development Principles

<table>
<tr>
<td width="50%" valign="top">

**Code**
- Readability is not a preference — it is a standard
- Abstractions must earn their existence
- Immutable state by default; mutations are explicit
- Fail fast: validate at boundaries, not deep in the stack

</td>
<td width="50%" valign="top">

**Process**
- Architecture decisions before first line of code
- Interfaces defined before implementations
- Tests at every layer boundary
- No placeholder commits — each one serves a purpose

</td>
</tr>
</table>

<br/>

---

<br/>

## ▸ Tech Stack

<div align="center">

**Platform**

<p>
  <img src="https://skillicons.dev/icons?i=kotlin,java,androidstudio,gradle&theme=dark"/>
</p>

**UI**

<p>
  <img src="https://skillicons.dev/icons?i=figma&theme=dark"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white&labelColor=0d1117"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Material%20Design%203-757575?style=flat-square&logo=materialdesign&logoColor=white&labelColor=0d1117"/>
</p>

**Architecture & Data**

<p>
  <img src="https://img.shields.io/badge/MVVM-00b4d8?style=flat-square&logoColor=white&labelColor=0d1117&logo=android"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Clean%20Architecture-00b4d8?style=flat-square&logoColor=white&labelColor=0d1117&logo=android"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Room-FF6F00?style=flat-square&logo=sqlite&logoColor=white&labelColor=0d1117"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Retrofit-48B983?style=flat-square&logo=square&logoColor=white&labelColor=0d1117"/>
</p>

**Async & DI**

<p>
  <img src="https://img.shields.io/badge/Coroutines-7F52FF?style=flat-square&logo=kotlin&logoColor=white&labelColor=0d1117"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Flow-7F52FF?style=flat-square&logo=kotlin&logoColor=white&labelColor=0d1117"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Hilt-FF6F00?style=flat-square&logo=android&logoColor=white&labelColor=0d1117"/>
</p>

**Infrastructure**

<p>
  <img src="https://skillicons.dev/icons?i=firebase,git,github&theme=dark"/>
</p>

</div>

<br/>

---

<br/>

## ▸ Architecture Model

<details>
<summary><strong>Expand — Layer Structure</strong></summary>

<br/>

```
┌─────────────────────────────────────────────┐
│                 Presentation                │  ← Compose UI · ViewModel · UI State
├─────────────────────────────────────────────┤
│                   Domain                   │  ← Use Cases · Entities · Business Logic
├─────────────────────────────────────────────┤
│                    Data                    │  ← Repository · Room · Retrofit · Firebase
└─────────────────────────────────────────────┘
         Dependency rule: always inward only.
```

**Constraints I apply to every project**

| Rule | Reason |
|------|--------|
| No business logic in ViewModel | Use Cases own domain logic |
| No framework imports in Domain | Domain is framework-agnostic |
| Repository always behind interface | Testable, swappable data sources |
| UI layer observes; never writes directly | Single source of truth |
| Sealed classes for UI state | Exhaustive handling enforced by compiler |

</details>

<br/>

---

<br/>

## ▸ Portfolio (in progress)

> Building three projects before registering a Play Developer account.  
> Each project will include: README · Architecture diagram · Screenshots · Roadmap.

<br/>

<table>
<tr>
<td width="33%" valign="top" align="center">

**Project #1**
`[in progress]`

`kotlin` `compose` `room` `mvvm`

Status: building

</td>
<td width="33%" valign="top" align="center">

**Project #2**
`[planned]`

`kotlin` `retrofit` `hilt` `flow`

Status: planned

</td>
<td width="33%" valign="top" align="center">

**Project #3**
`[planned]`

`kotlin` `firebase` `clean-arch`

Status: planned

</td>
</tr>
</table>

<br/>

---

<br/>

## ▸ Repository Standard

Every repository I publish follows this checklist:

```
☐  README with purpose, setup, and architecture overview
☐  Architecture diagram or description
☐  Module and package structure documented
☐  Dependencies listed with versions
☐  Screenshots or screen recordings
☐  Roadmap section with current status
☐  License
```

Discipline is visible in the structure of repositories before a single line of code is evaluated.

<br/>

---

<br/>

## ▸ Roadmap

```
2025 ─────────────────────────────────────────────────────────────────
  ✓  Kotlin fundamentals
  ✓  Jetpack Compose basics
  ✓  MVVM + Clean Architecture pattern
  →  Hilt · advanced Flow · Room at scale
  →  Retrofit + structured error handling

2026 ─────────────────────────────────────────────────────────────────
  ◯  Pet Project #1 shipped to GitHub (documented)
  ◯  Pet Project #2 shipped to GitHub
  ◯  Pet Project #3 shipped to GitHub
  ◯  Play Developer account registered
  ◯  First Play Store release

Long-term ────────────────────────────────────────────────────────────
  ◯  HYBROOT Company — public product suite
  ◯  YouTube technical channel active
  ◯  Sustainable revenue from at least one channel
  ◯  Contribute to Android OSS ecosystem
```

<br/>

---

<br/>

## ▸ GitHub Analytics

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api?username=YourUsername&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00b4d8&icon_color=00b4d8&text_color=8892a4&rank_icon=github"/>
&nbsp;&nbsp;
<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YourUsername&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00b4d8&text_color=8892a4&langs_count=6"/>

<br/><br/>

<img width="68%" src="https://streak-stats.demolab.com?user=YourUsername&theme=github-dark-blue&hide_border=true&background=0d1117&ring=00b4d8&fire=00b4d8&currStreakLabel=00b4d8&sideLabels=8892a4&dates=8892a4&sideNums=ffffff&currStreakNum=ffffff"/>

</div>

<br/>

---

<br/>

## ▸ Contribution Activity

<div align="center">

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=YourUsername&bg_color=0d1117&color=8892a4&line=00b4d8&point=ffffff&area=true&area_color=00b4d8&hide_border=true"/>

</div>

<br/>

---

<br/>

## ▸ Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/YourUsername/YourUsername/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/YourUsername/YourUsername/output/github-contribution-grid-snake.svg"/>
  <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/YourUsername/YourUsername/output/github-contribution-grid-snake-dark.svg"/>
</picture>

</div>

<br/>

---

<br/>

## ▸ Achievements

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=YourUsername&theme=darkhub&no-frame=true&no-bg=true&margin-w=6&column=6"/>

</div>

<br/>

---

<br/>

## ▸ Contact

<div align="center">

<a href="mailto:your@email.com">
  <img src="https://img.shields.io/badge/Email-0d1117?style=flat-square&logo=gmail&logoColor=00b4d8&label=Contact"/>
</a>
&nbsp;
<a href="https://www.linkedin.com/in/YourProfile">
  <img src="https://img.shields.io/badge/LinkedIn-0d1117?style=flat-square&logo=linkedin&logoColor=00b4d8&label=Connect"/>
</a>
&nbsp;
<a href="https://www.youtube.com/@YourChannel">
  <img src="https://img.shields.io/badge/YouTube-0d1117?style=flat-square&logo=youtube&logoColor=00b4d8&label=HYBROOT"/>
</a>

</div>

<br/>

---

<br/>

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00b4d8,50:1a1a2e,100:0d0d0d&height=110&section=footer&animation=fadeIn"/>

<sub><code>HYBROOT · HYBROOT Company · Building in public</code></sub>

<br/><br/>

<img src="https://img.shields.io/badge/Made%20with-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white&labelColor=0d1117"/>
&nbsp;
<img src="https://img.shields.io/badge/Target-Android-3DDC84?style=flat-square&logo=android&logoColor=white&labelColor=0d1117"/>
&nbsp;
<img src="https://img.shields.io/badge/Brand-HYBROOT-00b4d8?style=flat-square&logoColor=white&labelColor=0d1117"/>

</div>
