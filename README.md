<p align="center">
  <img src="logo.png" alt="AgentPresso" width="256">
</p>

# AgentPresso

**[AI-native operations agent for macOS](https://agentpresso.com/).** One autonomous agent that handles your full server and WordPress stack — deploys plugins, hardens security, manages system configs, runs WP-CLI and SSH commands, audits servers, optimizes SEO, and writes content. From system administration to site management, all from a single native app.

---

## Features

### Autonomous Skills (21 built-in)

| Skill | What it does |
|---|---|
| **WP-CLI** | Run any WP-CLI command — plugin activate, user create, db export, search-replace, core update |
| **Admin Browser** | Log in to wp-admin and navigate the WordPress admin UI — pages, posts, settings, plugins |
| **Security** | Audit WordPress sites for vulnerabilities, check file permissions, scan for malware, harden configs |
| **SEO** | Optimize meta titles, descriptions, Yoast readability, XML sitemaps, redirects, structured data |
| **Theme Development** | Create, customize, and deploy WordPress themes — from child themes to full custom builds |
| **Plugin Management** | Install, update, activate, deactivate, and troubleshoot WordPress plugins |
| **Database** | Query, optimize, clean revisions, expire transients, repair tables, export/import |
| **Content Creation** | Write, edit, and publish WordPress posts and pages via Gutenberg blocks |
| **Gutenberg Blocks** | Build custom Gutenberg blocks — attributes, inspectors, dynamic rendering, ACF blocks |
| **REST API** | Interact with the WordPress REST API — CRUD posts, users, media, custom endpoints |
| **WooCommerce** | Manage products, orders, coupons, customers, and WooCommerce settings |
| **→ [See all 21 skills on agentpresso.com](https://agentpresso.com/skills/)** |

### Multi-Site Management

Manage multiple WordPress sites from one app. Switch between them instantly. Each site gets its own chat session with full context.

### Sparkle Auto-Updates

Automatic updates delivered via Sparkle — you always get the latest version.

---

## Download

[**Download latest DMG**](https://github.com/miljushm/AgentPresso/releases/latest/download/AgentPresso.dmg)

All releases: [github.com/miljushm/AgentPresso/releases](https://github.com/miljushm/AgentPresso/releases)

### System Requirements

- **macOS 14.0 (Sonoma)** or later
- **Apple Silicon** or **Intel Mac**
- 4 GB RAM minimum (8 GB recommended)
- Internet connection required for cloud AI models (local models supported via LM Studio or custom endpoint)

---

## Screenshots

*Screenshots coming soon.*

<!-- Placeholder for screenshots:
![Chat Interface](assets/screenshot-chat.png)
![Settings](assets/screenshot-settings.png)
![Skills](assets/screenshot-skills.png)
-->

---

## Quick Start

1. [Download the DMG](https://github.com/miljushm/AgentPresso/releases/latest/download/AgentPresso.dmg)
2. Drag AgentPresso to your Applications folder
3. Open AgentPresso
4. Go to **Settings → Model** and enter your API key
5. Add a WordPress site and start chatting

---

## Supported AI Providers

AgentPresso supports the following AI model providers, configurable in **Settings → Model**.

### Cloud Providers

- ChatGPT / Codex
- DeepSeek
- OpenAI
- Anthropic
- Google AI Studio
- xAI
- OpenRouter
- Z.AI / GLM
- MiniMax

### Local / Self-Hosted

- LM Studio
- Custom (OpenAI-compatible)

### Per-Provider Settings

Each provider remembers its own:
- **API key** — saved securely in the system keychain
- **Model selection** — pick the specific model variant
- **Custom base URL** — for self-hosted or alternative endpoints
- **Reasoning effort** — toggle thinking/reasoning (Low, Medium, High, Max)
- **API mode** — Auto, Chat Completions, Responses API, or Anthropic Messages (for multi-mode endpoints)

---

## Credits

Built on top of Hermes Agent by Nous Research
