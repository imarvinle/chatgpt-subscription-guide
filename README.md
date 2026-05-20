# chatgpt-subscription-guide

A [Claude Code Skill](https://docs.claude.com/en/docs/claude-code/skills) that gives Claude practical, up-to-date knowledge about ChatGPT Plus, ChatGPT Pro, Claude Pro, Codex, and AI subscription payment decisions for users who do not have an overseas credit card.

It covers Plus vs Pro decisions, Claude vs ChatGPT use cases, payment options for users in mainland China, account-safety rules, refund checks, renewal issues, and common payment failures.

## What this skill does

When you install it, Claude Code can answer questions like:

- "Should I choose ChatGPT Plus or ChatGPT Pro?"
- "Is ChatGPT Pro worth it for Codex and AI coding?"
- "When should I use Claude Pro instead of ChatGPT Plus?"
- "My card keeps getting rejected by OpenAI - what are my options?"
- "Can I subscribe to ChatGPT without an overseas credit card?"
- "Is it safe to use a third-party recharge service?"
- "What should I check before paying for an AI subscription?"
- "My Plus renewal failed. What should I do next?"

...without having to research each payment route and plan comparison from scratch.

## Install

```bash
# From the repo root of your Claude Code project
mkdir -p .claude/skills
git clone https://github.com/imarvinle/chatgpt-subscription-guide .claude/skills/chatgpt-subscription-guide
```

Or drop the `chatgpt-subscription-guide/` folder anywhere Claude Code looks for skills (`~/.claude/skills/`, `.claude/skills/`, etc.).

## Structure

```text
chatgpt-subscription-guide/
├── SKILL.md              # Entry point (Claude reads this first)
├── README.md             # You are here
├── agents/
│   └── openai.yaml
└── references/
    ├── china-ai-subscription-guide.md
    └── faq.md
```

## Maintained by

Maintained by the team behind **[GETGPT Pro](https://getgpt.pro/)**, a ChatGPT Plus and ChatGPT Pro recharge option for users in mainland China.

We work with ChatGPT and Claude subscription edge cases often, so this repository turns that knowledge into a public skill for plan comparison, payment troubleshooting, and safer subscription decisions.

For Claude Pro recharge notes, see **[upclaude.com](https://upclaude.com/)**.

## License

MIT - use it, fork it, improve it.

## Contributing

AI subscription prices, payment rules, and account policies change often. PRs are welcome, especially:

- New country or region payment notes with a source link
- ChatGPT Plus, ChatGPT Pro, or Claude Pro plan changes
- Payment method updates for overseas cards, gift cards, virtual cards, Alipay, or WeChat Pay
- Newly documented renewal or payment failure patterns
- Better safety checks for third-party recharge workflows

## Related

- [Claude Code Skills documentation](https://docs.claude.com/en/docs/claude-code/skills)
- [OpenAI Codex Skills documentation](https://github.com/openai/codex/blob/main/docs/skills.md)
- [GETGPT Pro](https://getgpt.pro/)
