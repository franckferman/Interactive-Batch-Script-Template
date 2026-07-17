<div id="top" align="center">

<!-- Shields Header -->
[![Contributors][contributors-shield]](https://github.com/franckferman/Interactive-Batch-Script-Template/graphs/contributors)
[![Stargazers][stars-shield]](https://github.com/franckferman/Interactive-Batch-Script-Template/stargazers)
[![License][license-shield]](https://github.com/franckferman/Interactive-Batch-Script-Template/blob/main/LICENSE)

<!-- Logo -->
<a href="https://github.com/franckferman/Interactive-Batch-Script-Template">
  <img src="https://raw.githubusercontent.com/franckferman/Interactive-Batch-Script-Template/refs/heads/main/docs/github/graphical_resources/Logo-without_background-Interactive-Batch-Script-Template.png" alt="Interactive-Batch-Script-Template Logo" width="auto" height="auto">
</a>

<!-- Title & Tagline -->
<h3 align="center">⚙️ Interactive-Batch-Script-Template</h3>
<p align="center">
    <em>A ready-to-use template for building interactive batch scripts on Windows.</em>
    <br>
    A clean, modular foundation for dynamic CLI tools — system administration, automation, and maintenance.
</p>

</div>

## 📜 Table of Contents

<details open>
  <summary><strong>Click to collapse/expand</strong></summary>
  <ol>
    <li><a href="#-about">📖 About</a></li>
    <li><a href="#-features">✨ Features</a></li>
    <li><a href="#-installation">🚀 Installation</a></li>
    <li><a href="#-usage">🎮 Usage</a></li>
    <li><a href="#-license">📜 License</a></li>
    <li><a href="#-contact">📞 Contact</a></li>
  </ol>
</details>

## 📖 About

**Interactive-Batch-Script-Template** is a **lightweight, modular foundation** for building **interactive batch scripts** for **Windows system automation, administration, and maintenance**.

Instead of starting from a blank `.bat` every time, you get a clean skeleton — a menu loop, input handling, and working example commands — so you can drop in your own logic and ship in minutes.

> ⚙️ **Note**: Originally built for personal and professional use, and shared publicly to save you time. It's **simple, efficient, and dependency-free** — a solid starting point without reinventing the wheel.

<p align="right">(<a href="#top">🔼 Back to top</a>)</p>

## ✨ Features

- 🧩 **Menu-driven loop** — a clean, colorized interactive menu, ready to extend.
- ✅ **Input validation** — prompts re-ask until a value is entered; no silent empty inputs.
- 🔐 **Admin-rights check** — refuses to run without elevation, so privileged commands don't half-fail.
- 🧰 **Working examples** — ping, DNS flush, date/time, and network-drive mapping to copy from.
- 🪶 **Pure batch** — no dependencies, no runtime, no install. One file.

<p align="right">(<a href="#top">🔼 Back to top</a>)</p>

## 🚀 Installation

### Prerequisites

- **Windows** (tested on **10 & 11**; older versions may work but aren't officially supported).
- **Command Prompt** (`cmd.exe`).

> ⚠️ Pure batch — **no external software or dependencies required.**

### Getting the Template

Open `cmd.exe` and download the script in one command:

```bash
curl.exe -sO https://raw.githubusercontent.com/franckferman/Interactive-Batch-Script-Template/refs/heads/main/InteractiveBatchScriptTemplate.bat
```

<p align="right">(<a href="#top">🔼 Back to top</a>)</p>

## 🎮 Usage

### Quick Start

1. Open **Command Prompt** in the folder where you downloaded the script.
2. Run it (it will request administrator rights):
```bash
InteractiveBatchScriptTemplate.bat
```
3. Follow the interactive menu and make your selection.

### Customization

Edit the `.bat` to add your own menu entries and functions. Each option is a self-contained label (`:pingUtility`, `:flushDNS`, …) that returns to `:main` — copy one, rename it, wire it into the menu, and you're done. The built-in examples already demonstrate prompts, input validation, and colored output.

<p align="right">(<a href="#top">🔼 Back to top</a>)</p>

## 📜 License

This project is licensed under the **GNU Affero General Public License v3.0**. See the [LICENSE](https://github.com/franckferman/Interactive-Batch-Script-Template/blob/main/LICENSE) file for details.

<p align="right">(<a href="#top">🔼 Back to top</a>)</p>

## 📞 Contact

[![ProtonMail][protonmail-shield]](mailto:contact@franckferman.fr)
[![LinkedIn][linkedin-shield]](https://www.linkedin.com/in/franckferman)
[![Twitter][twitter-shield]](https://www.twitter.com/franckferman)

<p align="right">(<a href="#top">🔼 Back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/franckferman/Interactive-Batch-Script-Template.svg?style=for-the-badge
[stars-shield]: https://img.shields.io/github/stars/franckferman/Interactive-Batch-Script-Template.svg?style=for-the-badge
[license-shield]: https://img.shields.io/github/license/franckferman/Interactive-Batch-Script-Template.svg?style=for-the-badge
[protonmail-shield]: https://img.shields.io/badge/ProtonMail-8B89CC?style=for-the-badge&logo=protonmail&logoColor=blueviolet
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=blue
[twitter-shield]: https://img.shields.io/badge/-Twitter-black.svg?style=for-the-badge&logo=twitter&colorB=blue
