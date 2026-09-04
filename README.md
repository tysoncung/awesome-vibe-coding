# Awesome Vibe Coding [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI-powered coding assistants, tools, and resources for enhancing the modern developer experience

🔥 **246+ AI coding tools** | 🆓 **Free alternatives included** | 📊 **Cost comparisons** | 🚀 **Updated weekly**

⭐ **Star this repo** to keep up with the AI coding revolution!

The future of coding is here - AI assistants that understand context, generate code, debug issues, and pair program with you. This list covers the best tools, platforms, and resources for AI-assisted development.

## Contents

- [AI Coding Assistants](#ai-coding-assistants)
  - [Full IDE Integrations](#full-ide-integrations)
  - [CLI Tools](#cli-tools)
  - [Browser Extensions](#browser-extensions)
  - [Specialized Tools](#specialized-tools)
- [AI Agents & Autonomous Coding](#ai-agents--autonomous-coding)
- [Browser Automation & UI Agents](#browser-automation--ui-agents)
- [AI Code Review & Analysis](#ai-code-review--analysis)
- [AI Debugging & Error Fixing](#ai-debugging--error-fixing)
- [AI Documentation & Comments](#ai-documentation--comments)
- [AI Testing](#ai-testing)
- [AI Refactoring](#ai-refactoring)
- [Voice-Powered Coding](#voice-powered-coding)
- [Pair Programming with AI](#pair-programming-with-ai)
- [Infrastructure & DevOps AI](#infrastructure--devops-ai)
- [Database & SQL AI Tools](#database--sql-ai-tools)
- [Learning & Education](#learning--education)
- [Productivity Tools](#productivity-tools)
- [Open Source Projects](#open-source-projects)
- [Benchmarks & Evaluation](#benchmarks--evaluation)
- [Cost Comparison](#cost-comparison)
- [Best Practices & Guides](#best-practices--guides)
- [AI Code Search & Discovery](#ai-code-search--discovery)
- [AI-Powered IDE Extensions](#ai-powered-ide-extensions)
- [Learning Paths & Tutorials](#learning-paths--tutorials)
- [Success Stories & Case Studies](#success-stories--case-studies)
- [Model Providers & APIs](#model-providers--apis)
- [Enterprise & Team Tools](#enterprise--team-tools)
- [Code Quality & Refactoring](#code-quality--refactoring)
- [Security & Privacy](#security--privacy)
- [Workflow Integration](#workflow-integration)
- [Community & Resources](#community--resources)

## AI Coding Assistants

### Full IDE Integrations

**Premium/Commercial:**

- [Cursor](https://cursor.com/) - AI-first code editor built on VSCode with agent, chat, and Tab completion.
  - Agent mode with Cursor's own Composer models plus Claude, GPT, and Gemini
  - Tab completion powered by Cursor's in-house models
  - Background agents, Bugbot PR review, and a CLI
  - Free Hobby plan; Pro $20/mo, with Pro+ and Ultra tiers

- [GitHub Copilot](https://github.com/features/copilot) - AI pair programmer from GitHub.
  - Inline completions, chat, and agent mode in VSCode, JetBrains, Neovim, and Xcode
  - Multiple models (Claude, GPT-5.x, Gemini) with context windows up to 1M tokens
  - Cloud coding agent that takes issues and opens pull requests
  - Free plan (2,000 completions and 50 chat requests per month); Pro $10/mo

- [Claude Code](https://claude.com/product/claude-code) - Anthropic's agentic coding tool.
  - Terminal agent with VSCode and JetBrains extensions, a desktop app, and a web version
  - Subagents, hooks, skills, and MCP support
  - Powered by Claude Fable 5.1, Opus 5, and Sonnet 5
  - Included with Claude Pro ($20/mo) and Max plans, or pay per API token

- [Tabnine](https://www.tabnine.com/) - Enterprise AI coding platform, acquired by Tricentis in July 2026.
  - Team-trained and private models
  - On-prem and air-gapped deployment
  - IDE integrations for VSCode and JetBrains
  - No free or individual plan; enterprise pricing from $39 per user per month

- [Kiro](https://kiro.dev/) - AWS's spec-driven agentic IDE and CLI, successor to Amazon Q Developer and CodeWhisperer.
  - Specs, hooks, and steering files for structured agent work
  - Kiro CLI, web, and mobile apps alongside the IDE
  - Multi-model (Claude and others) with MCP and skills support
  - Free tier; credit-based paid plans

- [Replit Agent](https://replit.com/products/agent) - Replit's autonomous app builder (formerly Ghostwriter).
  - Builds and deploys full apps from a prompt
  - Agent 4 with long-running autonomous tasks
  - Works entirely in the browser
  - Integrated with Replit hosting and databases

- [Sourcegraph Cody](https://sourcegraph.com/cody) - AI coding assistant with codebase awareness.
  - Understands entire codebase
  - Code search integration
  - Multi-repo context
  - Enterprise only since July 2025; individual users are directed to Amp

- [Windsurf (now Devin Desktop)](https://devin.ai/desktop) - Agentic IDE from Cognition, formerly Codeium.
  - Built on VSCode with the Cascade agent
  - Windsurf Plugin (formerly Codeium) for other editors with unlimited free autocomplete
  - Multi-file editing and deep codebase understanding
  - Free plan with a limited agent quota; paid Pro plan

- [JetBrains AI Assistant](https://www.jetbrains.com/ai/) - Built-in AI for IntelliJ IDEA family.
  - Code completion and generation
  - Chat with codebase
  - Junie coding agent for autonomous tasks
  - Works across all JetBrains IDEs
  - Free tier included with JetBrains IDEs; AI Pro from $10/mo

- [Zed](https://zed.dev/) - High-performance collaborative code editor with AI.
  - Written in Rust, open source
  - Built-in agent panel and edit prediction
  - Local models via Ollama or LM Studio, or bring your own API keys
  - Free Personal plan; Pro $10/mo for hosted models

- [Google Antigravity](https://antigravity.google/) - Google's agent-first development platform.
  - IDE, CLI, and SDK with a multi-agent command center
  - Manages multiple local agents, projects, and scheduled tasks
  - Replaces Gemini Code Assist for individual developers
  - Free tier; Google AI Pro and Ultra plans

**Open Source:**

- [Cline](https://github.com/cline/cline) - Autonomous coding agent for VSCode, JetBrains, and the CLI.
  - Plan and Act modes for autonomous workflows
  - Create and edit files, run terminal commands
  - Local models via Ollama or LM Studio, or bring your own keys
  - Apache 2.0, free

- [Kilo Code](https://github.com/Kilo-Org/kilocode) - Open-source coding agent for VSCode, JetBrains, and the CLI.
  - Code, Plan, Ask, Debug, and Review modes
  - 500+ models with mid-task switching, zero markup on provider rates
  - MCP marketplace and autonomous CI mode
  - MIT licensed

- [Continue](https://continue.dev/) - Open-source AI code assistant, acquired by Cursor in June 2026.
  - VSCode and JetBrains
  - Bring your own LLM
  - Apache 2.0 code still available, but the repository is read-only and unmaintained

- [NotFair Plugin (formerly Toprank)](https://github.com/nowork-studio/notfair-plugin) - Open-source SEO, GEO, and marketing skills for AI coding agents.

- [Tabby](https://tabbyml.github.io/tabby/) - Self-hosted AI coding assistant.
  - Open source
  - Self-hosted
  - No telemetry
  - GPU/CPU support

### CLI Tools

- [OpenAI Codex CLI](https://github.com/openai/codex) - OpenAI's open-source terminal coding agent.
  - Sandboxed local execution with approval modes
  - IDE extensions, desktop app, and a cloud version for background tasks
  - Sign in with a ChatGPT plan or use an API key
  - Apache 2.0; included with ChatGPT Plus, Pro, and Business

- [Gemini CLI](https://github.com/google-gemini/gemini-cli) - Google's open-source terminal agent for Gemini models.
  - 1M-token context with built-in Google Search grounding
  - File, shell, and web tools plus MCP support
  - GitHub Actions integration for PR review and issue triage
  - Apache 2.0; free tier with Google sign-in

- [OpenCode](https://github.com/anomalyco/opencode) - Open-source, provider-agnostic terminal coding agent.
  - Build and plan agents with a permissioned read-only plan mode
  - Works with any model provider, including local models
  - Desktop app for macOS, Windows, and Linux
  - MIT licensed, bring your own keys

- [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) - Plugin-based open-source agent harness from DeepSeek.
  - Providers, tools, and context injection are all swappable plugins
  - Trajectory view for auditing every tool call
  - Works with DeepSeek, OpenRouter, and other providers
  - MIT licensed, developer preview

- [GitHub Copilot CLI](https://github.com/github/copilot-cli) - GitHub's terminal agent with native repo, issue, and PR access.
  - Agentic build, edit, and debug with action previews
  - MCP extensibility and LSP support
  - Multiple models including Claude and GPT-5
  - Requires a paid Copilot subscription

- [Pi](https://github.com/badlogic/pi-mono) - Minimal, self-extending TypeScript coding agent and toolkit.
  - Four core tools and a very small system prompt
  - The agent writes its own extensions
  - Reusable packages for LLM access, agent core, and TUI
  - MIT licensed

- [Crush](https://github.com/charmbracelet/crush) - Charm's terminal coding agent, successor to mods.
  - Switch models mid-session
  - LSP and MCP integration
  - Local models via Ollama, llama.cpp, or LM Studio
  - FSL-1.1-MIT licensed

- [Qwen Code](https://github.com/QwenLM/qwen-code) - Alibaba's open-source terminal agent for Qwen and compatible models.
  - Subagents, agent teams, and MCP support
  - VSCode, Zed, and JetBrains plugins plus a desktop app
  - Apache 2.0

- [Grok Build](https://github.com/xai-org/grok-build) - xAI's open-source Rust terminal coding agent.
  - Full-screen TUI, headless CI mode, and editor embedding
  - Up to eight subagents in isolated worktrees
  - Apache 2.0; requires a SuperGrok or X Premium+ subscription

- [Muse Code](https://developer.meta.com/ai/products/muse-code/) - Meta's terminal coding agent powered by Muse Spark models.
  - Lead session spawns child agents in per-child Git worktrees
  - Voice mode, computer use, and a GitHub bot
  - Open-source CLI client with hosted inference; subscriptions from $5/mo

- [Mistral Vibe](https://github.com/mistralai/mistral-vibe) - Mistral's open-source coding agent CLI built around Devstral 2.
  - Works with Mistral API models
  - Apache 2.0

- [Kimi Code CLI](https://github.com/MoonshotAI/kimi-code) - Moonshot AI's TypeScript terminal coding agent for Kimi models.
  - MIT licensed

- [Warp](https://www.warp.dev/) - AI-powered terminal with a built-in coding agent.
  - Natural language to commands and agent mode
  - Source-available; free plan with limited credits
  - Build $20/mo, Max $200/mo

- [codex-profiles](https://github.com/Ducksss/codex-profiles) - Manage named Codex CLI profiles with separate local `CODEX_HOME` state.
  - Run Codex CLI and one-shot commands in a selected profile
  - Supports per-profile login, status, and diagnostics
  - Can launch matching isolated ChatGPT Desktop windows on macOS

- [vnsh](https://github.com/raullenchai/vnsh) - Ephemeral encrypted file sharing for AI.
  - Pipe logs, diffs, files to secure URLs
  - Client-side AES-256 encryption
  - Claude reads vnsh links directly via MCP
  - Auto-vaporizes in 24 hours

- [aider](https://aider.chat/) - AI pair programming in the terminal.
  - Works with Claude, GPT-5, Gemini, DeepSeek, and local models
  - Git integration
  - Multi-file editing
  - Undo/redo support

- [cursor-bridge](https://github.com/hkc5/cursor-bridge) - Claude Code that runs on your Cursor subscription. One Rust binary, zero config.

- [ChatGPT CLI](https://github.com/j178/chatgpt) - ChatGPT in the terminal.
  - Interactive chat
  - Code generation
  - Multiple model support

- [CodeGPT](https://github.com/appleboy/CodeGPT) - CLI for code review and generation.
  - Git commit messages
  - Code review
  - Multiple LLM support

- [AI Shell](https://github.com/BuilderIO/ai-shell) - Natural language to shell commands.
  - Converts English to bash/zsh
  - Safe command preview
  - Uses OpenAI models (configurable)

- [ShellGPT](https://github.com/TheR1D/shell_gpt) - ChatGPT in terminal.
  - Shell commands from natural language
  - Code snippet generation
  - Multiple roles
  - Conversation history

### Browser Extensions

- [Blackbox AI](https://www.blackbox.ai/) - Code autocomplete anywhere.
  - Works in browser
  - Chrome extension
  - Multiple languages
  - Code search

### Specialized Tools

- [v0 by Vercel](https://v0.dev/) - Generate UI from text.
  - React/Next.js components
  - Tailwind CSS
  - Interactive preview
  - Iterative refinement

- [Screenshot to Code](https://screenshottocode.com/) - Convert designs to code.
  - Works with OpenAI, Claude, and Gemini vision models
  - HTML/Tailwind output
  - React/Vue/Svelte support

- [Google Stitch (formerly Galileo AI)](https://stitch.withgoogle.com/) - AI for UI design.
  - Text and image to UI designs
  - Export to Figma or code
  - Free Google Labs product

- [Butterfish](https://butterfi.sh/) - Shell copilot.
  - AI assistance in terminal
  - Context-aware suggestions
  - Git integration
  - Open source

- [GitHub Spec Kit](https://github.com/github/spec-kit) - GitHub's toolkit for spec-driven development.
  - Constitution, specify, plan, tasks, and implement commands
  - Works with 30+ coding agents
  - MIT licensed

- [OpenSpec](https://github.com/Fission-AI/OpenSpec) - Spec-driven development workflow for coding agents.
  - Change proposals and specs kept alongside the code
  - Slash commands for Claude Code, Cursor, Codex, and others
  - MIT licensed

- [BMAD-METHOD](https://github.com/bmad-code-org/BMAD-METHOD) - Multi-agent framework covering the full software lifecycle.
  - Analyst, PM, architect, and developer agent roles
  - Works with major coding agents

- [Superpowers](https://github.com/obra/superpowers) - Skills library and methodology for coding agents.
  - Brainstorm, plan, TDD, and review workflows
  - Works with Claude Code, Cursor, Codex, and Copilot CLI
  - MIT licensed

- [Context7](https://github.com/upstash/context7) - MCP server that injects current, version-specific library docs into agent prompts.
  - Works with 30+ agents
  - Automatic version matching
  - MIT licensed

- [Serena](https://github.com/oraios/serena) - MCP toolkit giving agents symbol-level code retrieval and editing via language servers.
  - 40+ languages
  - Rename, move, and safe-delete refactors with cross-file references
  - MIT licensed

- [Sillage](https://github.com/MarlBurroW/sillage) - Self-hosted, mobile-first web UI that drives the native Claude Code and Codex CLIs on your own machine.
  - Sessions that outlive the client, with full-text search across every conversation
  - IDE panel (file explorer, editor, diffs, terminal) and a board agents read through its own MCP server
  - Installable PWA with push; single Docker container
  - MIT licensed

## AI Agents & Autonomous Coding

Tools that can autonomously build apps, implement features, or complete coding tasks with minimal human intervention.

- [Bolt.new](https://bolt.new/) - StackBlitz's AI app builder.
  - Build full-stack apps from prompts
  - Instant preview and deployment
  - Supports React, Vue, Vite
  - Runs entirely in browser
  - Free tier available

- [Lovable (formerly GPT Engineer App)](https://lovable.dev/) - Full-stack app builder.
  - Natural language to full applications
  - Frontend and backend generation
  - Database setup
  - Deployment automation
  - Iterative refinement

- [Playcode](https://playcode.io/ai-website-builder) - AI website and app builder.
  - Natural language to hosted sites and web apps
  - Visual editing and AI chat iteration
  - One-click publishing
  - Custom domains and Playcode Cloud hosting

- [Devin](https://devin.ai/) - Cognition's autonomous AI software engineer.
  - Completes entire tasks with its own terminal and browser
  - Self-serve since April 2025
  - Also powers Devin Desktop (formerly Windsurf)
  - Pro from $20/mo

- [OpenHands (formerly OpenDevin)](https://github.com/OpenHands/OpenHands) - Open source AI coding agent.
  - Autonomous software development
  - Terminal and browser access
  - Open source alternative to Devin
  - Active community

- [Dyad](https://github.com/dyad-sh/dyad) - Local, open-source app builder, an alternative to Lovable and Bolt.
  - Runs on your machine with your own API keys
  - Free and open source, with an optional Pro tier

- [GitHub Copilot coding agent](https://docs.github.com/en/copilot/concepts/agents/coding-agent/about-coding-agent) - Background agent that turns issues into pull requests.
  - Assign an issue to Copilot and get a PR built on GitHub Actions
  - Teams and Slack integrations
  - Available on all paid Copilot plans

- [Jules](https://jules.google/) - Google's cloud coding agent.
  - Takes a GitHub repo and a prompt, plans, and returns a PR
  - Plan and diff approval before commit
  - Free tier of 15 tasks per day; Pro and Ultra plans

- [Amp](https://ampcode.com/) - Multi-model coding agent, spun out of Sourcegraph.
  - Web, macOS, iOS, and CLI surfaces
  - Shareable threads
  - Successor to Cody for individual developers

- [Factory Droid](https://docs.factory.ai/) - Enterprise agent covering coding, review, QA, and docs.
  - Desktop, CLI, web, and headless modes
  - Connectors, skills, plugins, and hooks
  - Enterprise pricing

- [Goose](https://github.com/aaif-goose/goose) - Open-source AI agent framework, originally from Block.
  - Now governed by the Linux Foundation's Agentic AI Foundation
  - Runs entirely locally
  - Extensible toolkit system
  - Goes beyond coding tasks
  - Apache 2.0

- [PR-Agent](https://github.com/The-PR-Agent/pr-agent) - AI-powered PR analysis, community-maintained since April 2026 (formerly Codium/Qodo).
  - Automated PR reviews
  - Code suggestions
  - PR improvements
  - Apache 2.0

## Browser Automation & UI Agents

AI agents that can interact with websites, automate UI tasks, and perform web-based actions.

- [Stagehand](https://www.stagehand.dev/) - AI browser automation framework.
  - Driver-agnostic (CDP) with SDKs for TypeScript, Python, Go, Java, Ruby, and Rust
  - Atomic primitives (act, extract, observe)
  - Dynamic agent for high-level decisions
  - Integrates OpenAI/Anthropic computer use models
  - Production-ready

- [browser-use](https://github.com/browser-use/browser-use) - Open-source AI web automation.
  - Make websites accessible for AI agents
  - Automate online tasks
  - Python-based
  - Simple API

- [ChatGPT agent](https://help.openai.com/en/articles/11752874-chatgpt-agent) - OpenAI's browser and computer-use agent (formerly Operator).
  - Full browser control via AI
  - Natural language automation
  - Built into ChatGPT

- [Skyvern](https://www.skyvern.com/) - Browser automation API.
  - Computer vision based
  - Works without selectors
  - Resilient to UI changes
  - API-first design

- [Browserbase](https://www.browserbase.com/) - Headless browser infrastructure for AI.
  - Serverless browsers for agents
  - Session management
  - Stealth mode
  - Production-grade reliability

## AI Code Review & Analysis

- [CodeRabbit](https://coderabbit.ai/) - AI code reviews for PRs.
  - Line-by-line feedback
  - Security checks
  - Performance suggestions
  - Learning from team feedback

- [Qodo (formerly CodiumAI)](https://www.qodo.ai/) - Code integrity platform.
  - Test generation
  - Code analysis
  - Bug detection
  - VSCode/JetBrains plugins

- [Snyk Code](https://snyk.io/product/snyk-code/) - Security-focused code analysis.
  - Real-time scanning
  - Fix suggestions
  - AI-powered
  - IDE integration

- [DeepSource](https://deepsource.io/) - Automated code review.
  - 10+ languages
  - Security & style
  - Fix automation
  - CI/CD integration

- [SonarQube for IDE (formerly SonarLint)](https://www.sonarsource.com/products/sonarlint/) - IDE code quality.
  - Real-time feedback
  - Multiple IDEs
  - Free and open source

- [Greptile](https://www.greptile.com/) - AI PR reviewer that indexes the whole codebase.
  - Learns standards from team comments
  - Plain-English custom rules
  - Free tier; Pro $30 per seat per month

- [Cursor Bugbot](https://cursor.com/bugbot) - Cursor's GitHub PR review bot focused on logic bugs.
  - Direct PR comments with fix suggestions
  - Bugbot rules
  - 14-day free trial, then paid

## AI Debugging & Error Fixing

- [Pieces for Developers](https://pieces.app/) - AI coding workflow tool.
  - Save and share snippets
  - Context awareness
  - Search codebase
  - Extract from screenshots

## AI Documentation & Comments

- [Mintlify](https://mintlify.com/) - AI documentation writer.
  - Doc generation from code
  - Beautiful doc sites
  - API reference automation

- [Stenography](https://stenography.dev/) - Auto-generate docstrings.
  - VSCode extension
  - Multiple languages
  - Natural language docs

- [DocuWriter.ai](https://www.docuwriter.ai/) - Code documentation automation.
  - Supports 12+ languages
  - API docs
  - Comments generation

## AI Testing

- [Testim (Tricentis)](https://www.testim.io/) - AI for test automation.
  - Self-healing tests
  - Smart locators
  - Fast execution

## AI Refactoring

- [Sourcery](https://sourcery.ai/) - AI code reviewer for Python.
  - Automated refactoring
  - Code quality metrics
  - IDE integration

- [CodeScene](https://codescene.com/) - Behavioral code analysis.
  - Hotspot detection
  - Refactoring prioritization
  - Technical debt analysis

## Voice-Powered Coding

- [Cursorless](https://www.cursorless.org/) - Voice coding in VSCode.
  - Talon Voice integration
  - Grammar-based commands
  - Structural editing

- [Serenade](https://serenade.ai/) - Voice coding assistant.
  - Natural language coding
  - Works with any editor
  - Low activity since 2024; community-maintained fork

- [Talon Voice](https://talonvoice.com/) - Hands-free coding.
  - Eye tracking support
  - Custom grammars
  - Developer-focused

## Pair Programming with AI

### Chat-Based Coding

- [ChatGPT](https://chatgpt.com/) - Chat, data analysis, and Codex cloud coding tasks.
- [Claude](https://claude.ai/) - Long context coding assistant.
- [Gemini Code Assist](https://cloud.google.com/gemini/docs/codeassist/overview) - Google's coding assistant for Business and Enterprise; the individual tier ended in June 2026 in favour of Antigravity.
- [Perplexity](https://www.perplexity.ai/) - AI search with sources.

### Prompt Engineering for Code

- [Prompt Engineering Guide for Code](https://www.promptingguide.ai/applications/coding) - Best practices.
- [Code Generation Patterns](https://github.com/openai/openai-cookbook/blob/main/examples/How_to_format_inputs_to_ChatGPT_models.ipynb) - OpenAI cookbook.

## Infrastructure & DevOps AI

AI tools for infrastructure as code, cloud management, and DevOps automation.

- [K8sGPT](https://k8sgpt.ai/) - Kubernetes diagnostic tool.
  - AI-powered cluster analysis
  - Problem detection and solutions
  - Multi-language support
  - Open source

- [Pulumi Neo](https://www.pulumi.com/product/neo) - Pulumi's AI agent for infrastructure code (formerly Pulumi AI).
  - Natural language to infrastructure
  - Multi-cloud support
  - Plans and applies changes with review

## Database & SQL AI Tools

AI assistants for database queries, schema design, and data analysis.

- [AI2sql](https://www.ai2sql.io/) - Natural language to SQL.
  - Support for MySQL, PostgreSQL, MongoDB
  - Query optimization
  - Schema understanding
  - Multi-database support

- [Text2SQL.AI](https://www.text2sql.ai/) - Generate SQL from English.
  - Complex query generation
  - Explain existing queries
  - Schema-aware
  - Free tier available

- [Supabase Studio AI](https://supabase.com/) - PostgreSQL with AI features.
  - Schema generation
  - Query assistance
  - Real-time data
  - Open source

## Learning & Education

- [Exercism](https://exercism.org/) - Code practice with AI mentorship.
- [Codewars](https://www.codewars.com/) - Coding challenges.
- [LeetCode](https://leetcode.com/) - Interview prep (some AI features).
- [CodeAcademy](https://www.codecademy.com/) - Interactive learning.
- [Brilliant](https://brilliant.org/) - CS fundamentals with AI.
- [Wikivibe](https://wikivibe.ru/en/) - Practical knowledge base for AI-assisted development with guides, a glossary, jobs, and a public MCP endpoint.
- [Vibe Coding with Confidence](https://zalt.me/guides/vibe-coding) - Web handbook on building AI-assisted apps that work beyond the demo: plan, build, debug, harden, ship, operate, and scale.

## Productivity Tools

### Code Organization

- [Linear](https://linear.app/) - Issue tracking with AI features.
- [Notion AI](https://www.notion.so/product/ai) - Docs with AI.

### Git & Version Control

- [GitClear](https://www.gitclear.com/) - Code review metrics.
- [What The Diff](https://whatthediff.ai/) - AI-powered PR descriptions.
- [Gitsense](https://gitsense.com/) - Analytics and insights.

### CI/CD & DevOps

- [Harness](https://www.harness.io/) - AI-powered CI/CD.
- [Ona (formerly Gitpod)](https://ona.com/) - Cloud development environments and background agents.
- [Bito Governor](https://bito.ai/) - Model router and cost optimizer for Claude Code, Cursor, and Codex.
- [ccusage](https://github.com/ryoppippi/ccusage) - Token and cost reports for Claude Code and other coding agents.

## Open Source Projects

### AI Models for Code

- [Qwen3-Coder](https://github.com/QwenLM/Qwen3-Coder) - Alibaba's open-weight coding models.
  - 480B-A35B and 30B-A3B mixture-of-experts variants plus Qwen3-Coder-Next
  - 256K native context
  - Strong on agentic coding benchmarks
  - Apache 2.0

- [DeepSeek V4](https://api-docs.deepseek.com/) - DeepSeek's current open-weight model family.
  - V4-Pro and V4-Flash with 1M context
  - Available via the DeepSeek API and as open weights
  - Successor to DeepSeek Coder V2, V3, and R1

- [Devstral 2](https://mistral.ai/news/devstral-2-vibe-cli/) - Mistral's open-weight agentic coding models.
  - Devstral 2 (123B) and Devstral Small 2 (24B)
  - 256K context
  - Pairs with the Mistral Vibe CLI

- [gpt-oss](https://openai.com/index/introducing-gpt-oss/) - OpenAI's open-weight models.
  - gpt-oss-120b and gpt-oss-20b
  - Apache 2.0
  - Runs locally via Ollama, LM Studio, and vLLM

- [Kimi K2](https://github.com/MoonshotAI/Kimi-K2) - Moonshot AI's open-weight agentic model.
  - Mixture-of-experts with strong tool use
  - Powers Kimi Code CLI

- [GLM-5](https://github.com/zai-org/GLM-5) - Z.ai's open-weight coding and agent model.
  - Available through the GLM Coding Plan and as open weights

- [Phi-4](https://huggingface.co/microsoft/phi-4) - Microsoft's small models.
  - Phi-4 (14B), Phi-4-mini (3.8B), and Phi-4-reasoning
  - Efficient and good for local use

- [CodeLlama](https://github.com/meta-llama/codellama) - Meta's 2023 code model (legacy, repository archived).
- [StarCoder 2](https://huggingface.co/bigcode/starcoder2-15b) - BigCode's 2024 open code LLM (legacy).

### Frameworks & Libraries

- [LangChain](https://github.com/langchain-ai/langchain) - Build LLM apps.
- [LlamaIndex](https://github.com/run-llama/llama_index) - Data framework for LLMs.
- [Guidance](https://github.com/guidance-ai/guidance) - Control LLM generation.
- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) - Autonomous AI agent.
- [Vercel AI SDK](https://github.com/vercel/ai) - TypeScript toolkit for building AI apps and agents.
- [FastMCP](https://github.com/jlowin/fastmcp) - Pythonic framework for building MCP servers and clients.

### Tools

- [LocalGPT](https://github.com/PromtEngineer/localGPT) - Private document Q&A.
- [PrivateGPT](https://github.com/zylon-ai/private-gpt) - Local document analysis.
- [GPT4All](https://gpt4all.io/) - Local LLM runner.
- [MCP Inspector](https://github.com/modelcontextprotocol/inspector) - Reference tool for testing and debugging MCP servers.

## Benchmarks & Evaluation

### Benchmark Datasets

- [HumanEval](https://github.com/openai/human-eval) - Code generation benchmark with 164 programming problems.
- [HumanEval+](https://github.com/evalplus/evalplus) - Extended HumanEval with 80x more test cases.
- [MBPP](https://github.com/google-research/google-research/tree/master/mbpp) - Python programming benchmark with 1,000 crowd-sourced problems.
- [BigCodeBench](https://huggingface.co/datasets/bigcode/bigcodebench) - Code completion benchmark focused on real-world complexity.
- [SWE-bench](https://www.swebench.com/) - Software engineering benchmark using real GitHub issues; SWE-bench Verified is the 500-task human-validated subset.
- [SWE-bench Pro](https://labs.scale.com/leaderboard/swe_bench_pro_public) - Harder long-horizon successor with 1,865 tasks across 41 repositories.
- [Terminal-Bench](https://www.tbench.ai/) - Benchmark of agentic tasks carried out in a terminal.
- [Aider Polyglot](https://aider.chat/docs/leaderboards/) - 225 Exercism exercises across six languages.
- [SWE-rebench](https://swe-rebench.com/) - Monthly refreshed, contamination-resistant issue benchmark.
- [LiveCodeBench](https://livecodebench.github.io/) - Continuously updated benchmark to prevent data contamination.

### Leaderboards & Comparisons

- [Arena Code Leaderboard](https://arena.ai/leaderboard/code/webdev/) - Community-voted rankings for web development and agentic coding (formerly Chatbot Arena / LMArena).
- [Artificial Analysis](https://artificialanalysis.ai/) - Speed, price, and quality metrics, including a Coding Agent Index.

**Key Metrics to Compare:**
- Pass@1, Pass@10 (success rates)
- Context length (128K - 1M+ tokens)
- Languages supported
- Speed (tokens/second)
- Cost (per million tokens)
- Code quality and style
- Documentation generation
- Bug detection accuracy

### Quick Comparison: Top AI Coding Assistants

| Tool                     | Price                | Context                    | Best For                   | Offline           |
| ------------------------ | -------------------- | -------------------------- | -------------------------- | ----------------- |
| Cursor                   | Free / $20/mo        | 200K (1M in Max mode)      | Full IDE experience        | ❌                 |
| GitHub Copilot           | Free / $10/mo        | Up to 1M (model dependent) | Completion and agents      | ❌                 |
| Claude Code              | $20/mo Pro or API    | 1M                         | Terminal agent             | ❌                 |
| Codex CLI                | ChatGPT plan or API  | Model dependent            | Terminal agent             | ❌                 |
| Cline                    | Free (BYOK)          | Varies                     | Autonomous tasks           | ✅ (local models)  |
| Windsurf (Devin Desktop) | Free tier / Pro      | Varies by model            | Agentic IDE, beginners     | ❌                 |
| OpenCode                 | Free (BYOK)          | Varies                     | Open-source terminal agent | ✅ (local models)  |
| Tabby                    | Free                 | Custom                     | Self-hosted                | ✅                 |
| Zed                      | Free / $10/mo Pro    | Varies                     | Fast editor, collaboration | ✅ (local models)  |

## Cost Comparison

### Free Tier Options

- ✅ **GitHub Copilot Free** - 2,000 completions and 50 chat requests per month
- ✅ **Cline** - Free, open-source extension; bring your own keys or local models
- ✅ **OpenCode** - Free, MIT-licensed terminal agent; bring your own keys or local models
- ✅ **Gemini CLI** - Free tier with Google sign-in
- ✅ **Windsurf Plugin (formerly Codeium)** - Unlimited autocomplete on the free tier; agent use is quota-limited
- ✅ **Zed** - Free editor; unlimited AI with your own keys or local models, 2,000 free edit predictions
- ✅ **Tabby** - Free self-hosted Community edition (up to 5 users)
- ✅ **Bolt.new** - Free plan with a monthly token allowance
- ✅ **JetBrains AI** - Free tier included with JetBrains IDEs

## Best Practices & Guides

### Effective AI-Assisted Coding

- [AI-Enhanced Development Workflow](https://github.blog/2023-06-20-how-to-write-better-prompts-for-github-copilot/) - GitHub's guide.
- [The Art of AI Coding](https://code.visualstudio.com/docs/editor/artificial-intelligence) - VSCode docs.

### Security & Privacy

- [AI Code Security Best Practices](https://owasp.org/www-project-machine-learning-security-top-10/) - OWASP.
- [Securing AI-Generated Code](https://github.blog/2023-05-09-github-copilot-for-business-is-now-available/) - GitHub.

## AI Code Search & Discovery

Tools for searching code semantically, finding examples, and discovering patterns across repositories.

- [Sourcegraph](https://sourcegraph.com/) - Universal code search with AI.
  - Search across all your repos
  - AI-powered code intelligence
  - Batch changes
  - Code insights

- [grep.app](https://grep.app/) - Search across GitHub repos.
  - Fast regex search
  - 500K+ repos indexed
  - Real-time results
  - Free to use

- [searchcode](https://searchcode.com/) - Source code search engine.
  - 75+ billion lines of code
  - Multiple languages
  - API access
  - Open source

- [GitHub Code Search](https://github.com/features/code-search) - Native GitHub search.
  - Powered by AI
  - Semantic code search
  - Regular expression support
  - Symbol search

## AI-Powered IDE Extensions

Extensions and plugins that enhance your coding environment with AI capabilities.

### VSCode Extensions

- [GitHub Copilot Chat](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat) - Chat interface for Copilot.
- [Cline](https://marketplace.visualstudio.com/items?itemName=saoudrizwan.claude-dev) - Autonomous coding agent.
- [CodeGPT](https://marketplace.visualstudio.com/items?itemName=DanielSanMedium.dscodegpt) - Multiple AI providers.
- [Windsurf Plugin (formerly Codeium)](https://docs.devin.ai/windsurf/plugins/getting-started) - Free AI autocomplete.
- [Continue](https://marketplace.visualstudio.com/items?itemName=Continue.continue) - Open-source AI assistant (unmaintained since June 2026).
- [Tabnine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode) - AI code completion (legacy listing, enterprise only).

### JetBrains Plugins

- [GitHub Copilot](https://plugins.jetbrains.com/plugin/17718-github-copilot) - Official Copilot plugin.
- [AI Assistant](https://plugins.jetbrains.com/plugin/22282-ai-assistant) - Built-in JetBrains AI.
- [Junie](https://www.jetbrains.com/junie/) - JetBrains' coding agent.
- [Sweep](https://sweep.dev/) - AI autocomplete and coding agent for JetBrains.
- [Tabnine](https://plugins.jetbrains.com/plugin/12798-tabnine-ai-code-completion) - AI completion (legacy listing, enterprise only).

### Neovim Plugins

- [copilot.vim](https://github.com/github/copilot.vim) - GitHub Copilot for Vim/Neovim.
- [windsurf.nvim](https://github.com/Exafunction/windsurf.nvim) - Free AI completion (formerly codeium.nvim).
- [copilot.lua](https://github.com/zbirenbaum/copilot.lua) - Lua Copilot client for Neovim.

## Learning Paths & Tutorials

Structured guides for mastering AI-assisted development.

### Getting Started (Beginners)

- [Getting Started with GitHub Copilot](https://github.com/skills/getting-started-with-github-copilot) - Official GitHub Skills course.
- [Intro to AI Agents](https://www.codecademy.com/learn/intro-to-ai-agents) - Codecademy interactive course.
- [AI Python for Beginners](https://www.deeplearning.ai/short-courses/ai-python-for-beginners/) - DeepLearning.AI course that teaches Python with an AI assistant.

### Intermediate

- [Advanced Prompt Engineering for Code](https://learnprompting.org/docs/basic_applications/coding_assistance) - Deep dive.
- [Building with AI Agents](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/) - Agent workflows.
- [Multi-Agent Systems](https://learn.microsoft.com/en-us/semantic-kernel/frameworks/agent/) - Semantic Kernel.

### Advanced

- [Hugging Face LLM Course](https://huggingface.co/learn/llm-course) - Transformers, fine-tuning, and evaluation.
- [Building Custom AI Tools](https://platform.openai.com/docs/guides/function-calling) - OpenAI functions.
- [Evaluating Code LLMs](https://github.com/bigcode-project/bigcode-evaluation-harness) - Benchmark creation.

## Success Stories & Case Studies

Real-world examples of AI-assisted development impact.

- [GitHub Customer Stories](https://github.com/customer-stories) - Attributed Copilot impact stories from Duolingo, Uber, and others.
- [Under the River: Shopify's AI coding agent](https://shopify.engineering/under-the-river) - How Shopify's River agent co-authors one in eight merged pull requests.
- [A quarter of YC W25 startups have mostly AI-generated codebases](https://techcrunch.com/2025/03/06/a-quarter-of-startups-in-ycs-current-cohort-have-codebases-that-are-almost-entirely-ai-generated) - Jared Friedman (YC) on AI-written code in the W25 batch.
- [Cursor Customer Stories](https://cursor.com/customers) - Attributed case studies from Coinbase, Brex, Nokia, and Vercel.
- [CodeRabbit Customer Stories](https://coderabbit.ai/customers) - Automated code review results.

## Model Providers & APIs

Direct access to LLMs for building custom coding tools.

### Commercial APIs

- [OpenAI API](https://platform.openai.com/) - GPT-5.6, GPT-5.5, GPT-5.3-Codex.
  - Codex models tuned for agentic coding
  - Function calling and vision
  - Codex CLI and cloud agent
  - $0.20-$5 input / $1.20-$30 output per 1M tokens

- [Anthropic API](https://platform.claude.com/) - Claude Fable 5.1, Opus 5, Sonnet 5, Haiku 4.5.
  - 1M context window (200K for Haiku)
  - Strong agentic coding and reasoning
  - Claude Code and the Claude Agent SDK
  - $1-$10 input / $5-$50 output per 1M tokens

- [Google Gemini API](https://ai.google.dev/) - Gemini 3.1 Pro, Gemini 3.8 Flash, Flash-Lite.
  - 1M context window
  - Multimodal capabilities
  - Code execution
  - Free tier for Flash models

- [Mistral AI API](https://mistral.ai/) - Codestral 25.08, Devstral 2, Devstral Small 2.
  - Code-specialized models
  - Fill-in-the-middle
  - European data residency
  - Open-source Mistral Vibe CLI

### Open Source Model Hosting

- [Together AI](https://www.together.ai/) - Host open source models.
  - DeepSeek, Qwen, Kimi, GLM, gpt-oss
  - Fast inference
  - Pay-per-use

- [Replicate](https://replicate.com/) - Run models via API.
  - One-line deployment
  - Auto-scaling
  - Simple pricing

- [Hugging Face Inference Providers](https://huggingface.co/docs/inference-providers) - Serverless inference across many providers.
  - Access to open models on Hugging Face through one API
  - Free monthly credits
  - Custom endpoints

### Self-Hosted

- [Ollama](https://ollama.com/) - Run LLMs locally.
  - Easy model management
  - Mac, Linux, Windows
  - REST API
  - Free and open source

- [LM Studio](https://lmstudio.ai/) - Local model UI.
  - GUI for model management
  - Chat interface
  - Compatible with OpenAI API
  - No coding required

- [LocalAI](https://localai.io/) - OpenAI alternative.
  - Self-hosted API
  - OpenAI-compatible
  - Multiple backends
  - Docker support

## Enterprise & Team Tools

### Team Collaboration

- [GitHub Copilot for Business](https://github.com/features/copilot/plans) - Enterprise-grade AI pair programming.
  - Organization-wide licensing
  - Policy management
  - Usage analytics
  - Admin controls

- [Tabnine Enterprise](https://www.tabnine.com/pricing) - Self-hosted AI coding platform, now part of Tricentis.
  - On-premise deployment
  - Custom models
  - IP protection
  - Code Assistant $39 and Agentic Platform $59 per user per month

### Code Review Assistants

- [Codacy](https://www.codacy.com/) - Automated code reviews.
  - Static analysis
  - Coverage tracking
  - Security scanning
  - CI/CD integration

## Code Quality & Refactoring

### Refactoring Tools

- [Rope](https://github.com/python-rope/rope) - Python refactoring library.
  - Automated refactorings
  - IDE integration
  - Open source

### Code Analysis

- [SonarQube](https://www.sonarsource.com/products/sonarqube/) - Code quality platform.
  - 30+ languages
  - Security hotspots
  - Technical debt tracking
  - Self-hosted or cloud

- [Semgrep](https://semgrep.dev/) - Static analysis with AI.
  - Custom rules
  - Security scanning
  - Fast and precise
  - Free for individuals

## Security & Privacy

### Secure Coding Tools

- [GitHub Advanced Security](https://github.com/features/security) - Enterprise security scanning.
  - Secret scanning
  - Dependency review
  - Code scanning
  - Security advisories

- [GitGuardian](https://www.gitguardian.com/) - Secrets detection.
  - Real-time alerts
  - Historical scanning
  - Policy enforcement
  - Free for individuals

### Privacy-First Alternatives

- [Tabby](https://github.com/TabbyML/tabby) - Self-hosted AI coding assistant.
  - Local deployment
  - No telemetry
  - Open source
  - GPU or CPU

## Workflow Integration

### CI/CD Integration

- [GitHub Actions](https://github.com/features/actions) - Automate workflows.
  - Pre-trained models
  - Custom actions
  - Workflow automation
  - Free for public repos

- [GitLab Duo Agent Platform](https://about.gitlab.com/gitlab-duo-agent-platform/) - GitLab's AI agent platform.
  - Code suggestions
  - Pipeline generation
  - Security scanning

- [agenttrace](https://github.com/luoyuctl/agenttrace) - Local TUI and report generator for AI coding-agent sessions.
  - Audits tokens, costs, tool calls, and run history
  - Supports local Claude Code, Codex CLI, Gemini CLI, Aider, Cursor, Qwen Code, Cline, OpenCode/OpenClaw, Kimi CLI, and JSON/JSONL traces
  - Provides Markdown/JSON reports and CI health gates

- [Mergify](https://mergify.com/) - PR automation.
  - Auto-merge rules
  - Queue management
  - AI-assisted reviews
  - Free for open source

## Community & Resources

### Blogs & Articles

- [AI Coding Tools Blog](https://www.cursor.com/blog) - Cursor blog.
- [GitHub Blog AI](https://github.blog/category/ai-and-ml/) - GitHub AI news.
- [Sourcegraph Blog](https://about.sourcegraph.com/blog) - Developer tools insights.

### YouTube Channels

- [Fireship](https://www.youtube.com/@Fireship) - AI coding tools reviews.
- [ThePrimeagen](https://www.youtube.com/@ThePrimeagen) - Dev tool discussions.
- [Theo - t3.gg](https://www.youtube.com/@t3dotgg) - Modern web development.

### Podcasts

- [Latent Space](https://www.latent.space/podcast) - AI engineering.
- [Practical AI](https://changelog.com/practicalai) - AI in practice.
- [The Changelog](https://changelog.com/podcast) - Developer tools.

### Communities

- [r/ChatGPTCoding](https://www.reddit.com/r/ChatGPTCoding/) - Reddit community.
- [r/cursor](https://www.reddit.com/r/cursor/) - Cursor users.
- [Cursor Community](https://forum.cursor.com/) - Official forum.
- [GitHub Copilot Discord](https://discord.gg/github-community) - Community support.

## Related Lists

- [awesome-claude-ai](https://github.com/tysoncung/awesome-claude-ai) - Claude AI tools and resources.
- [awesome-prompt-engineering](https://github.com/tysoncung/awesome-prompt-engineering) - Prompt engineering.
- [awesome-devsecops](https://github.com/tysoncung/awesome-devsecops) - DevSecOps tools and security.
- [awesome-chatgpt](https://github.com/humanloop/awesome-chatgpt) - ChatGPT resources.
- [awesome-llm](https://github.com/Hannibal046/Awesome-LLM) - Large Language Models.
- [awesome-ai-tools](https://github.com/mahseema/awesome-ai-tools) - AI tools collection.

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

**What to contribute:**
- New AI coding tools and assistants.
- Benchmarks and comparisons.
- Best practices and guides.
- Use cases and success stories.
- Tutorials and resources.

To the extent possible under law, [Tyson Cung](https://github.com/tysoncung) has waived all copyright and related or neighboring rights to this work.

---

**Star ⭐ this repo if you find it useful! Share with fellow developers!**

---

*Last updated: September 03, 2026*
