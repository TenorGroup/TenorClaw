# TenorClaw

> Forked from [ClawX](https://github.com/ValueCell-ai/ClawX) by ValueCell Team.
> TenorClaw is a customized build by Tenor Group for internal deployment.

<p align="center">
  <img src="src/assets/logo.svg" width="128" height="128" alt="TenorClaw Logo" />
</p>

<h1 align="center">TenorClaw</h1>

<p align="center">
  <strong>Graphical AI Assistant by Tenor Group — powered by OpenClaw</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-MacOS%20%7C%20Windows%20%7C%20Linux-gray" alt="Platform" />
  <img src="https://img.shields.io/badge/electron-40+-47848F?logo=electron" alt="Electron" />
  <img src="https://img.shields.io/badge/react-19-61DAFB?logo=react" alt="React" />
  <img src="https://img.shields.io/badge/license-MIT-green" alt="License" />
</p>

---

## About

TenorClaw is a desktop AI assistant interface built on [OpenClaw](https://github.com/nicepkg/openclaw). It provides a graphical UI for managing AI agents, messaging channels (Zalo, Telegram, WhatsApp, Discord), scheduled tasks, and skills — without touching the terminal.

This fork is maintained by **Tenor Group** and includes:
- Monochrome/grayscale Tenor visual identity
- Montserrat font throughout
- Vietnamese language support
- Custom branding and deployment configuration

## Getting Started

```bash
# Install dependencies
pnpm install

# Development mode
pnpm dev

# Build for production
pnpm build
```

## Tech Stack

- **Electron 40+** — Desktop runtime
- **React 19** — UI framework
- **TypeScript** — Type safety
- **Tailwind CSS + shadcn/ui** — Styling
- **Zustand** — State management
- **i18next** — Internationalization (EN, ZH, JA, VI)

## Attribution

TenorClaw is a fork of [ClawX](https://github.com/ValueCell-ai/ClawX) by the ValueCell Team, licensed under the MIT License. See [LICENSE](LICENSE) and [NOTICE.md](NOTICE.md) for full attribution details.

## License

MIT — See [LICENSE](LICENSE) for details.
