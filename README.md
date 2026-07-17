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
    <em>A starting point for interactive batch scripts on Windows.</em>
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

A starter `.bat` for interactive command-line tools on Windows — admin tasks, automation, quick maintenance jobs. It comes with a menu loop, input prompts with validation, an admin-rights check, and a few working example commands, so you don't rewrite the same boilerplate every time.

> ⚙️ Built for my own use and shared as-is. Pure batch, no dependencies.

<p align="right">(<a href="#top">🔼 Back to top</a>)</p>

## ✨ Features

- Interactive, colorized menu loop
- Input prompts that re-ask on empty input
- Administrator-rights check at startup
- Example commands: ping, DNS flush, date/time, network-drive mapping
- Pure batch — single file, no dependencies

<p align="right">(<a href="#top">🔼 Back to top</a>)</p>

## 🚀 Installation

### Prerequisites

- Windows (tested on 10 and 11)
- Command Prompt (`cmd.exe`)

No external software or dependencies — it's pure batch.

### Download

From `cmd.exe`:
```bash
curl.exe -sO https://raw.githubusercontent.com/franckferman/Interactive-Batch-Script-Template/refs/heads/main/InteractiveBatchScriptTemplate.bat
```

<p align="right">(<a href="#top">🔼 Back to top</a>)</p>

## 🎮 Usage

1. Open `cmd.exe` in the folder where you downloaded the script.
2. Run it (it asks for administrator rights):
```bash
InteractiveBatchScriptTemplate.bat
```
3. Pick an option from the menu.

### Customization

Each menu action is a self-contained label (`:pingUtility`, `:flushDNS`, …) that jumps back to `:main`. Copy one, rename it, add it to the menu and the `:inputChoice` dispatcher.

<p align="right">(<a href="#top">🔼 Back to top</a>)</p>

## 📜 License

GNU Affero General Public License v3.0. See the [LICENSE](https://github.com/franckferman/Interactive-Batch-Script-Template/blob/main/LICENSE) file.

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
