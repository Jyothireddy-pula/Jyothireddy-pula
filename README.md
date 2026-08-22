<!-- Banner (kept from your original) -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=blur&color=gradient&height=320&section=header&text=PULA%20JYOTHI%20REDDY&fontSize=85&fontAlignY=38&animation=fadeIn&desc=Software%20Engineer%20%7C%20GenAI%20Systems%20%7C%20Full-Stack%20Developer&descAlignY=65&descSize=18"/>
</p>

<p align="center">
  I build AI systems that actually run — agents, federated models, and the backends that hold them together.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jyothireddy-pula-5b3a01337/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:jyothireddypula@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Based%20in-Tirupati,%20India-555?style=flat"/>
  <img src="https://komarev.com/ghpvc/?username=Jyothireddy-pula&label=Profile%20views&color=0e75b6&style=flat"/>
</p>

---

CS undergrad at VIT-AP, currently in my third year. Most of my time goes into two things: making language-model agents reason and use tools reliably, and training models in settings where the data can't be centralized. I like problems where the interesting part is the *system* — how the pieces stay consistent, cheap, and correct once they're running, not just whether a notebook produces a nice number.

Right now I'm digging into multi-agent orchestration, federated / privacy-preserving training, and vision-language models.

<!--
  ↓ FILL THESE IN — this is what makes the README read as real rather than generated.
  For each featured project, add: a live demo link, the repo link, and ONE true metric
  (accuracy, latency, cost saved, users, dataset size). Don't invent numbers.
-->

## Featured work

### FedCareX — federated learning for clinical models
A setup that lets multiple hospitals train one shared diagnostic model without any patient
record ever leaving the building. Each site trains locally in PyTorch; only the weight
updates are aggregated, so raw data stays put. The hard part was keeping the global model
stable when every node sees a different data distribution.
`PyTorch` · `Federated Learning` · `Distributed training`
<!-- 🔗 Demo: … | Repo: … | Metric: e.g. "matched centralized accuracy within X% with zero data sharing" -->

### SynapseFlow-AI — an agentic GenAI framework
A multi-agent system where agents plan, call tools, and carry memory across steps to finish
real workflows instead of one-shot answers. Built it modular on purpose — new tools and new
agent roles drop in without touching the core loop.
`LLM agents` · `Tool use` · `Memory` · `Python`
<!-- 🔗 Demo / Repo / Metric -->

### GemmaSpatialX — vision + spatial reasoning
A vision-language model that reasons about *where* things are, not just *what* they are —
aimed at tasks where spatial relationships change the answer. Built on top of Gemma.
`Vision-Language` · `Multimodal` · `Gemma`
<!-- 🔗 Demo / Repo / Metric -->

### ZeroScale-API — serverless backend, scales to zero
An AWS backend that costs nothing when idle and scales up under load, with CI/CD so deploys
are one push. The focus was the boring-but-real stuff: cold-start behavior, cost, and
reliable pipelines.
`AWS` · `Serverless` · `CI/CD`
<!-- 🔗 Demo / Repo / Metric -->

## Also built

| Project | What it is |
|---|---|
| **Neurivox** | Multi-agent platform for automation and code intelligence, with a modular backend and service orchestration. |
| **Verto** | Gesture-controlled 3D / hologram interface — human–computer interaction driven by vision models. |
| **AirXfer** | Transfer files between devices with a hand gesture. |
| **PARAS** | Contributor on a large-scale platform system. |

<!-- Turn any of these bold names into links: [**Neurivox**](https://github.com/…/neurivox) -->

## Tools I reach for

**Languages** &nbsp; Python · Java · C
**AI / ML** &nbsp; PyTorch · LLM agents · Federated learning · Vision-language models
**Web** &nbsp; React · Next.js · Tailwind
**Backend** &nbsp; Node.js · FastAPI · MongoDB · MySQL
**Cloud / infra** &nbsp; AWS · Docker · Git · Linux · Raspberry Pi

## GitHub

<p align="center">
  <img src="https://raw.githubusercontent.com/Jyothireddy-pula/Jyothireddy-pula/main/profile-3d-contrib/profile-night-rainbow.svg" alt="Jyothi's 3D contribution calendar" width="100%"/>
</p>


<p align="center">
  <img height="170" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api?username=Jyothireddy-pula&show_icons=true&hide_border=true&theme=tokyonight&include_all_commits=true&count_private=true" />
  <img height="170" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=Jyothireddy-pula&layout=compact&hide_border=true&theme=tokyonight" />
</p>

<p align="center">
  <img height="170" src="https://streak-stats.demolab.com/?user=Jyothireddy-pula&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Jyothireddy-pula&bg_color=0d1117&color=00f7ff&line=00f7ff&point=ffffff&area=true&hide_border=true" />
</p>
## Open to

GenAI and agent-based work, backend / distributed systems, and research-leaning projects
where the goal is something that actually ships. If that's you, my inbox is open —
**jyothireddypula@gmail.com**.
