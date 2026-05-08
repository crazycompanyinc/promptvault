# ⬡ PromptVault — Version Control for AI Prompts

> Git-like version control, A/B testing, and collaboration for your AI prompts.

## Why PromptVault?

Teams lose track of what prompt version is in production. When something breaks, nobody knows what changed. PromptVault gives you:

- **Git-like version control** — commit, diff, branch, merge prompts
- **A/B testing** — compare variants with statistical significance
- **One-click rollback** — instantly revert to any previous version
- **Team collaboration** — review workflows, comments, approvals
- **CI/CD integration** — API and CLI for automated testing
- **Self-hosted option** — your prompts never leave your servers

## Framework-Agnostic

Works with OpenAI, Anthropic, Google, LangChain, LlamaIndex, or any custom setup.

## Quick Start

```bash
# Install
npm i -g promptvault

# Initialize
promptvault init

# Commit a prompt
promptvault commit -m "Add customer support v2"

# Compare versions
promptvault diff v1 v2

# Rollback
promptvault rollback v1
```

## Pricing

| Plan | Price | Prompts | Features |
|------|-------|---------|----------|
| Free | $0 | 10 | Version history, CLI |
| Pro | $19/mo | 100 | A/B testing, team collab, CI/CD |
| Team | $49/mo | Unlimited | Self-hosted, SSO, compliance |

## Comparison

| Feature | PromptVault | PromptLayer | LangSmith | Helicone |
|---------|-------------|-------------|-----------|----------|
| Version Control | ✅ Full git-like | ✅ Basic | ✅ Basic | ❌ |
| A/B Testing | ✅ Built-in | ✅ | ❌ | ❌ |
| Self-Hosted | ✅ | ❌ | ❌ | ❌ |
| Framework-Agnostic | ✅ | ✅ | ❌ LangChain only | ✅ |
| Free Tier | ✅ 10 prompts | ✅ Limited | ❌ | ✅ |
| CLI-First | ✅ | ❌ | ❌ | ❌ |

## Roadmap

- [ ] CLI tool (Python + Node)
- [ ] Web dashboard
- [ ] API for CI/CD
- [ ] Self-hosted Docker image
- [ ] VS Code extension
- [ ] Slack integration

## License

MIT © 2026 ZOO Technologies
