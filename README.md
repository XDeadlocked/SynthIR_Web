---
title: "SynthIR @ SIGIR 2026"
collection: pages
permalink: /SIGIR2026Workshop-SynthIR
author_profile: false
---

<div align='center'>
  <h2> Special Interest Group on Information Retrieval </h2>
</div>

<div align='center' style="vertical-align:middle">
  <h2> SIGIR 2026 <a href="https://sigir.org/">(https://sigir.org/)</a> </h2>
</div>

<div align='center'>
  <h2> Workshop on </h2>
  <h2> SynthIR: The First Workshop on Synthetic Content in Information Retrieval Ecosystems (SIGIR 2026) </h2>
  <img src="https://github.com/XDeadlocked/SynthIR_Web/blob/main/logo.png?raw=true" alt="workshop logo" />
</div>

<meta name="og:image" content="logo.png" />
<meta name="og:description" content="SynthIR: The First Workshop on Synthetic Content in Information Retrieval Ecosystems (SIGIR 2026)" />
<meta name="description" content="SIGIR 2026 Workshop SynthIR: The First Workshop on Synthetic Content in Information Retrieval Ecosystems (SIGIR 2026)" />

SynthIR focuses on the system-level implications of AI-generated content in retrieval ecosystems, emphasizing evaluation validity, provenance, user trust, and human-centered design in mixed (synthetic + human-authored) information environments.

[[Submission Site]](https://openreview.net/group?id=ACM.org/SIGIR/2026/Workshop/SynthIR)

## SEED: Benchmark for Provenance Tracing in Sequential Deepfake Facial Edits
<div align='center'>
  <img src="https://github.com/XDeadlocked/SynthIR_Web/blob/main/competition.jpg?raw=true" alt="competition logo" />
</div>

We introduce SEED, the first large-scale benchmark for sequential visual provenance tracing in facial imagery. SEED contains 91,526 images built from highquality real face datasets (FFHQ and CelebAMask-HQ) and edited by
diffusion-based pipelines. Unlike prior benchmarks that focus on isolated manipulations, SEED targets sequential editing: each sample is produced by applying
one to four attribute edits in order, where later operations may partially overwrite
earlier traces. 

[[Competition Site]](https://www.codabench.org/competitions/15351/)

[[Paper Site]](https://arxiv.org/abs/2604.10522)

> [!NOTE]
> The submission deadline has been extended to **6 June 2026**. We encourage participants to publicly release their code to support reproducibility and community reuse. We will issue certificates for the **Best Paper Award**, **Most Creative Approach Award**, and **Community Contribution Award**.

## News
- 28/2/2026 - Workshop homepage is now available.
- 10/4/2026 - Competition is now available.
- 26/5/2026 - Submission deadline has been extended to 6 June 2026.
- 29/6/2026 - Notification and camera-ready dates have been updated.

## Important Dates
Please note: Deadlines are at 11:59 p.m. of the stated deadline date [Anywhere on Earth](https://time.is/Anywhere_on_Earth)

- **Competition deadline:** 21 May 2026
- **Submission deadline:** ~~30 May 2026~~ 6 June 2026  
- **Notification:** ~~22 June 2026~~ 29 June 2026  
- **Camera-ready:** ~~29 June 2026~~ 4 July 2026  

## Abstract
The proliferation of AI-generated content is fundamentally altering the information ecosystems in which retrieval systems operate. Search engines, recommender systems, and retrieval-augmented generation pipelines increasingly function in mixed environments where synthetic and human-authored content are tightly interwoven, raising system-level challenges for information retrieval. SynthIR provides a forum to examine these implications with emphasis on reflection, evaluation, and human-centered system design, and to foster community discussion that may inform future evaluation efforts and shared tasks.

## Themes and Discussion Tasks
**Focus areas** include evaluation validity, provenance/attribution, grounding and trust signals, and user interaction in AIGC-aware IR systems.

**Micro shared tasks** (lightweight analytical exercises):
- **Task A: AIGC in ranked retrieval results** — ranking placement, perceived quality, provenance signals, and evaluation gaps.
- **Task B: AIGC in retrieval-augmented generation (RAG)** — factual alignment, attribution quality, hallucination patterns, and trust signals.
- **Task C: Model provenance and attribution** — provenance availability, attribution granularity, uncertainty representation, and impact on ranking/trust.
- **Case study:** sequential AIGC edits and provenance challenges in IR.

## Submission Guidelines
[[Submission Site]](https://openreview.net/group?id=ACM.org/SIGIR/2026/Workshop/SynthIR)

Full research papers must describe original work that has not been previously published (except on pre-print servers, see below for details), not accepted for publication elsewhere, and not simultaneously submitted or currently under review in another journal or conference (including the other tracks of SIGIR 2026). Please note that concurrent submissions are a violation of the [ACM Policy on Authorship](https://www.acm.org/publications/policies/new-acm-policy-on-authorship). The SIGIR 2026 program chairs will refer any such violations to the [Ethics & Plagiarism Committee](https://www.acm.org/publications/publications-board-committees) of the ACM Publications Board.

Submissions of full research papers must be in English, in PDF format, and be at most 4 pages (including figures, tables, proofs, appendixes, acknowledgments, and any content except references) in length, with unrestricted space for references, in the current ACM two-column conference format. Suitable LaTeX, Word, and Overleaf templates are available from the [ACM Website](https://www.acm.org/publications/proceedings-template) (use “sigconf” proceedings template for LaTeX and the Interim Template for Word). ACM’s CCS concepts and keywords are required for review.

For LaTeX, the following should be used:

\documentclass[sigconf,natbib=true,anonymous=true]{acmart}

## Workshop Format and Schedule

SynthIR is planned as a highly interactive half-day workshop, structured to move from shared context setting to task-driven analysis and participant-driven discussion.

**Date:** July 24, 2026

| Time | Paper | PDF |
|---|---|---|
| 13:30–13:40 | Welcome | — |
| 13:40–13:55 | **EMMM, Explain Me My Model! Explainable Multi-Dimension Multi-Level Multi-Strategy Chatbot Detection**<br>Angela Yifei Yuan, Haoyi Li, Soyeon Caren Han, and Christopher Leckie<br>SIGIR 2026 SynthIR Workshop | [PDF](https://github.com/XDeadlocked/SynthIR_Web/blob/main/papers/emmm-explain-me-my-model.pdf) |
| 13:55–14:10 | **Faithful or Findable? Evaluating LLM-Generated Metadata for RDF Dataset Search**<br>Riccardo Terrenzi and Serkan Ayvaz<br>SIGIR 2026 SynthIR Workshop | [PDF](https://github.com/XDeadlocked/SynthIR_Web/blob/main/papers/faithful-or-findable.pdf) |
| 14:10–14:25 | **HybridQPP: Scaling Synthetic Evaluation Signals through Pointwise and Pairwise LLM Alignment**<br>Cezary Golecki, Aleksander Wawer, and Paweł Zawistowski<br>SIGIR 2026 SynthIR Workshop | [PDF](https://github.com/XDeadlocked/SynthIR_Web/blob/main/papers/hybridqpp.pdf) |
| 14:25–14:40 | **OpenCoderRank: Personalized Technical Assessments with Generative AI**<br>Hridoy Sankar Dutta, Sana Ansari, Swati Kumari, and Shounak Ravi Bhalerao<br>SIGIR 2026 SynthIR Workshop | [PDF](https://github.com/XDeadlocked/SynthIR_Web/blob/main/papers/opencoderrank.pdf) |
| 14:40–15:30 | Coffee break | — |
| 15:30–15:45 | **Relevant but Hard to Recover: An Empirical Study of AIGC Rewrites in Ranked Retrieval**<br>Ding Wu<br>SIGIR 2026 SynthIR Workshop | [PDF](https://github.com/XDeadlocked/SynthIR_Web/blob/main/papers/relevant-but-hard-to-recover.pdf) |
| 15:45–16:00 | **Silent Failures in Multimodal Agentic Search: A Diagnostic Taxonomy and Cross-Judge Evaluation**<br>Zhengxian Wu, Junjie Gao, and Kai Yang<br>SIGIR 2026 SynthIR Workshop | [PDF](https://github.com/XDeadlocked/SynthIR_Web/blob/main/papers/silent-failures.pdf) |
| 16:00–16:15 | **Towards Vision-Free CIR: Attribute-Augmented Scoring and LLM-Based Reranking for Zero-Shot Composed Image Retrieval**<br>Ryotaro Shimada, Yu-Chieh Lin, Yuji Nozawa, Youyang Ng, Osamu Torii, and Yusuke Matsui<br>SIGIR 2026 SynthIR Workshop | [PDF](https://github.com/XDeadlocked/SynthIR_Web/blob/main/papers/towards-vision-free-cir.pdf) |
| 16:15–16:30 | **When Do LLM-Generated Note Cards Help Retrieval and Reranking?**<br>Shanmin Sun and Xinlu Lin<br>SIGIR 2026 SynthIR Workshop | [PDF](https://github.com/XDeadlocked/SynthIR_Web/blob/main/papers/when-do-llm-generated-note-cards-help.pdf) |

## Organizing Team

| <img src="https://www.unr.edu/main/images/colleges-schools/engineering/cse/profiles/Ping-Liu.jpg" width="160" /> | <img src="https://www.zdzheng.xyz/images/mstile-150x150.webp" width="160" /> | <img src="https://scholar.googleusercontent.com/citations?view_op=medium_photo&user=OFlBSEEAAAAJ&citpid=8" width="160" /> | <img src="https://xinyu-au.github.io/images/profile.png" width="160" /> |
| :-: | :-: | :-: | :-: |
| [Ping Liu](https://pinglmlcv.github.io/pingliu264/), University of Nevada, USA | [Zhedong Zheng](https://zdzheng.xyz), University of Macau, China | [J. Shane Culpepper](https://jsc.github.io/), University of Queensland, Australia | [Xin Yu](https://xinyu-au.github.io/), Adelaide University, Australia |

## Contact
For questions, please contact the organizers. (Replace this line with your preferred contact email / form.)

## Workshop Citation
```bibtex
@inproceedings{SynthIR2026,
  title     = {SynthIR: Workshop on Synthetic Content in Information Retrieval Ecosystems},
  booktitle = {Proceedings of the 49th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2026) Workshops},
  author = {Ping Liu, Zhedong Zheng, J. Shane Culpepper, Xin Yu},
  year      = {2026}
}
```

## Competition & Benchmark Citation
```bibtex
@misc{hoi2026seedlargescalebenchmarkprovenance,
      title={SEED: A Large-Scale Benchmark for Provenance Tracing in Sequential Deepfake Facial Edits}, 
      author={Mengieong Hoi and Zhedong Zheng and Ping Liu and Wei Liu},
      year={2026},
      eprint={2604.10522},
      archivePrefix={arXiv},
      primaryClass={cs.CR},
      url={https://arxiv.org/abs/2604.10522}, 
}
```
