<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=cylinder&color=0:0d1117,50:161b22,100:0d1117&height=140&section=header&text=Üzeyir%20İsmail%20Bahtiyar&fontSize=38&fontColor=e6edf3&animation=fadeIn&fontAlignY=55&desc=Full-stack%20engineer%20—%20I%20ship%20the%20app%20and%20run%20the%20infrastructure%20under%20it&descAlignY=78&descSize=14&descColor=8b949e" />
</div>

<br />

```typescript
const uzeyir = {
  location:  "Istanbul, Turkey 🇹🇷 (UTC+3)",
  currently: "Sole engineer @ Lema Dental — 3 production apps + the infra they run on",
  building:  "Yezuri — CRM & marketing platform, founded and built solo",
  stack:     ["Next.js", "TypeScript", "Go", "PocketBase", "Docker Swarm", "Rust"],
  workflow:  "Claude Code via Orca — several agents in parallel across isolated worktrees",
  openTo:    ["collabs", "OSS contributions", "interesting problems"],
};
```

## What I actually do

I build products end to end and don't stop at the application layer. Most full-stack work ends at a `git push` to a managed platform — mine goes further: I run my own production infrastructure on Docker Swarm with Traefik, TLS, and monitoring across every service I ship.

I also work AI-first, and I mean it structurally rather than as autocomplete. I run Claude Code through Orca so several coding agents work on isolated git worktrees at the same time. That's the reason one engineer can carry three production applications and their infrastructure.

Five years in, and the part I still like most is the ambiguous brief — the one where nobody has written down what the software should be yet.

## 85 repositories, most of them live

That number isn't a boast about volume — plenty of people have 85 abandoned repos. It's the output of two specific decisions.

The first is that I run several coding agents in parallel across isolated git worktrees instead of working one branch at a time. The second is that I host everything myself on Docker Swarm rather than paying per project, so spinning up a new service costs me minutes and nothing else.

Together they mean shipping something is cheap enough that I actually do it. A few are described below. Ask me about any of the rest.

## Selected work

**Yezuri** — CRM and digital marketing platform. Founded the company, built the whole product solo: lead management, persona analysis, and analytics. Includes a conversational layer where users create leads and invoices through chat instead of forms. Two years in and still shipping to it.

**Self-hosted deployment platform** — Dokploy on Docker Swarm. Service orchestration, Traefik reverse proxy and routing, automated TLS issuance and renewal, container deploys, centralised logging and monitoring.

**3D treatment planning application** — Visualises a proposed course of medical treatment as a 3D animation and tracks it through to completion. The hard part wasn't the rendering; it was making a clinical plan legible to someone with no clinical training.

**Automated content agent** — A production pipeline that drafts SEO-structured posts, generates the accompanying imagery, and publishes them. Built as distinct inspectable stages rather than one prompt.

**[uzeyiros](https://github.com/uzeyirrr/uzeyiros)** — A hobby operating system in Rust on x86-64. Where I go to understand what sits underneath the frameworks I use every day.

## What's behind the private repos

Fifty-odd of the repositories here are private — client systems and internal platforms I can't open source. A sample of what's in there, since the titles alone won't tell you:

- **A payment system** handling transactions for a clinic group
- **A lead-data pipeline** that scrapes and structures business listings from Google Maps into a CRM
- **A multi-domain site system** — one codebase serving many domains, each with its own content and routing
- **A programmatic landing page generator** for campaign pages, built for volume
- **A server management dashboard** for the infrastructure I run
- **A localisation service** that keeps a multi-language product in sync
- **A full product across three repositories** — Astro frontend, C# API, admin panel
- **A review aggregation system** pulling and normalising ratings from several sources

Happy to walk through any of them in a conversation.

## Stack

**Frontend**
`Next.js` `React` `Astro` `TypeScript` `JavaScript` `Tailwind CSS` `HTML` `CSS`

**Backend**
`Go` `Node.js` `PocketBase` `PHP` `Laravel` `REST API` `OpenAPI / Scalar`

**Database**
`PostgreSQL` `MySQL` `MongoDB` `Redis` `PocketBase`

**DevOps & Infrastructure**
`Docker` `Docker Swarm` `Dokploy` `Traefik` `Nginx` `GCP` `Linux` `Bash` `SSH` `Git` `GitHub Actions`

**AI & Automation**
`Claude Code` `Orca (ADE)` `Cursor` `Anthropic API` `OpenAI API` `LangChain` `prompt engineering` `workflow automation`

**Systems**
`Rust` `Go`

**Mobile**
`iOS` `Android`

<details>
<summary><b>Also — CMS, marketing, and design</b></summary>

<br />

**CMS & Web** · `WordPress` `WooCommerce` `Yoast SEO` `WP Fastest Cache` `Polylang`

**Marketing & Analytics** · `Meta Ads` `Google Ads` `Google Analytics` `GTM` `SEO`

**Design & 3D** · `Figma` `Blender` `Adobe Photoshop` `Illustrator` `Premiere Pro` `After Effects`

Before engineering became the whole job, I ran ad campaigns and built client sites. It still shows up as useful context whenever I work on something customer-facing.

</details>

## Currently exploring

- **Agentic workflows** — multi-step orchestration, human-in-the-loop gates, and where handing control to a model stops being a good idea
- **Backend tooling** with Laravel and Scalar/OpenAPI for structured API design
- **AI-powered** content and automation pipelines
- **3D** with Blender for product and UI concepts

## Stats

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=uzeyirrr&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true&hide_title=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=uzeyirrr&layout=compact&langs_count=6&theme=github_dark&hide_border=true&hide_title=true" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=uzeyirrr&theme=github-dark-blue&hide_border=true" />
</div>

## Reach me

<a href="mailto:uzeyirismailbahtiyar@gmail.com">uzeyirismailbahtiyar@gmail.com</a> &nbsp;·&nbsp;
<a href="https://linkedin.com/in/üzeyirismail">LinkedIn</a>
