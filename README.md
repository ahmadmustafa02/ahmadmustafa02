<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24&height=180&section=header&text=Ahmad%20Mustafa&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full%20Stack%20AI%20Engineer%20%7C%20Undergraduate%20Researcher&descAlignY=58&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.herokuapp.com?font=Space+Mono&weight=700&size=18&duration=3000&pause=1000&color=FF6B2B&center=true&vCenter=true&width=700&height=40&lines=Building+AI-Agent+Security+Systems;Publishing+Empirical+AI%2FSecurity+Research;AI+Lead+%40+AWS+Student+Builder+Group+-+CUI" />

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-FF6B2B?style=flat-square&logo=firefoxbrowser&logoColor=white)](https://ahmadmustafa.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ahmadmustafabutt)
[![Email](https://img.shields.io/badge/ahmadmustafabutt.dev%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ahmadmustafabutt.dev@gmail.com)
[![GitHub](https://img.shields.io/badge/ahmadmustafa02-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ahmadmustafa02)

</div>

<br/>

## `01` About Me

```ts
const ahmad = {
  role       : "Full Stack AI Engineer & Undergraduate Researcher",
  university : "COMSATS University Islamabad (2023 - 2027)",
  leadership : "AI Lead @ AWS Student Builder Group, CUI",
  focus      : ["AI-Agent Security", "Applied LLM Engineering", "Empirical Research"],
  currently  : "Building production agent-security tooling & publishing research",
  contact    : "ahmadmustafabutt.dev@gmail.com"
};
```

I build **production AI systems** and back them with **rigorous, measured research** — from adversarial evaluation labs that stress-test AI agents, to empirical studies on vulnerability introduction in AI-authored code. My work spans full-stack engineering, agentic system design, and applied security research, with a bias toward reporting real numbers over vibes.

<br/>

## `02` Experience

<table>
<tr>
<td width="50%" valign="top">

**🏢 Placentek** — *Full Stack Developer*
`Jul 2026 – Present`
Built a production RAG-based AI shopping assistant (Next.js, OpenAI, Redis) for a WooCommerce store, grounding LLM responses in live inventory to eliminate hallucinated pricing. Implemented JWT auth and optimized Postgres queries (~35% faster APIs), and shipped a reusable React/Tailwind component library (+20 Lighthouse points, -12% load time).

</td>
<td width="50%" valign="top">

**🤖 Arbisoft** — *AI-Focused SWE Intern*
`Aug 2026 – Oct 2026`
Completed an 8-week AI-focused program covering full-stack fundamentals and agentic AI system design (skills, memory, hooks, MCP). Designed and shipped **Warrant** as a self-proposed capstone — a provenance-based tool-authorization security layer for AI agents, approved by mentor review.

</td>
</tr>
</table>

**🎓 AI Lead — AWS Student Builder Group, COMSATS University Islamabad**
Leading AI-focused initiatives, workshops, and builder programs for the student community at CUI.

<br/>

## `03` Featured Projects

### 🛡️ Warrant
*TypeScript · Groq AI · npm (published packages)*

Open-source security layer that stops AI agents from being hijacked by malicious instructions hidden in the content they process — attacking the agent in a sandbox to find weaknesses, then enforcing strict controls over its authorized actions.

- CLI proxy + framework-free TypeScript guard intercepting every sensitive tool call, enforcing permissions derived only from the user's original request
- Measured adversarial lab: 60 tuned attacks across 6 families, 24 benign tasks, 15 held-out
- **60/60 attack-stop** with guard active (vs. 17/60 hijacked with guard off) · **15/15** on a held-out attack set never used to tune rules
- Published as `@warrant-lab/guard` and `@warrant-lab/cli` on npm, with a live evaluation dashboard and full threat-model docs

### 🔍 CodePulse
*React · TypeScript · Node.js · Express.js · PostgreSQL · Groq AI*

Production-style AI-powered GitHub App reviewing pull requests through an event-driven pipeline, defended against prompt injection, with its own maintained evaluation harness.

- Async, queue-based review pipeline (BullMQ/Redis) with HMAC-verified webhooks, retry/dead-letter handling, and full multi-tenant isolation
- Pre-LLM prompt-injection defense gate (embeddings + logistic classifier) with an adversarial evaluation harness tracked on a live security dashboard
- Same-day comparative model evaluation (50-case labeled benchmark) to lock the production model on precision/false-positive tradeoffs
- Trace Viewer exposing per-job, step-by-step execution timelines with automatic fault localization

### 🧪 LabCrew
*Next.js · TypeScript · PostgreSQL · BullMQ · Flutter*

Self-hosted operations platform for research labs — a human-gated multi-agent weekly pipeline, structured research-data collection, and AI-assisted document-to-schema workflows.

- Four-stage agent pipeline (signal collection → evidence scoring → human-approved drafting → automated reporting), with strict human-approval gates before any AI-drafted action reaches a student
- Structured research-data pipeline (collect, validate, visualize, analyze) with statistical outlier flagging and privacy floors protecting small-cohort data
- Flutter field-collection companion app for offline capture, plus a review-gated document-to-schema extraction workflow
- Structural multi-tenant isolation verified with a dedicated test suite covering session and bearer-token access paths

<br/>

## `04` Research

**Software Security During AI-Assisted Software Development: Dependency Vulnerability Introduction in AI-Agent-Authored Pull Requests**
Empirical study of 17,727 merged pull requests finding AI coding agents introduce known-vulnerable dependencies at roughly double the odds of human developers (OR = 2.06), with a self-identified and corrected clustering artifact reported as a methodological caution.

**Generalization and Explainability of AI-Based Software Vulnerability Detection Across Projects**
Empirical comparison of ML and DL vulnerability detectors across nine open-source projects, finding predictive performance degrades far more than explanation stability under cross-project distribution shift, with Holm-Bonferroni corrected hypothesis testing throughout.

<br/>

## `05` Tech Stack

<div align="center">

**Languages** &nbsp;|&nbsp; JavaScript (ES6+) · TypeScript · Python
**Frontend** &nbsp;|&nbsp; React.js · Next.js · Flutter · Tailwind CSS · HTML5/CSS3 · Jest
**Backend** &nbsp;|&nbsp; Node.js · Express.js · RESTful APIs · WebSockets · JWT · BullMQ
**Databases** &nbsp;|&nbsp; PostgreSQL · MongoDB · MySQL · Redis
**AI / Agentic** &nbsp;|&nbsp; Groq API · OpenAI API · Gemini API · Anthropic Claude API · LangChain · MCP · Multi-Agent Orchestration
**DevOps & Tools** &nbsp;|&nbsp; Git · GitHub Actions · Vercel · Docker · Azure · Postman · Figma

<br/>

<img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,flutter,tailwind,html,css&theme=dark" />
<br/>
<img src="https://skillicons.dev/icons?i=nodejs,express,postgres,mongodb,mysql,redis&theme=dark" />
<br/>
<img src="https://skillicons.dev/icons?i=git,github,vercel,docker,azure,figma,postman&theme=dark" />

</div>

<br/>

## `06` Open Source & Achievements

- Merged open-source contributions into **Pipedream** (11.6k★, 5.7k forks, acquired by Workday) — a bug fix restoring Adobe PDF Services extraction reliability, and a new Jira Download Attachment action ([PR #21505](https://github.com/PipedreamHQ/pipedream/pull/21505), [PR #21452](https://github.com/PipedreamHQ/pipedream/pull/21452))
- 🥈 Silver tier — Google Antigravity AI Seekho 2026 hackathon
- 🎓 Certifications: Machine Learning Specialization (DeepLearning.AI) · Introduction to Model Context Protocol (Anthropic) · Google UX Design Professional Certificate

<br/>

<div align="center">

*"Ship features that work. Measure the ones that matter."*

<br/>

[![Portfolio](https://img.shields.io/badge/View_Portfolio-FF6B2B?style=for-the-badge&logo=firefoxbrowser&logoColor=white)](https://ahmadmustafa.me)
&nbsp;
[![Get In Touch](https://img.shields.io/badge/Get_In_Touch-FF6B2B?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ahmadmustafabutt.dev@gmail.com)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24&height=100&section=footer" width="100%"/>

</div>
