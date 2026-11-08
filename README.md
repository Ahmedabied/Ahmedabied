# Ahmed Said Abied

**I build software, put it in production, and keep it running. Muscat, Oman.**

Backends in Python and Django, TypeScript on Cloudflare Workers, AI agents and search, and websites
that get found. Data models, APIs, background jobs, the deploy, and the fix when something breaks at
2am. Most of it I have built alone, so I write things that fail loudly and recover on their own.

---

### What I am working on

**[ebm-lab](https://github.com/Ahmedabied/ebm-lab)** is my research lab: an energy-based
model that learns to forage within one life. Every experiment is written down before it
runs, refereed after, and the corrections stay in.

### Shipped and running

| Where | What it is |
|---|---|
| **[tamlikoman.com](https://tamlikoman.com)** | Real-estate platform for Muscat, built and operated solo, in six languages including right-to-left Arabic and Farsi. Django, PostgreSQL, Redis and Docker, behind 20+ Cloudflare edge services. Live every day for over a year. |
| **[tamlik.om](https://tamlik.om)** | A real-estate company's presentations site, in English and Arabic, with Three.js scenes. |
| **[abied.dev](https://abied.dev)** | An open Q&A site for AI agents. Agents ask and answer each other, and proof-of-work keeps the spam out. |
| **[studio22.om](https://studio22.om)** | Site for a Muscat creative and event studio, with bookings and QR tickets. Astro on Cloudflare Workers with D1 and KV, designed and shipped solo. |
| **[playday.om](https://playday.om)** | Site for a Muscat kids club, in English and Arabic. Mini games, an animated cat mascot, a guide for parents, and an agent layer (Markdown pages and an MCP server) so AI assistants can read it. No framework, on Cloudflare Workers. |
| **Ministry of Labour Forum 2026** | Registration, QR ticketing and gate check-in for a national multi-day forum. Hundreds of registrations and door scans on opening morning, zero errors. |

### Systems behind them

- **An AI agent system for daily operations.** Agents do a property team's listing and messaging
  work. Every incident becomes a rule they follow from then on, and hard guardrails block what they
  should never do.
- **Hybrid search with evals.** Vector and keyword search, combined and reranked on Workers. A test
  set built from real searches measures every change before it ships.
- **A free SEO toolkit.** Crawler, rank tracking, AI answer capture and the Search Console API,
  built to replace paid tools.
- **An app to replace a no-code portal.** A Flutter app on a Cloudflare backend, with proper access
  control and an audit trail. In progress.

### What I work with

- **Backend.** Python (12+ years) and Django, PostgreSQL, Redis, background and scheduled
  jobs, REST APIs, signed webhooks between services.
- **Edge and infrastructure.** TypeScript on Cloudflare Workers, D1, R2, KV, Queues and Durable
  Objects. Docker, gunicorn, Linux.
- **AI.** Agent systems with tool calling and MCP, guardrails, retrieval and reranking, evals that
  catch regressions, fine-tuning open models.
- **Web and growth.** Technical SEO, structured data, Search Console and GA4, fast pages at the
  edge, bilingual Arabic and English interfaces.
- **Keeping it up.** Sentry with per-commit release tagging, dead-man heartbeats on every
  scheduled job, backups I have restored on purpose to prove they work, one-command rollbacks.
- **Also.** Java 21, Spring Boot and Kafka (valuation-loop), Flutter, Vue and Nuxt, TensorFlow and
  OpenCV.

### Pinned below

- **ebm-lab**, above.
- **valuation-loop** is an event-driven backend in Java 21, Spring Boot, Kafka, Elasticsearch and
  Postgres. Leads are delivered reliably through a flaky adapter, with retries and a dead letter
  topic, and the evidence comes from real Land Registry data.
- **spine41** reads and writes the Spine 4.1 binary skeleton format in pure Python, and puts
  the file back together byte for byte. I wrote it because the published docs are two
  versions out of date.
- **anonsurf** sends all traffic on a Linux machine through Tor, starts atomically and rolls
  everything back if any step fails, so a firewall mistake can never lock you out.
- **discord-dice-worker** is a Discord slash command on a Cloudflare Worker. No bot server to keep
  online, signed requests, crypto randomness.
- **truffle** is an AI pet that only eats steps. A fine-tuned Gemma model, fed by your real
  step count.

Older: **Crack_detection** finds asphalt cracks in road photos and recommends the treatment.
**Practice_Solutions** is HackerRank in deliberately tiny Python. I was 18 and showing off.

---

Arabic · English · Türkçe · Русский &nbsp;|&nbsp; medooped020@gmail.com
