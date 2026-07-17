# Interactive-Batch-Script-Template

A menu-driven `.bat` skeleton for Windows — bring your own commands.

## About

A starter `.bat` for interactive command-line tools on Windows: menu loop, input prompts with validation, an admin-rights check, and a few example commands to copy from — so you skip the boilerplate.

## What's included

- Colorized menu loop
- Input prompts that re-ask on empty input
- Admin-rights check at startup
- Example commands: ping, DNS flush, date/time, network-drive mapping

## Download

From `cmd.exe`:

```bash
curl.exe -sO https://raw.githubusercontent.com/franckferman/Interactive-Batch-Script-Template/refs/heads/main/InteractiveBatchScriptTemplate.bat
```

## Usage

Run it (it asks for admin rights) and pick a menu option:

```bash
InteractiveBatchScriptTemplate.bat
```

Each action is a label (`:pingUtility`, `:flushDNS`, …) that returns to `:main`. Copy one, rename it, add it to the menu and the `:inputChoice` dispatcher.

## License

[AGPL-3.0](LICENSE)

## Contact

[ProtonMail](mailto:contact@franckferman.fr) · [LinkedIn](https://www.linkedin.com/in/franckferman) · [Twitter](https://www.twitter.com/franckferman)
