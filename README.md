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
- Install free evaluator skill: `npx skills add https://github.com/fxjim/agent-commerce-guard --skill try-agent-commerce-guard`
- Install GitHub Copilot plugin: `copilot plugin install fxjim/agent-commerce-guard:plugins/agent-commerce-guard`
- Policy-only review API: https://agent-commerce-guard.vercel.app/api/policy-review
- Policy-only remote MCP server: https://agent-commerce-guard.vercel.app/api/mcp
- MCP setup guide: https://agent-commerce-guard.vercel.app/mcp
- Pages MCP setup mirror: https://fxjim.github.io/agent-commerce-guard/mcp/
- Connect from Codex: `codex mcp add agent-commerce-guard --url https://agent-commerce-guard.vercel.app/api/mcp`
- Connect from Claude Code: `claude mcp add --transport http agent-commerce-guard https://agent-commerce-guard.vercel.app/api/mcp`
- MCP offer resource: https://agent-commerce-guard.vercel.app/offer.json
- MCP initialization guidance: inspect the public offer resource, require explicit user approval before payment, and verify the Base USDC transaction after payment
- MCP guided prompt: `review-before-purchase` joins policy review, offer inspection, explicit approval, and verified receipt handling without initiating payment
- Official MCP Registry listing: https://registry.modelcontextprotocol.io/?search=agent-commerce-guard
- MCP Registry server name: `io.github.fxjim/agent-commerce-guard`
- Immutable MCP server release: `mcp-server-v1.2.0` at `582a9d66bedd913d0fe0334b91c8b2b851de5562`
- MCP release notes: https://github.com/fxjim/agent-commerce-guard/releases/tag/mcp-server-v1.2.0
- MCP Registry publish run: `30142593478`
- Awesome Copilot external-plugin review: https://github.com/github/awesome-copilot/issues/2413
- Install buyer skill: `npx skills add https://github.com/fxjim/agent-commerce-guard --skill buy-agent-commerce-guard`
- Canonical-domain install: `npx skills add https://agent-commerce-guard.vercel.app --skill buy-agent-commerce-guard`
- Canonical buyer-skill index: https://agent-commerce-guard.vercel.app/.well-known/skills/index.json
- GitHub Pages buyer-skill index: https://fxjim.github.io/agent-commerce-guard/.well-known/skills/index.json
- Skills directory: https://skills.sh/fxjim/agent-commerce-guard/buy-agent-commerce-guard
- Free evaluator presets: wallet spend, production deploys, token launches, and marketplace jobs
- Free GitHub Action: `uses: fxjim/agent-commerce-guard@v1`
- Latest GitHub Action release: https://github.com/fxjim/agent-commerce-guard/releases/tag/v1.0.2
- GitHub Action sample workflow: https://github.com/fxjim/agent-commerce-guard/tree/v1.0.2/examples/github-actions
- GitHub Action proof and purchase outputs: `sample-report-url`, `package-metadata-url`, `base-mcp-recipe-url`, `checkout-url`, and `x402-evaluate-url`
- Public Gist buyer brief: https://gist.github.com/fxjim/869cada8014dc52f520cccbce655f0eb
- Buy the Base launch pass: https://agent-commerce-guard.vercel.app/pay
- One-tap Base Account checkout: the official `/pay` page links to the full sample report, Base MCP purchase recipe, and support before a user-confirmed 1 USDC payment, automatically waits for a pending receipt, preserves the returned transaction hash across refreshes, then verifies it server-side before unlock.
- Verify a Base payment: https://agent-commerce-guard.vercel.app/verify?tx={tx}
- Success unlock page: https://agent-commerce-guard.vercel.app/success?tx={tx} retries pending receipts, resumes after refresh, and focuses the verified package download when ready.
- Well-known payment request: https://agent-commerce-guard.vercel.app/.well-known/pay.json
- Agent purchase guide: https://agent-commerce-guard.vercel.app/buy
- Package metadata: https://agent-commerce-guard.vercel.app/package-metadata.json
- Service status: https://agent-commerce-guard.vercel.app/status.json
- Well-known service status: https://agent-commerce-guard.vercel.app/.well-known/status.json
- License terms: https://agent-commerce-guard.vercel.app/license
- Well-known license terms: https://agent-commerce-guard.vercel.app/.well-known/license.md
- Pages package metadata mirror: https://fxjim.github.io/agent-commerce-guard/package-metadata.json
- Public sample CLI report: https://agent-commerce-guard.vercel.app/sample-report
- Machine-readable sample report: https://agent-commerce-guard.vercel.app/sample-report.json
- GitHub Pages package preview: https://fxjim.github.io/agent-commerce-guard/sample/
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
- Current production deployment: `dpl_HGrmKwsoozaskbdxnbh2ha4EaWbe`
- Current public launch commit: `d63e4429109963c285b7c5664c0bf732a5eba468`
- Current GitHub Pages run: `30142077346`
- Awesome Copilot intake run: `30056882220` (automated quality gates passed; ready for review)
- GitHub Action smoke run: `30139660040`
- Current product validation: `64/64` tests, functional checkout and success-page pending-receipt polling, refresh recovery, invalid-hash rejection, focused post-verification download, and confirmed-non-payment browser checks, desktop and mobile no-overflow checks, clean public build, zero npm vulnerabilities, exact Action discovery readback across Vercel and Pages, live policy-only review API, live remote MCP initialization guidance plus one tool, one offer resource, and one non-executing prompt, active latest Registry version `1.2.0`, live six-check buyer preflight, and tarball-backed proof for all 13 advertised package files
- Current paid package shasum: `c67fb09bd83da591c58ae5fae002a6a59557fc97`
- Current paid package size: `122737` bytes
- Payment metadata now advertises `/success?tx={tx}` alongside `/verify?tx={tx}` for post-payment unlock.
- Official x402scan discovery classifies both 1 USDC routes as paid and all five public utility routes as unprotected with zero warnings.
- The checkout leads with the official Base Account payment control and keeps browser-wallet and payment-URI fallbacks. Both browser unlock pages automatically retry pending receipts, recover valid transaction hashes after refresh, and require server-side Base USDC verification before exposing the download.

The first launch pass is priced at 1 USDC on Base and unlocks the packaged CLI, templates, examples, and installable guardrail skill.
