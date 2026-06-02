# 김세훈 | Sehun Kim

<img src="https://raw.githubusercontent.com/sehunkuim/sehunkuim/main/assets/main_profile_photo_ot1.jpg" width="360" alt="Sehun main photo" />
<img src="https://raw.githubusercontent.com/sehunkuim/sehunkuim/main/assets/sa_7d2039811.jpg" width="360" alt="LG Aimers Team Presentation" />

## About
- 서울과학기술대학교 인공지능응용학과 2학년
- President of **A.ING**, a 140-member AI club (2026)
- Founder and Team Lead of startup club team **EAO**


## Tech Stack
- Languages: Python, JavaScript, TypeScript
- AI/ML: scikit-learn, PyTorch (torch), TensorFlow, CatBoost, Hugging Face, vLLM
- Web/Backend: Next.js, Node.js, FastAPI, Genkit
- Data/Infra: Supabase, Docker, GitHub Actions
## Build & Leadership
- Built and launched the official A.ING website: https://aing.uk
- Built and launched the EAO project (Xinote): https://xinote.ai
- Built and deployed the partner organization website for **bunchang.co** (`Next.js`, `TypeScript`)

## Competition Highlights
| Year | Competition | Result | Detail |
|---|---|---:|---|
| 2026 | LG Aimers 8기 모델 경량화 (온라인) | 🥈 **2등 / 1,537명** | [Solution](https://github.com/sehunkuim/lg-aimers-8th-solution) |
| 2026 | 제3회 국민대학교 AI빅데이터 분석 경진대회 | 🥈 **2등 / 1,803명** | [Solution](https://github.com/sehunkuim/dacon-kookmin-comovement-solution) |
| 2026 | Kaggle ML 2차 (Audio Classification) | 🥇 **1등 / 86명** | [Solution](https://github.com/sehunkuim/kaggle-audio-classification-2026) |
| 2026 | Kaggle ML 1차 (Bike Rental Demand Forecast) | 🥇 **1등 / 90명** | [Solution](https://github.com/sehunkuim/kaggle-bike-rental-demand-forecast) |
| 2026 | 서울시립대 공개 AI 경진대회 (Track1) | 🥈 **2등 / 1,652명** | [Solution](https://github.com/sehunkuim/uos-soccer-dual-tower-solution) |

## Related Projects

### 1) Qwen VL 4B QLoRA Fine-tuning
- Model: `Qwen/Qwen3.5-4B` with QLoRA (rank 16, 2 epochs)
- Validation set: 100 samples (teacher = `qwen3.5-flash`)
- Quantitative gains:
  - ROUGE-L F1: **0.225 -> 0.260** (`+0.035`, win-rate 69%)
  - Token F1: **0.357 -> 0.413** (`+0.055`, win-rate 80%)
  - BLEU-1: **0.399 -> 0.462** (`+0.063`, win-rate 80%)
  - Hallucination heuristic: **32% -> 17%** (`-15pp`)

![Qwen QLoRA benchmark](https://raw.githubusercontent.com/sehunkuim/sehunkuim/main/assets/project1_qwen_qlora_metrics.png)

### 2) RAG + Reranker + Image-Routing Pipeline (OCR_VL23)
- Pipeline: retrieval -> router/reranker -> answerer with selective vision attachment
- Benchmark result: **101.0 / 102.0** aggregate score
- Scenario-level behavior validated with multi-intent queries (summary, image focus, QA, quiz, notes)

![RAG reranker benchmark](https://raw.githubusercontent.com/sehunkuim/sehunkuim/main/assets/project2_ocr_rag_reranker_benchmark.png)

### 3) Layout Postprocessing with IoU-based Matching (OCR_VL23)
- Applied IoU-based dedupe/matching in layout postprocessing and routing alignment
- Quality snapshot from benchmark logs:
  - Intent match: **100%**
  - Vision-match rule pass: **91.7%** (11/12)
  - No-hallucination rule pass: **100%**

![IoU layout quality](https://raw.githubusercontent.com/sehunkuim/sehunkuim/main/assets/project3_iou_layout_quality.png)

> Note: For `OCR_VL23` projects, only benchmark visuals/results are shown here. Source files are intentionally not uploaded.

## Main Repositories
- [LG Aimers 8th Final Solution](https://github.com/sehunkuim/lg-aimers-8th-solution)
- [Kookmin Comovement Solution](https://github.com/sehunkuim/dacon-kookmin-comovement-solution)
- [UOS Soccer Dual-Tower Solution](https://github.com/sehunkuim/uos-soccer-dual-tower-solution)
- [Kaggle Audio Classification 2026](https://github.com/sehunkuim/kaggle-audio-classification-2026)
- [Kaggle Bike Rental Demand Forecast](https://github.com/sehunkuim/kaggle-bike-rental-demand-forecast)
- [studio](https://github.com/sehunkuim/studio)
- [start-of-ai](https://github.com/sehunkuim/start-of-ai)

## References
- LG Aimers page: https://dacon.io/competitions/official/236673/overview/description
- Kookmin leaderboard: https://dacon.io/competitions/official/236619/leaderboard
- DACON home: https://dacon.io/

---
See each solution repository for full experiments, artifacts, and implementation details.
