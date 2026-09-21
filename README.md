<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D0D0D,100:2B2B2B&height=220&section=header&text=Ahmad%20Mustafa&fontSize=52&fontColor=D4AF37&fontAlignY=42&desc=Full%20Stack%20AI%20Engineer%20%C2%B7%20Agent%20Security%20Researcher&descAlignY=62&descSize=17&descColor=F5F1E8&animation=fadeIn" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Georgia&size=19&duration=3200&pause=900&color=D4AF37&center=true&vCenter=true&width=680&lines=Building+AI+systems+that+survive+adversarial+pressure;Attacking+my+own+agents+before+someone+else+does;COMSATS+%E2%80%9927+%7C+Researching+under+Dr.+Basit+Raza)](https://git.io/typing-svg)

<br/>

<a href="mailto:ahmadmustafabutt.dev@gmail.com"><img src="https://img.shields.io/badge/-Email-2B2B2B?style=flat-square&logo=gmail&logoColor=D4AF37" /></a>
<a href="https://linkedin.com/in/ahmadmustafabutt"><img src="https://img.shields.io/badge/-LinkedIn-2B2B2B?style=flat-square&logo=linkedin&logoColor=D4AF37" /></a>
<a href="https://github.com/ahmadmustafa02"><img src="https://img.shields.io/badge/-GitHub-2B2B2B?style=flat-square&logo=github&logoColor=D4AF37" /></a>
<a href="https://ahmadmustafa.me"><img src="https://img.shields.io/badge/-Portfolio-2B2B2B?style=flat-square&logo=safari&logoColor=D4AF37" /></a>

</div>

<br/>

### About

I build production AI systems, then try to break them &mdash; and I write up what happens either way. My work sits at the intersection of full-stack engineering and applied security research: RAG pipelines, multi-agent orchestration, and the guardrails that keep an AI agent from being hijacked by its own inputs. Currently a 7th-semester CS student at COMSATS University Islamabad, working under Dr. Basit Raza on empirical software-security research.

<br/>

### Currently

<table>
<tr>
<td width="70"><img src="./assets/placentek.png" width="46"/></td>
<td><b>Full Stack Developer</b> &mdash; Placentek <sub>Jul 2026 &ndash; Present</sub><br/>Shipping a production RAG shopping assistant and a reusable component library used across the app.</td>
</tr>
<tr>
<td width="70"><img src="./assets/aws-sbg.png" width="46"/></td>
<td><b>AI Lead</b> &mdash; AWS Student Builder Group, CUI <sub>Sep 2026 &ndash; Present</sub><br/>Running workshops and mentoring students on applied AI and cloud development.</td>
</tr>
</table>

<br/>

### Featured Work

<table>
<tr>
<td width="50%" valign="top">

**Warrant** &mdash; *TypeScript, Groq AI, npm*
<br/>
A security layer that stops AI agents from being hijacked by malicious instructions hidden in the content they process &mdash; by attacking the agent in a sandbox first, then locking down what it's allowed to do.

- 60/60 attacks stopped with the guard active, vs. 17/60 hijacked with it off
- 15/15 on a held-out attack set never used to tune the rules
- Published as [`@warrant-lab/guard`](https://npmjs.com) and [`@warrant-lab/cli`](https://npmjs.com) on npm

[Repo →](https://github.com/ahmadmustafa02/warrant)

</td>
<td width="50%" valign="top">

**CodePulse** &mdash; *React, Node.js, PostgreSQL, Groq AI*
<br/>
An AI-powered GitHub App that reviews pull requests through an event-driven pipeline, with a defense gate against prompt-injection sitting in front of the model.

- Queue-based pipeline (BullMQ/Redis) with HMAC-verified webhooks and full tenant isolation
- Embeddings + logistic-regression gate catching prompt-injection before it reaches the LLM
- Trace Viewer for step-by-step, fault-localized debugging of every review job

[Repo →](https://github.com/ahmadmustafa02/codepulse)

</td>
</tr>
</table>

<br/>

### Experience

<table>
<tr><td width="70"><img src="./assets/arbisoft.png" width="46"/></td>
<td>

**AI-Focused Software Engineering Intern** &mdash; Arbisoft &nbsp;·&nbsp; *Aug &ndash; Oct 2026*
Self-proposed and shipped **Warrant** as the program's capstone; worked through full-stack fundamentals into multi-agent orchestration and MCP server/client integration.

</td></tr>
<tr><td width="70"><img src="./assets/placentek.png" width="46"/></td>
<td>

**Full Stack Developer** &mdash; Placentek &nbsp;·&nbsp; *Jul 2026 &ndash; Present*
RAG shopping assistant grounded in live inventory data; JWT auth and indexed Postgres queries cutting API response time ~35%; a component library that lifted Lighthouse scores by 20 points.

</td></tr>
<tr><td width="70"><img src="./assets/aws-sbg.png" width="46"/></td>
<td>

**AI Lead** &mdash; AWS Student Builder Group, CUI &nbsp;·&nbsp; *Sep 2026 &ndash; Present*
Designing and delivering sessions on AI development and cloud tooling; mentoring student builders through their own AI projects.

</td></tr>
</table>

<br/>

### Research

**Software Security During AI-Assisted Development: Dependency Vulnerability Introduction in AI-Agent-Authored PRs**
Empirical study of 17,727 merged pull requests &mdash; AI coding agents introduce known-vulnerable dependencies at roughly double the odds of human developers (OR = 2.06), with a self-identified clustering artifact reported as a methodological caution. [GitHub →](https://github.com/ahmadmustafa02)

**Generalization and Explainability of AI-Based Vulnerability Detection Across Projects**
Cross-project comparison of ML/DL vulnerability detectors across nine open-source projects, with Holm-Bonferroni corrected testing throughout &mdash; predictive performance degrades far more than explanation stability under distribution shift. [GitHub →](https://github.com/ahmadmustafa02)

<br/>

### Open Source

<img src="./assets/pipedream.png" width="22" valign="middle"/> &nbsp;Merged contributions into **Pipedream** (11.6k★, 5.7k forks, acquired by Workday) &mdash; a fix restoring Adobe PDF Services extraction, and a new Jira *Download Attachment* action.
&nbsp;&nbsp;[PR #21505](https://github.com/PipedreamHQ/pipedream/pull/21505) &nbsp;·&nbsp; [PR #21452](https://github.com/PipedreamHQ/pipedream/pull/21452)

Silver tier &mdash; Google Antigravity AI Seekho Hackathon 2026.

<br/>

### Stack

<p align="left">
<img src="https://skillicons.dev/icons?i=js,ts,react,nextjs,nodejs,express,py,postgres,mongodb,redis,docker,git,github,vercel,azure,figma&theme=dark" />
</p>

<sub>AI & Agentic &mdash; Groq API · OpenAI API · Gemini API · Anthropic Claude API · LangChain · Model Context Protocol · Multi-Agent Orchestration</sub>

<br/>
<br/>

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=ahmadmustafa02&show_icons=true&theme=transparent&hide_border=true&title_color=D4AF37&icon_color=D4AF37&text_color=F5F1E8&count_private=true" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=ahmadmustafa02&theme=transparent&hide_border=true&ring=D4AF37&fire=D4AF37&currStreakLabel=D4AF37&sideLabels=F5F1E8&currStreakNum=F5F1E8&sideNums=F5F1E8&dates=F5F1E8" height="165"/>
</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2B2B2B,100:0D0D0D&height=90&section=footer" width="100%"/>

</div>
