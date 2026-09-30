<picture>
  <source media="(prefers-reduced-motion: reduce)" srcset="./assets/hero.png">
  <img src="./assets/hero.gif" alt="Nicolas Lasch — Useful systems. Unexpected worlds. An original pixel explorer stands beside a portal in a quiet, dotted landscape." width="100%">
</picture>

# Nicolas Lasch

**Software engineer & AI researcher.** Based in Belgium. Master's degree in Design and Artificial Intelligence, SUTD.

I build at the intersection of **software engineering, AI, and interaction design**: local AI tools, machine learning services, and multiplayer worlds. I like turning complicated systems into something people can actually use—or play.

[Explore my repositories](https://github.com/NicolasLasch?tab=repositories) · [Find me on X](https://x.com/__Spat__)

## Selected work

<table>
<tr>
<td width="50%" valign="top">

### 01 / Tidy

<a href="https://github.com/NicolasLasch/Tidy">
  <picture>
    <source media="(prefers-reduced-motion: reduce)" srcset="./assets/tidy-static.png">
    <img src="./assets/tidy-demo.gif" alt="Tidy in action: a real demo of its local file assistant and reviewable plans. Click to explore the project." width="100%">
  </picture>
</a>

**A local AI assistant for your Mac's files.**

Ask in plain English, review the exact plan, and undo changes. A Rust safety engine handles execution; the optional local model helps interpret requests.

`Rust` `Tauri` `TypeScript` `llama.cpp`

[Explore the project →](https://github.com/NicolasLasch/Tidy) · [Download](https://github.com/NicolasLasch/Tidy/releases/latest)

</td>
<td width="50%" valign="top">

### 02 / Bergen Bike Analysis

<a href="https://yfpzcgnbsf.ap-southeast-1.awsapprunner.com/">
  <img src="./assets/bergen-dashboard.jpg" alt="A screenshot of the prediction timeline on the live Bergen Bike Intelligence web dashboard. Click to open the app." width="100%">
</a>

**Bike-demand forecasting, beyond the notebook.**

Historical usage, time, and weather feed a prediction pipeline. A Flask API, Docker container, and AWS deployment workflow connect the model to a usable service.

`Python` `Machine learning` `Flask` `AWS`

[Try the web app →](https://yfpzcgnbsf.ap-southeast-1.awsapprunner.com/) · [Source](https://github.com/NicolasLasch/Bergen_Bike_Analysis)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 03 / Hospital DTwin

<a href="https://github.com/NicolasLasch/Hospital-DTwin">
  <img src="./assets/hospital-architecture.svg" alt="Hospital DTwin architecture illustration: an eight-bed 3D ward linked to interactive patient dashboards. This is a source-based schematic, not an app screenshot." width="100%">
</a>

**A hospital ward you can explore in 3D.**

An educational digital twin with bed inspection, telemetry streams, and patient dashboards. Three.js connects spatial interaction with demonstration patient data.

`JavaScript` `Three.js` `Socket.IO`

[Explore the project →](https://github.com/NicolasLasch/Hospital-DTwin)

</td>
<td width="50%" valign="top">

### 04 / Generative Audio

<a href="https://github.com/NicolasLasch/GenAI---Music-in-video">
  <img src="./assets/audio-pipeline.svg" alt="Generative Audio pipeline: video perception, LLM audio planning, AudioLDM2 generation, and CLAP scoring. Click to explore the code." width="100%">
</a>

**From silent video to generated sound.**

An experimental pipeline combines visual scene analysis, LLM audio planning, AudioLDM2 generation, and CLAP scoring to create sound effects for video.

`Python` `Vision-language models` `AudioLDM2`

[Explore the project →](https://github.com/NicolasLasch/GenAI---Music-in-video)

</td>
</tr>
</table>

## Also in the workshop

| Project | What I built |
| :--- | :--- |
| [Character Clips](https://github.com/NicolasLasch/Character-Clips) | YouTube clipping around recognized faces, using YOLOv8 and face recognition. |
| [Karmine SMP](https://github.com/NicolasLasch/Karmine-SMP-Mod) | A Forge multiplayer world with custom dimensions, portals, guild cards, and rank-based access. |
| [Farkle Dice](https://github.com/NicolasLasch/Farkle-Dice-1.21.11) | A Fabric dice game with villager opponents, betting, and player challenges. |
| [FoliaMarket](https://github.com/NicolasLasch/FoliaMarket) / [UserShops](https://github.com/NicolasLasch/UserShops) | Java plugins for server markets and player trading. |
| [NGNLUHC](https://github.com/NicolasLasch/NGNLUHC) | A No Game No Life UHC mode with custom multiplayer systems; still in development. |
| [Odoo Hackathon 4.2](https://github.com/Odoo-Hackathons-Macos-Linux/hackathon-4.2) | Collaborative development with the Macos-Linux team. |

## My toolkit

**Languages** · Java, Python, Rust, TypeScript, C#<br>
**Across projects** · Local inference, computer vision, model serving, desktop apps, game systems.

<details>
<summary><b>Open the terminal</b></summary>

```java
package com.github.nicolaslasch;

// A small profile, in Java.
public record Profile(String name, String[] interests) {
    public static void main(String[] args) {
        var nicolas = new Profile("Nicolas Lasch", new String[] {
            "Useful tools", "Learning systems", "Unexpected worlds"
        });
        System.out.println("Ready to build: " + nicolas.name());
    }
}
```

```text
nicolas@workshop:~$ java Profile.java
Ready to build: Nicolas Lasch
nicolas@workshop:~$ _
```

</details>

---

<sub>Curious about how something works? Open a repository. The interesting part is inside.</sub>
