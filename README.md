> I build on Solana and with AI — products that move money, watch chains, and automate the boring parts.
> I work the whole stack: Rust programs, Next.js frontends, Postgres, queues, whatever the product needs that week.
> This page is the receipts.

<h1 align="center">🛠️ Proof of Work</h1>


### 🪐 Solana × Real-time Intelligence

| Project | What it does | Stack | Links |
|---|---|---|---|
| **Khaata** | My stablecoin cash register — non-custodial USDC checkout on Solana with UPI-grade UX. Money lands straight in the merchant's wallet in ~1.4s, every receipt verifiable on-chain | Next.js 16 · Rust · Anchor · Drizzle · Postgres · Tailwind | [Live](https://dev.khaata.xyz) |
| **WatchTower** | My private watchdog — a single Rust binary that tracks Solana prices and balances over Telegram and pings me the moment a rule trips. No dashboard, no custody, no noise | Rust · SQLite · Telegram Bot API · Solana RPC | [Repo](https://github.com/0xuser64bit/WatchTower) |
| **Praxis** | Gave an agent a wallet without giving it trust — plain English becomes simulated Solana transactions, while an on-chain program enforces spend caps and allow-lists. A jailbroken LLM stays inside the envelope | Next.js · Rust · Anchor · Gemini · TS | [Live](https://usepraxis.fun) · [Repo](https://github.com/0xuser64bit/Praxis) |
| **RugPulse** | New-token radar for Solana — fresh launches enriched and scored deterministically, so you get a trader-readable verdict instead of vibes | Next.js · TS · Birdeye · Tailwind | [Repo](https://github.com/0xuser64bit/RugPulse) |
| **GetToasted** | Got toasted? This proves it — scans any Solana wallet for sandwich attacks and prices the MEV damage in USD. Validated 30/30 against real Jito bundles | Next.js · TS · Helius · BullMQ · Jupiter | [Live](https://gettoasted.fun) · [Repo](https://github.com/0xuser64bit/GetToasted) |
| **GhostTip** | Tip anyone on X without the awkward wallet-address DM — X-OAuth claims, private-rail settlement, auto-refund if never claimed | Next.js · Solana · Prisma · Loyal Network | [Live](https://ghost-tip.vercel.app) · [Repo](https://github.com/0xuser64bit/Ghost-Tip) |
| **Receba Guard** | Brazilian merchants get paid in USDC over WhatsApp — and a local Rust verifier, not a screenshot, decides when an invoice is really settled | Rust · Solana · WhatsApp · Solana Pay | [Live](https://receba-guard.vercel.app/) · [Repo](https://github.com/0xuser64bit/receba-guard) |
| **Tipmark** | Buy-me-a-coffee with no platform in the middle — creators claim a handle, supporters send SOL direct, Arweave holds the profile, the chain holds the receipts | Next.js 15 · Rust · Anchor · Arweave · Solana · TS | [Live](https://tipmark-platform.vercel.app) · [Repo](https://github.com/0xuser64bit/Tipmark) |
| **PollChain** | Voting where the ballot box is the blockchain — create polls, vote, verify, all on-chain | Rust · Anchor · Solana · Next.js · TS | [Live](https://poll-chain.vercel.app/) · [Repo](https://github.com/0xuser64bit/poll-chain) |
| **sous** | My sous-chef for Cookie Chain — quotes, swaps, staking, and bridging behind a paper-ticket review. You read the ticket, sign in Nightly, get a receipt. The app never touches keys | Next.js · TS · Cookie Chain · Nightly · MCP | [Live](https://sous.usevora.fun) · [Repo](https://github.com/0xuser64bit/sous) |

---

### 🤖 AI Agents, MCP & RAG

| Project | What it does | Stack | Links |
|---|---|---|---|
| **DevDNA** | Paste a GitHub username, get a cinematic developer identity report. Pure fun, built to be shared | Next.js · TS · Tailwind · framer-motion | [Live](https://dev-dna-theta.vercel.app) · [Repo](https://github.com/0xuser64bit/dev-dna) |
| **DD-Agent** | A Don't-Die-inspired longevity coach — chat about health, get structured plans back | Next.js · OpenAI · TS · Tailwind | [Live](https://dd-agent-ruby.vercel.app) · [Repo](https://github.com/0xuser64bit/dd-agent) |
| **Ask Genie** | A lamp button for every page you read — summon AI grounded in the article, with your own key. No backend, nothing leaves your machine | Vite · React · TS · OpenAI · Anthropic | [Repo](https://github.com/0xuser64bit/ask-genie) |
| **Legal Sahayak** | Indian legal help as an MCP server — bonds, POSH, consumer rights — pluggable into Puch AI or Claude | Python · MCP · FastAPI | [Repo](https://github.com/0xuser64bit/legal-sahayak-mcp) |
| **RAG-PDF** | Upload a PDF, interrogate it — cited answers over your own documents | Django · ChromaDB · OpenAI | [Repo](https://github.com/0xuser64bit/rag-pdf) |

---

### 🧰 Developer Tools & Experiments

| Project | What it does | Stack | Links |
|---|---|---|---|
| **TweetFolio** | This profile's louder sibling — a portfolio styled as an X feed | Next.js · TS · Tailwind | [Live](https://user64bit.vercel.app) · [Repo](https://github.com/0xuser64bit/The-Tweetfolio) |
| **Get Git** | GitHub profiles worth looking at — contributions, repos, and activity in one interactive page | Next.js · GitHub API · TS | [Live](https://get-git-search.vercel.app/) · [Repo](https://github.com/0xuser64bit/get-git) |
| **cry-on-crash** | Your terminal failures, dramatized — a sound every time a command or diagnostic blows up. You'll fix things faster just to shut it up | TypeScript · VS Code API | [Repo](https://github.com/0xuser64bit/cry-on-crash) |
| **Notebook** | A Notion alternative that doesn't read your notes — private by design | Next.js · Convex · TS · Tailwind | [Live](https://notebook-self-phi.vercel.app/) · [Repo](https://github.com/0xuser64bit/notebook) |
| **Suchi** | A task CLI that stays out of the way — add, edit, done. Written in Rust because startup time is a feature | Rust | [Live](https://crates.io/crates/suchi) · [Repo](https://github.com/0xuser64bit/suchi) |
| **Echo GPT** | Never lose a good ChatGPT thread again — pin and bookmark conversations | TS · Chrome APIs | [Repo](https://github.com/0xuser64bit/echo-gpt) |
| **Job Not Finished** | Shame as a service — a dashboard that roasts you about abandoned repos until you finish them | Next.js 15 · GitHub API · TS | [Live](https://job-not-finished.vercel.app) · [Repo](https://github.com/0xuser64bit/job-not-finished) |
| **ChibiTown** | A pixel-art office for remote teams — walk around, see who's here, skip the wall of video tiles | React · TS · Phaser · Express · Prisma · WebSocket · Turborepo | [Demo](https://youtu.be/Whr1wNQ97Tc) · [Repo](https://github.com/0xuser64bit/ChibiTown) |

---

### 🧪 Earlier Builds

[CryptoCompass](https://github.com/0xuser64bit/CryptoCompass) · [CodeRunner](https://github.com/0xuser64bit/CodeRunner) · [Streamify](https://github.com/0xuser64bit/streamify) · [Flashcards](https://github.com/0xuser64bit/Flashcards) · [tweet-it](https://github.com/0xuser64bit/tweet-it) · [Canteen](https://github.com/0xuser64bit/Canteen) — the archive of experiments that taught me everything above.

---

## 🔎 Want more?

> Explore every PR, review & open-source contribution on **[Get Git →](https://get-git-search.vercel.app/0xuser64bit)**
