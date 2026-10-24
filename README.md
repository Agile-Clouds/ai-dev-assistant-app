# AI Dev Assistant

**From roadmap to reviewed code.**

AI Dev Assistant develops your projects, with or without GitHub, continuously with the AI subscriptions you already have: **Claude** and **Codex**. A program called the assistant runs on your own computer.

It turns your project's plan into tasks. Claude or Codex builds each one on your computer or in its cloud, your project's own checks run, the other AI reviews it when both can work, and only that reviewed commit reaches main. You manage, approve and answer from its dashboard, on your PC; online from any browser, by invitation.

It is for a person who wants a project to move forward every day, while keeping each change checked and reviewed.

![AI Dev Assistant: a project's tasks moving from plan to reviewed code](images/hero-light.jpg)

![The dashboard: what needs you, what runs, what is next](images/dashboard-light.jpg)

## What you need

- A Claude or ChatGPT plan, the one you already pay for. One is enough. You can use both.
- A Windows, macOS or Linux computer.
- A GitHub account only for projects kept on GitHub. A project can also live in a folder on your PC without GitHub.

## Install

No account and no administrator rights are needed for the first install.

**Windows, in PowerShell**

```powershell
irm https://ai-dev-assistant.agile-clouds.com/install.ps1 | iex
```

**Mac or Linux**

```sh
curl -fsSL https://ai-dev-assistant.agile-clouds.com/install.sh | sh
```

Setup opens in your browser. Choose Claude, Codex or both, sign in, then add a project. Nothing starts with your computer: you start it.

You can read the install scripts before you run them: [Windows](https://ai-dev-assistant.agile-clouds.com/install.ps1) or [Mac and Linux](https://ai-dev-assistant.agile-clouds.com/install.sh).

## What stays on your PC

A new install keeps its dashboard and its data on your PC, with no account. Your tasks, proof, rules and publish history stay there. Your AI and GitHub sign-ins stay on your PC and are never seen by the website.

Going online is a later choice. When you move the dashboard online, your PC locks project details with your account's key before they leave it. Read [Privacy and terms](https://ai-dev-assistant.agile-clouds.com/privacy) for what the dashboard receives and keeps, and the terms that apply.

## Updates and the release key

Your PC checks the public version file when its dashboard opens and once a day. When a newer version is ready, **Update now** shows what changes. Your PC checks the signature, size and checksum before it installs the update. A failed update changes nothing.

Release key fingerprint: `e6f8-ac27-4363-57ca`

The install checks the assistant's release with this key before unpacking it; your PC checks every update against it before downloading. The install line itself is not signed: the first install trusts the dashboard that serves it.

## Stop or uninstall

To stop it, open **Your PC** and press **Stop the assistant**. On Windows, you can also use **Stop the assistant** from its icon by the clock. Closing the browser does not stop it. Each task keeps its saved work and continues from there when you start again.

To remove it, stop it first, then use:

- Windows: **Uninstall AI Dev Assistant** in the Start menu.
- Mac: `~/Library/Application\ Support/AI\ Dev\ Assistant/uninstall`
- Linux: `~/.local/share/ai-dev-assistant/uninstall`

Uninstall keeps your projects folder, sign-ins, Claude Code and GitHub work. It keeps a checked local backup of the assistant's projects, tasks and choices so that **Welcome back** can offer them after another install.

## Feedback and security

Already using AI Dev Assistant? Open **Feedback** in your dashboard. For a question before you start, use [Contact us](https://ai-dev-assistant.agile-clouds.com/#contact) or email [contact@agile-clouds.com](mailto:contact@agile-clouds.com).

For a security problem, follow [SECURITY.md](SECURITY.md). Do not put keys, tokens, passwords or `.env` contents in an issue.

## Licence

AI Dev Assistant is free to download and use under the terms in [LICENSE](LICENSE).
