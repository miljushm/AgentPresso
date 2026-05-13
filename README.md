# AgentPresso

**AI-native WordPress agent for macOS.** Chat with an autonomous agent that manages your WordPress sites — deploys plugins, fixes security holes, optimizes SEO, writes content, and runs WP-CLI commands. All from a single native macOS app.

---

## Features

### Autonomous Skills (11 built-in)

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
- Internet connection (AI model access required)

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

| Provider | Models |
|---|---|
| **DeepSeek** | deepseek-v4-pro, deepseek-v4-flash, deepseek-chat, deepseek-reasoner |
| **OpenAI** | gpt-5.4, gpt-5.4-mini, gpt-5-mini, gpt-5.3-codex, gpt-4.1, gpt-4o, gpt-4o-mini |
| **Anthropic** | claude-opus-4-7, claude-opus-4-6, claude-sonnet-4-6, claude-haiku-4-5-20251001 |
| **Google AI Studio** | gemini-3.1-pro-preview, gemini-3-pro-preview, gemini-3-flash-preview, gemini-3.1-flash-lite-preview |
| **xAI** | grok-4, grok-4-fast, grok-3, grok-3-fast, grok-3-mini, grok-3-mini-fast, grok-code-fast-1 |
| **OpenRouter** | auto, openai/gpt-5.4, anthropic/claude-sonnet-4-6, google/gemini-3-pro-preview (any OpenRouter model by ID) |
| **Z.AI / GLM** | glm-5.1, glm-5-turbo, glm-5, glm-4.7, glm-4.7-flash, glm-4.7-flashx, glm-4.6, glm-4.5, glm-4.5-air, glm-4.5-x, glm-4.5-airx, glm-4.5-flash, glm-4-32b-0414-128k |
| **MiniMax** | MiniMax-M2.7, MiniMax-M2.7-highspeed, MiniMax-M2.5, MiniMax-M2.5-highspeed, M2-her |

### Local / Self-Hosted

| Provider | Configuration |
|---|---|
| **LM Studio** | Local inference server. Default URL: `http://localhost:1234/v1`. API key optional. |
| **Custom (OpenAI-compatible)** | Any provider with an OpenAI-compatible endpoint — works with Ollama, vLLM, Groq, Together AI, Fireworks, Mistral, Perplexity, Cohere, HuggingFace, NVIDIA, AWS Bedrock, Azure AI Foundry, and more. Enter a custom base URL and model name. |

### Per-Provider Settings

Each provider remembers its own:
- **API key** — saved securely in the system keychain
- **Model selection** — pick the specific model variant
- **Custom base URL** — for self-hosted or alternative endpoints
- **Reasoning effort** — toggle thinking/reasoning (Low, Medium, High, Max)
- **API mode** — Auto, Chat Completions, Responses API, or Anthropic Messages (for multi-mode endpoints)

---

## Credits

AgentPresso is powered by [Hermes Agent](https://hermes-agent.nousresearch.com/) — an open-source, model-agnostic AI agent framework.
