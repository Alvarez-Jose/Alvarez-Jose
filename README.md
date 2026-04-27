# Hi, I'm Antonio 👋

M.S. Natural Language Processing candidate at **UC Santa Cruz** ($86K NLP Fellowship), with 3+ years building secure, large-scale software for the Department of Defense. Now focused on transformer fine-tuning, hybrid retrieval systems, and human-in-the-loop ML pipelines.

- 🎓 M.S. NLP @ UC Santa Cruz, expected Dec 2026
- 🛠️ Currently: Graduate Researcher on a human-rights NLP classification system (Arabic / English)
- 💼 Previously: Software Engineer @ Peraton — IAM platforms and data pipelines for 50,000+ DoD users
- 🔐 DoD Secret Clearance (currently inactive — left Peraton Dec 2025) · CompTIA Security+
- 📍 Santa Cruz, CA
- 🔗 [LinkedIn](https://linkedin.com/in/jose-alvarez-maciel) · 🤗 [Hugging Face](https://huggingface.co/jalva182) · ✉️ jalva182@ucsc.edu

## What I'm working on now

- **Human-rights NLP system** ([applied-nlp-multilabel-pipeline](https://github.com/Alvarez-Jose/applied-nlp-multilabel-pipeline)) — fine-tuning DeBERTa v3 for multilabel classification of Arabic/English news incidents; FastAPI + Streamlit pipeline with human-in-the-loop review. Source-available, restricted-use; data not included — see [NOTICE](https://github.com/Alvarez-Jose/applied-nlp-multilabel-pipeline/blob/main/NOTICE.md).
- **GRPO fine-tuning** — extending a teammate's GRPO training section on Llama-3-8B; published two LoRA adapters on Hugging Face

---

## Solo / lead work

Repositories I built and own end-to-end.

| Project | Stack | What it does |
|---|---|---|
| **[applied-nlp-multilabel-pipeline](https://github.com/Alvarez-Jose/applied-nlp-multilabel-pipeline)** | DeBERTa v3 · PyTorch · Streamlit · Sheets API | Human-in-the-loop multilabel NLP pipeline — DeBERTa v3 + margin-based reviewer routing + Sheets feedback loop. Applied in production to a private human-rights research project. Source-available, restricted-use; see [NOTICE.md](https://github.com/Alvarez-Jose/applied-nlp-multilabel-pipeline/blob/main/NOTICE.md). |
| **[nlp-ml-journey](https://github.com/Alvarez-Jose/nlp-ml-journey)** | Jupyter · PyTorch · HuggingFace · scikit-learn | Curated NLP / ML learning log — annotated notebooks working through transformers, retrieval, fine-tuning, and evaluation. |

**Trained models on Hugging Face**

| Model | Base | Method | Link |
|---|---|---|---|
| `jalva182/cli-agent-model` | `unsloth/llama-3-8b-Instruct` | GRPO + LoRA (TRL via Unsloth) | [🤗](https://huggingface.co/jalva182/cli-agent-model) |
| `jalva182/cli-agent-model-gpu1` | `unsloth/llama-3-8b-Instruct` | GRPO + LoRA (TRL via Unsloth) | [🤗](https://huggingface.co/jalva182/cli-agent-model-gpu1) |

These came out of the team-derived GRPO training work below.

---

## Team / collaborative work

Honest framing: these are repos where I contributed as a team member. I credit teammates by handle and link the work I actually did.

| Project | Role | Contribution |
|---|---|---|
| **[unsloth-grpo-project](https://github.com/Alvarez-Jose/unsloth-grpo-project)** | Extending [@Carson1829](https://github.com/Carson1829)'s GRPO training section | GUI/Tkinter wrapper, Docker + Northflank deployment, requirements/integration, training runs that produced the two Hugging Face adapters above |
| **[Visualtaggy/ragx](https://github.com/Visualtaggy/ragx)** | SemEval-2025 Task 8 (FinQA), team member | Evaluation + data role (non-code contributions). My fork has been removed; upstream is the canonical version. |
| **`Visualtaggy/project_cortex`** *(private team repo)* | Multi-agent desktop assistant | C code, Python ↔ GUI bridge, training-code improvements on top of [@Carson1829](https://github.com/Carson1829)'s work. Model artifacts published on Hugging Face (linked above). |

---

## Tech I work with

**Languages** — Python · Java · JavaScript · TypeScript · C · C++ · SQL
**ML / NLP** — PyTorch · HuggingFace Transformers · DeBERTa · BERT · spaCy · NLTK · scikit-learn · SentenceTransformers · TRL · Unsloth · PEFT / LoRA
**Methods** — Multilabel classification · Hybrid retrieval (BM25 + dense + HyDE) · GRPO / fine-tuning · Transfer learning · Human-in-the-loop ML
**Infra** — FastAPI · Flask · Spring Boot · React · Docker · Northflank · Streamlit · Linux · Git

## Selected experience

- **Software Engineer, Lead Associate** @ Peraton (Oct 2024 – Dec 2025) — Led Angular v13→v18 migration across DoD apps serving 10,000+ daily users; reduced load times by 35%+. Architected automated regression detection (Karma/Jasmine).
- **Software Engineer** @ Peraton (Jan 2023 – Oct 2024) — Led data migration for MP ICAM (50,000+ identity records) to Final Operational Capability. Built scalable IAM across web and desktop.

---

📫 **Open to:** ML / NLP Engineer · ML Research Engineer · LLM / Agent Engineer · Cleared SWE roles
🤝 **Reach me:** [LinkedIn](https://linkedin.com/in