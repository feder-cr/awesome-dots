# Awesome Dots

> The open-source side of dots: agents you can run yourself, and the pieces every
> dot is made of. A model, a browser, a memory, tools, and a way to reach you.

OpenAI launched [dots](https://openai.com/index/introducing-dots/) on September 29,
2026: always-on agents in ChatGPT, each with its own cloud computer and browser.
This list is about building and running the same idea on your own machine.

_Unofficial. Not affiliated with or endorsed by OpenAI._

## Contents

- [What a dot is made of](#what-a-dot-is-made-of)
- [Open-source dots](#open-source-dots)
- [Always-on personal agents](#always-on-personal-agents)
- [The browser](#the-browser)
- [Memory](#memory)
- [Tools, skills and plugins](#tools-skills-and-plugins)
- [Official](#official)
- [News](#news)
- [Related lists](#related-lists)

## What a dot is made of

- **A model** that decides what to do next.
- **A browser**, because most of the work lives on websites. It is also the part
  that fails most often: OpenAI's own guide says a dot uses your local browser
  [when its cloud browser is blocked](https://help.openai.com/en/articles/20001530-getting-started-with-your-dot).
- **A memory**, so the agent knows what it already did and what you prefer.
- **Tools**, usually over MCP, for everything that has an API.
- **A channel** to reach you: chat, Slack, Telegram, voice.
- **A clock**, so it keeps working when you are not looking.

## Open-source dots

- [open-dots](https://github.com/Anil-matcha/open-dots) - Self-hosted chat with tools, approvals, connectors and computer tasks. Next.js and FastAPI.
- [opendots](https://github.com/diggerhq/opendots) - An always-on personal agent on the model you choose, built on serverless agents.
- [open-dot](https://github.com/composio-community/open-dot) - Personal agents that each get their own browser, memory and rules, with scheduled routines.
- [opendot](https://github.com/defog-ai/opendot) - Runs Codex or Claude Code in a locked-down container and asks before it acts. Slack and CLI.
- [dots](https://github.com/dots-oai/dots) - A goal-driven agent runtime: a planner, an executor and a watcher that keep going between conversations.
- [AgentForEach](https://github.com/AgentForEach/AgentForEach) - A serverless backend for running one agent per user.

## Always-on personal agents

The projects that made the idea popular before dots had a name.

- [OpenClaw](https://github.com/openclaw/openclaw) - A gateway that stays on, with channels, skills and a heartbeat that lets the agent start work on its own.
- [nanobot](https://github.com/HKUDS/nanobot) - A small Python take on the same idea, with memory, MCP, cron and chat channels.

## The browser

Everything a dot does on the web goes through one. What the site sees is the
browser, not the model.

- [dots](https://github.com/feder-cr/dots) - A web agent with a chat on one side and its live browser on the other, driven by any OpenRouter model, on a patched Firefox engine.
- [invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) - The same browser as an MCP server, for Claude Code, Codex, Gemini CLI and other clients.
- [browser-use](https://github.com/browser-use/browser-use) - A Python library for agents that use the browser.
- [Playwright MCP](https://github.com/microsoft/playwright-mcp) - Playwright as an MCP server.
- [Chrome DevTools MCP](https://github.com/ChromeDevTools/chrome-devtools-mcp) - Chrome DevTools for coding agents.

## Memory

- [mem0](https://github.com/mem0ai/mem0) - A memory layer for agents: what the user said, preferred and asked for, across sessions.

## Tools, skills and plugins

- [AutoBot](https://github.com/demeyer1/Autobot) - A local ChatGPT and Codex project harness with on-disk memory, privacy zones and verifier-backed completion.
- [Secure MCP Tunnel client](https://github.com/openai/tunnel-client) - Connects an MCP server on your own machine to ChatGPT without exposing it to the internet.
- [ChatGPT developer mode](https://developers.openai.com/api/docs/guides/developer-mode) - How to add your own MCP server as a plugin.
- [Computer use](https://developers.openai.com/api/docs/guides/tools-computer-use) - The API tool where you run the computer and the model decides the clicks.
- [openai/skills](https://github.com/openai/skills) - Skills catalog: folders with a `SKILL.md` that teach an agent one job.

## Official

- [Introducing dots](https://openai.com/index/introducing-dots/) - The launch post.
- [Getting started with your dot](https://help.openai.com/en/articles/20001530-getting-started-with-your-dot) - Setup, local computer access, approvals.
- [DevDay 2026 recap](https://openai.com/index/devday-2026-recap/) - Everything announced alongside dots.

## News

- [OpenAI launches Dots](https://techcrunch.com/2026/09/29/openai-launches-dots-its-bubbly-agentic-avatar/) - TechCrunch.
- [Always-on AI agents with their own cloud computers](https://thenextweb.com/news/openai-dots-always-on-ai-agents-cloud-computers-devday) - The Next Web.
- [OpenAI DevDay 2026 live blog](https://simonwillison.net/2026/Sep/29/openai-devday-2026-live-blog/) - Simon Willison.

## Related lists

- [mergisi/awesome-dots](https://github.com/mergisi/awesome-dots) - Guides, pricing, plugins and use cases for OpenAI's dots.
- [awesome-openclaw](https://github.com/vincentkoc/awesome-openclaw) - Skills, plugins and guides for OpenClaw.

## Contributing

Open a pull request with one line in the right section: the name, the link, and
what it does in one sentence. See [CONTRIBUTING.md](CONTRIBUTING.md).
