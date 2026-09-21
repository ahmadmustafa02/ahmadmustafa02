<!-- ============================== HEADER ============================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:FF6B2B,100:FF2E63&height=220&section=header&text=Ahmad%20Mustafa&fontSize=64&fontColor=ffffff&fontAlignY=38&desc=Full%20Stack%20AI%20Engineer%20%20%E2%80%A2%20%20AI%20Security%20Researcher&descSize=18&descAlignY=60&animation=fadeIn" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=2800&pause=900&color=FF6B2B&center=true&vCenter=true&width=720&height=45&lines=I+build+AI+agents+that+can't+be+hijacked.;Shipping+LLM+products+to+production.;Publishing+research+on+AI-agent+security." alt="Typing SVG" />

<br/>

<a href="https://ahmadmustafa.me"><img src="https://img.shields.io/badge/Portfolio-ahmadmustafa.me-FF6B2B?style=for-the-badge&logo=googlechrome&logoColor=white"/></a>
<a href="https://linkedin.com/in/ahmadmustafabutt"><img src="https://img.shields.io/badge/LinkedIn-ahmadmustafabutt-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:ahmadmustafabutt.dev@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20Hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>

</div>

<br/>

<!-- ============================== ABOUT ============================== -->
## <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28"> &nbsp;whoami

```ts
const ahmad = {
  role       : "Full Stack AI Engineer",
  alsoKnownAs: "Undergraduate Researcher, AI-Agent Software Security",
  building   : ["Agent security layers", "RAG systems", "AI developer tooling"],
  currently  : {
    job      : "Full Stack Developer @ Placentek",
    program  : "AI-Focused SWE Intern @ Arbisoft",
    community: "AI Lead @ AWS Student Builder Group, CUI",
    studying : "BS Computer Science @ COMSATS Islamabad (2027)",
  },
  obsessedWith: "Making LLMs useful, measurable, and safe to trust",
  contact     : "ahmadmustafabutt.dev@gmail.com",
};
```

<br/>

<!-- ============================== FEATURED PROJECTS ============================== -->
## 🔥 &nbsp;Featured Work

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ [Warrant](https://github.com/ahmadmustafa02/warrant)
**Provenance-based tool authorization for AI agents.**

Stops agents from being hijacked by malicious instructions hidden in the content they read. Warrant attacks your agent in a sandbox to find weak spots, then enforces permissions derived *only* from the user's original request.

- 🔒 CLI proxy + framework-free TypeScript guard intercepts every sensitive tool call
- 🧪 Adversarial lab: 60 tuned attacks, 6 families, 24 benign tasks
- 📊 **60/60** stopped with guard on (vs **17/60** hijacked with it off)
- 🎯 **15/15** on a held-out set never used for tuning
- 📦 Published as installable npm packages

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white"/> <img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=anthropic&logoColor=white"/>

</td>
<td width="50%" valign="top">

### 🔍 [CodePulse](https://github.com/ahmadmustafa02/codepulse)
**AI GitHub App that reviews PRs and grades itself.**

An event-driven review pipeline with prompt-injection defense and a maintained evaluation harness that tracks its own review quality over time.

- ⚙️ Async BullMQ/Redis pipeline, HMAC-verified webhooks, retries + dead-letter queue
- 🏢 Full multi-tenant isolation across GitHub App installations
- 🧱 Pre-LLM injection gate (embeddings + logistic classifier) with live security dashboard
- 📐 50-case labeled benchmark to pick the model on precision, not recall alone
- 🧭 Trace Viewer with step-by-step timelines and automatic fault localization

<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/> <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>

</td>
</tr>
</table>

<br/>

<!-- ============================== RESEARCH ============================== -->
## 🔬 &nbsp;Research

> **Do AI coding agents ship vulnerable code more often than humans?** I measure it.

<table>
<tr>
<td width="50%" valign="top">

#### 📄 [Dependency Vulnerability Introduction in AI-Agent-Authored Pull Requests](https://github.com/ahmadmustafa02)

Empirical study of **17,727 merged PRs**. AI coding agents introduce known-vulnerable dependencies at roughly **double the odds** of human developers (**OR = 2.06**). Includes a self-identified and corrected clustering artifact, reported openly as a methodological caution.

</td>
<td width="50%" valign="top">

#### 📄 [Generalization & Explainability of AI Vulnerability Detection Across Projects](https://github.com/ahmadmustafa02)

ML vs DL vulnerability detectors across **nine open-source projects**. Under cross-project distribution shift, predictive performance degrades far more than explanation stability. Holm-Bonferroni corrected hypothesis testing throughout.

</td>
</tr>
</table>

<br/>

<!-- ============================== EXPERIENCE ============================== -->
## 💼 &nbsp;Experience

```diff
+ Placentek                                     Full Stack Developer     Jul 2026 > Present
  ├─ Production RAG shopping assistant (Next.js, OpenAI, Redis) grounded in live inventory
  ├─ JWT auth + PostgreSQL indexing, ~35% faster average API responses
  └─ React + Tailwind component library, +20 Lighthouse, 12% faster loads

+ Arbisoft                                      AI-Focused SWE Intern    Aug 2026 > Oct 2026
  ├─ 8-week program: full-stack fundamentals + agentic AI (skills, memory, hooks, MCP)
  ├─ Shipped Warrant as a self-proposed, mentor-approved capstone
  └─ Multi-agent orchestration, supervisor/worker patterns, MCP server/client, tool-call tracing

+ AWS Student Builder Group @ CUI               AI Lead                  Sep 2026 > Present
  ├─ Run workshops and hands-on sessions on LLMs, AI tooling, and cloud
  └─ Mentor student builders from idea to working project
```

<br/>

<!-- ============================== OPEN SOURCE ============================== -->
## 🌍 &nbsp;Open Source & Wins

<div align="center">

<a href="https://github.com/PipedreamHQ/pipedream/pull/21505"><img src="https://img.shields.io/badge/Pipedream-PR%20%2321505%20Merged-8957E5?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://github.com/PipedreamHQ/pipedream/pull/21452"><img src="https://img.shields.io/badge/Pipedream-PR%20%2321452%20Merged-8957E5?style=for-the-badge&logo=github&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Google%20Antigravity%20AI%20Seekho%202026-Silver%20Tier-C0C0C0?style=for-the-badge&logo=google&logoColor=white"/>

</div>

- 🐛 Restored Adobe PDF Services extraction reliability in **Pipedream** (11.6k⭐, acquired by Workday)
- ✨ Added a new **Jira Download Attachment** action to Pipedream
- 🥈 Silver tier at **Google Antigravity AI Seekho 2026**

<br/>

<!-- ============================== TECH STACK ============================== -->
## 🧰 &nbsp;Tech Arsenal

<div align="center">

**Languages & Frontend**
<br/>
<img src="https://skillicons.dev/icons?i=ts,js,python,react,nextjs,flutter,tailwind,html,css,jest&theme=dark&perline=10" />

**Backend & Data**
<br/>
<img src="https://skillicons.dev/icons?i=nodejs,express,postgres,mongodb,mysql,redis&theme=dark" />

**DevOps & Tools**
<br/>
<img src="https://skillicons.dev/icons?i=git,github,githubactions,docker,azure,vercel,postman,figma&theme=dark" />

<br/>

**AI & Agentic Systems**
<br/>
<img src="https://img.shields.io/badge/Anthropic%20Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white"/>
<img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/Multi--Agent%20Orchestration-FF6B2B?style=for-the-badge&logo=robotframework&logoColor=white"/>
<img src="https://img.shields.io/badge/RAG-0D1117?style=for-the-badge&logo=databricks&logoColor=FF6B2B"/>
<img src="https://img.shields.io/badge/BullMQ-E0234E?style=for-the-badge&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white"/>

</div>

<br/>

<!-- ============================== STATS ============================== -->
## 📈 &nbsp;GitHub in Numbers

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=ahmadmustafa02&show_icons=true&hide_border=true&bg_color=0D1117&title_color=FF6B2B&icon_color=FF6B2B&text_color=C9D1D9&rank_icon=github&count_private=true" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ahmadmustafa02&layout=compact&hide_border=true&bg_color=0D1117&title_color=FF6B2B&text_color=C9D1D9&langs_count=6" />

<img src="https://streak-stats.demolab.com?user=ahmadmustafa02&hide_border=true&background=0D1117&ring=FF6B2B&fire=FF6B2B&currStreakLabel=FF6B2B&sideLabels=C9D1D9&dates=8B949E&currStreakNum=FFFFFF&sideNums=FFFFFF" width="70%"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ahmadmustafa02&bg_color=0D1117&color=C9D1D9&line=FF6B2B&point=FFFFFF&area=true&area_color=FF6B2B&hide_border=true" width="100%"/>

</div>

<br/>

<!-- ============================== CERTS ============================== -->
## 🎓 &nbsp;Education & Certifications

<div align="center">

| | |
|:---|:---|
| 🏛️ **COMSATS University Islamabad** | BS Computer Science, 2023 to 2027 |
| 🧠 **Machine Learning Specialization** | DeepLearning.AI |
| 🔌 **Introduction to Model Context Protocol** | Anthropic |
| 🎨 **Google UX Design Professional Certificate** | Google |

</div>

<br/>

<!-- ============================== FOOTER ============================== -->
<div align="center">

### 🤝 Let's build something that's smart *and* safe.

*Open to AI engineering roles, research collaborations, and interesting agent-security problems.*

<br/>

<a href="https://ahmadmustafa.me"><img src="https://img.shields.io/badge/View%20Portfolio-FF6B2B?style=for-the-badge&logo=googlechrome&logoColor=white"/></a>
&nbsp;
<a href="mailto:ahmadmustafabutt.dev@gmail.com"><img src="https://img.shields.io/badge/Get%20In%20Touch-0D1117?style=for-the-badge&logo=gmail&logoColor=FF6B2B"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF2E63,50:FF6B2B,100:0D1117&height=120&section=footer" width="100%"/>

</div>
