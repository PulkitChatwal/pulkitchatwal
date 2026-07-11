<!-- ============ CUSTOM ANIMATED HEADER (hand-authored SVG) ============ -->
<p align="center">
  <img src="./header.svg" width="100%" alt="Pulkit Chatwal — AI Engineer"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/model-pulkit--chatwal--v1-6dd5ed?style=flat-square&labelColor=0c1430"/>
  <img src="https://img.shields.io/badge/status-shipping-22c55e?style=flat-square&labelColor=0c1430"/>
  <img src="https://img.shields.io/badge/license-open__to__work-1a6fb5?style=flat-square&labelColor=0c1430"/>
  <img src="https://komarev.com/ghpvc/?username=PulkitChatwal&style=flat-square&color=1a6fb5&label=loads"/>
</p>

---

>  **Model Card for `pulkit-chatwal-v1`**
> A dual-capability system that *researches* and *ships*. Publishes peer-reviewed NLP and deploys production AI products end-to-end. Not a chatbot &mdash; the one who fine-tunes and serves them.

<table>
<tr><td><b> Developer</b></td><td>Self-directed, RGIPT (IDD B.Tech + M.Tech, CSE &amp; AI)</td></tr>
<tr><td><b> Base role</b></td><td>AI Engineer &amp; Founding Engineer @ <a href="https://www.voxxagent.ai/">Voxx Agent</a> (Srinergy.ai)</td></tr>
<tr><td><b> Modalities</b></td><td>Text · Speech · Multimodal (image + text)</td></tr>
<tr><td><b> Languages</b></td><td>English, Hindi &mdash; plus multilingual NLP research (Arabic, Indic, Spanish)</td></tr>
<tr><td><b> Checkpoints</b></td><td>9 peer-reviewed publications · production voice agent · 3+ shipped projects</td></tr>
</table>

---

###  &nbsp;`intended_use` &mdash; what I'm good for

```yaml
primary_tasks:
  - fine-tuning open-weight LLMs        # LoRA / QLoRA / DPO / quantization
  - building RAG systems                # hybrid RAG, graph RAG, citation-grounded
  - serving models in production        # FastAPI, vLLM, TGI, Triton — latency & cost aware
  - LLM safety & evaluation             # benchmarks, LLM-as-judge, refusal analysis
  - voice AI agents                     # STT / TTS / telephony, live with real clients

out_of_scope: [ "buzzword-only theory", "notebooks that never ship" ]
```

---

###  &nbsp;`training_data` &mdash; where the signal came from

| Source | Signal |
|---|---|
|  **Srinergy.ai** | Founding engineer of **Voxx Agent** — voice AI live across enterprise clients; ERP/CRM integrations; 9,000+ call campaign |
|  **9 Publications** | Financial safety · multilingual NLP · multimodal alignment · causal reasoning |
|  **Research** | LLM safety benchmarks, federated multimodal affect, jurisdiction-aware legal alignment |
|  **Hackathons** | 2× Smart India Hackathon Winner (Govt. of India) |

---

###  &nbsp;`evaluation` &mdash; benchmarks (a.k.a. the stack)

<p>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/vLLM-FF6F61?style=flat-square"/>
<img src="https://img.shields.io/badge/Triton-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/RAG_·_GraphRAG-0F4C81?style=flat-square"/>
<img src="https://img.shields.io/badge/LoRA_·_QLoRA-8A2BE2?style=flat-square"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
</p>

<div align="center">
<img height="150" src="https://github-readme-stats.vercel.app/api?username=PulkitChatwal&show_icons=true&count_private=true&hide_border=true&title_color=6dd5ed&icon_color=1a6fb5&text_color=8aa0c0&bg_color=00000000"/>
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=PulkitChatwal&layout=compact&hide_border=true&title_color=6dd5ed&text_color=8aa0c0&bg_color=00000000&langs_count=7"/>
</div>

---

###  &nbsp;`deployments` &mdash; models in production

<table>
<tr>
<td width="25%" align="center"><a href="https://www.voxxagent.ai/"><b> Voxx Agent</b></a><br/><sub><code>live · enterprise</code></sub><br/>Voice AI agent</td>
<td width="25%" align="center"><a href="https://github.com/PulkitChatwal/ChristianMind-AI"><b> ChristianMind AI</b></a><br/><sub><code>RAG · FastAPI</code></sub><br/>Grounded + judged</td>
<td width="25%" align="center"><a href="https://twogetherme.vercel.app/"><b> TwoGether</b></a><br/><sub><code>live demo</code></sub><br/>Full-stack app</td>
<td width="25%" align="center"><a href="https://github.com/PulkitChatwal/PaperCast"><b> PaperCast</b></a><br/><sub><code>NLP · audio</code></sub><br/>Papers &rarr; audio</td>
</tr>
</table>

---

###  &nbsp;`citations` &mdash; selected publications

```bibtex
@inproceedings{chatwal2026beyond,
  title  = {Beyond Refusal: Measuring Safety Erosion in Multi-Turn Financial Jailbreaks},
  author = {Chatwal, Pulkit and others},
  note   = {Under Review, EMNLP 2026}
}
@inproceedings{chatwal2026qraft,
  title  = {QRAFT: QLoRA Retrieval-Augmented Fine-Tuning for Causal Span Extraction},
  author = {Bajpai, M. and Chatwal, Pulkit and others},
  booktitle = {LREC 2026}, note = {4th / 9 — FinCausal 2026}
}
@inproceedings{chatwal2025cultura,
  title  = {Cultura-Arabica: Arabic Cultural Awareness in LLMs via LoRA},
  author = {Chatwal, Pulkit and Mishra, S. K.},
  booktitle = {ArabicNLP 2025}, note = {2nd place — PalmX}
}
```
<sub> full list &rarr; <a href="https://scholar.google.com/">Google Scholar</a></sub>

---

###  &nbsp;`limitations` &mdash; known behaviours

```diff
+ ships research to production instead of leaving it in a notebook
+ reads the paper, then writes the working code
- context window overflows when a problem is genuinely interesting
- non-deterministic sleep schedule during an active fine-tune
```

---

###  &nbsp;`how_to_use` &mdash; inference endpoint

<p align="center">
<a href="mailto:21cs2027@rgipt.ac.in"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://scholar.google.com/"><img src="https://img.shields.io/badge/Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white"/></a>
<a href="https://www.voxxagent.ai/"><img src="https://img.shields.io/badge/Voxx_Agent-0F4C81?style=for-the-badge&logo=rocket&logoColor=white"/></a>
</p>

<div align="center">

![snake](https://raw.githubusercontent.com/PulkitChatwal/PulkitChatwal/output/github-contribution-grid-snake-dark.svg)

<sub><code>pulkit-chatwal-v1</code> &mdash; open to work · responds fast · low latency</sub>

</div>
