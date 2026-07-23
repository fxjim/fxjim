# fxjim

Current public launch:

## Agent Commerce Guard

Agent Commerce Guard is an x402-paid workflow validator and approval-gate pack for AI agents before wallet spend, deployments, command risk, token launches, social actions, or credential access.

[![Agent Skills installs](https://www.skills.sh/b/fxjim/agent-commerce-guard)](https://www.skills.sh/fxjim/agent-commerce-guard/buy-agent-commerce-guard)

- Live product: https://agent-commerce-guard.vercel.app
- Agent-readable offer: https://agent-commerce-guard.vercel.app/offer.json
- GitHub Pages launch page: https://fxjim.github.io/agent-commerce-guard/
- Pages offer mirror: https://fxjim.github.io/agent-commerce-guard/offer.json
- Pages well-known offer mirror: https://fxjim.github.io/agent-commerce-guard/.well-known/agent-commerce-guard.json
- Pages well-known offer alias: https://fxjim.github.io/agent-commerce-guard/.well-known/offer.json
- Pages well-known x402: https://fxjim.github.io/agent-commerce-guard/.well-known/x402
- Pages well-known purchase guide: https://fxjim.github.io/agent-commerce-guard/.well-known/purchase.json
- Install buyer skill: `npx skills add https://github.com/fxjim/agent-commerce-guard --skill buy-agent-commerce-guard`
- Canonical-domain install: `npx skills add https://agent-commerce-guard.vercel.app --skill buy-agent-commerce-guard`
- Canonical buyer-skill index: https://agent-commerce-guard.vercel.app/.well-known/skills/index.json
- GitHub Pages buyer-skill index: https://fxjim.github.io/agent-commerce-guard/.well-known/skills/index.json
- Skills directory: https://skills.sh/fxjim/agent-commerce-guard/buy-agent-commerce-guard
- Free GitHub Action: `uses: fxjim/agent-commerce-guard@v1`
- GitHub Action release: https://github.com/fxjim/agent-commerce-guard/releases/tag/v1.0.0
- Public Gist buyer brief: https://gist.github.com/fxjim/869cada8014dc52f520cccbce655f0eb
- Buy the Base launch pass: https://agent-commerce-guard.vercel.app/pay
- One-tap Base Account checkout: the official `/pay` page leads with a user-confirmed 1 USDC payment and verifies the returned transaction server-side before unlock.
- Verify a Base payment: https://agent-commerce-guard.vercel.app/verify?tx={tx}
- Success unlock page: https://agent-commerce-guard.vercel.app/success?tx={tx}
- Well-known payment request: https://agent-commerce-guard.vercel.app/.well-known/pay.json
- Agent purchase guide: https://agent-commerce-guard.vercel.app/buy
- Package metadata: https://agent-commerce-guard.vercel.app/package-metadata.json
- Service status: https://agent-commerce-guard.vercel.app/status.json
- Well-known service status: https://agent-commerce-guard.vercel.app/.well-known/status.json
- License terms: https://agent-commerce-guard.vercel.app/license
- Well-known license terms: https://agent-commerce-guard.vercel.app/.well-known/license.md
- Pages package metadata mirror: https://fxjim.github.io/agent-commerce-guard/package-metadata.json
- Pages service status mirror: https://fxjim.github.io/agent-commerce-guard/status.json
- Pages well-known service status mirror: https://fxjim.github.io/agent-commerce-guard/.well-known/status.json
- Pages license mirror: https://fxjim.github.io/agent-commerce-guard/license/
- Pages well-known license mirror: https://fxjim.github.io/agent-commerce-guard/.well-known/license.md
- LLM-readable summary: https://agent-commerce-guard.vercel.app/llms.txt
- Well-known LLM summary: https://agent-commerce-guard.vercel.app/.well-known/llms.txt
- Agents manifest: https://agent-commerce-guard.vercel.app/agents.json
- Singular agent manifest alias: https://agent-commerce-guard.vercel.app/agent.json
- Well-known singular agent manifest alias: https://agent-commerce-guard.vercel.app/.well-known/agent.json
- Pages singular agent manifest: https://fxjim.github.io/agent-commerce-guard/agent.json
- Pages well-known singular agent manifest: https://fxjim.github.io/agent-commerce-guard/.well-known/agent.json
- Pages well-known LLM summary: https://fxjim.github.io/agent-commerce-guard/.well-known/llms.txt
- x402 paid evaluator: https://agent-commerce-guard.vercel.app/api/x402-evaluate
- x402 paid package download: https://agent-commerce-guard.vercel.app/api/x402-download
- Public repo and release notes: https://github.com/fxjim/agent-commerce-guard
- Launch/support thread: https://github.com/fxjim/agent-commerce-guard/issues/1
- Launch discussion: https://github.com/fxjim/agent-commerce-guard/discussions/2
- Current production deployment: `dpl_FUQJgzEah8HjEyY2FJwVuE83wbzX`
- Current public launch commit: `7b45e75f9057a9324a3c6948a0ee4bcf8ed34aba`
- Current GitHub Pages run: `30052241574`
- GitHub Action smoke run: `30052243054`
- Current paid package shasum: `c67fb09bd83da591c58ae5fae002a6a59557fc97`
- Current paid package size: `122737` bytes
- Payment metadata now advertises `/success?tx={tx}` alongside `/verify?tx={tx}` for post-payment unlock.
- Official x402scan discovery classifies both 1 USDC routes as paid and all five public utility routes as unprotected with zero warnings.
- The checkout leads with the official Base Account payment control, keeps browser-wallet and payment-URI fallbacks, and requires server-side Base USDC verification before unlock.

The first launch pass is priced at 1 USDC on Base and unlocks the packaged CLI, templates, examples, and installable guardrail skill.
