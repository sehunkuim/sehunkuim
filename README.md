# Hi there! 👋 I'm **Sehun**

**LG Aimers 8기** · On-device **EXAONE** 경량화 · **🥈 2nd place**

> 이 파일은 공개 저장소 **`sehunkuim/sehunkuim`** 의 `README.md`입니다. GitHub은 이 내용을 [**프로필 Overview**](https://github.com/sehunkuim) 상단에 표시합니다. (별도 설정 메뉴 없음)

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sehunkuim)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sehun7079@naver.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-222?style=flat-square&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=sehunkuim&show_icons=true&theme=tokyonight&hide_border=true&cache_seconds=86400)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=sehunkuim&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&cache_seconds=86400)

---

## 📌 Highlights

| Category | Details |
| :-- | :-- |
| **Contest** | LG Aimers **8기** — DACON 모델 경량화 · **2nd place** |
| **Model** | EXAONE **4.0 · ~1.2B** (on-device 타깃) |
| **Stack** | TRL **DPO** + PEFT **LoRA** · **llmcompressor** GPTQ · **vLLM** 벤치마크 |

## 🔬 Interests

- **Alignment**: DPO / LoRA (**r=64**, **α=128**), pairwise preference data (Ultrafeedback 등)
- **Compression**: **FP8** GPTQ, **W8A8** · **W4A16**, calibration 설계 (**512 × 2048**)
- **Inference**: vLLM throughput & accuracy, **SM120+**에서 Int8 한계 시 **FP8** 폴백
- **Evaluation**: KMMLU, MMLU-Redux, reasoning / non-reasoning 듀얼 트랙

---

## 📋 Education & Experience

| Period | Organization | Summary | Links |
| :--: | :-- | :-- | :-- |
| **2026** | **LG Aimers 8기** · 온라인 해커톤 | DPO 정렬 → GPTQ(**FP8**) → **512-shot** calibration (MANTA, GSM8K, KMMLU-Redux, ES, WikiText, tool-schema) → **vLLM** contest benchmarks | [기술 노트](https://github.com/sehunkuim/studio/blob/main/docs/LG_AIMERS_8th_Solution_Notes.md) · [DACON](https://dacon.io/competitions/official/236673/overview/description) |

---

## 🏆 LG Aimers — Solution snapshot

| Topic | Summary |
| :-- | :-- |
| **DPO** | TRL `DPOTrainer`, **781 steps**, loss ~**0.68 → 0.59**, preference-accuracy logs up to ~**0.76** |
| **Quant** | `GPTQModifier` **FP8** (block **128**, damp **0.01**); also tried **W8A8**, **W4A16** (256×512 calib) |
| **Calibration** | **512** samples · **max_len 2048** · buckets: MANTA plain/reasoning, GSM8K, KMMLU-Redux, TELEIA/FLORES ES, WikiText, agent tools |
| **Bench** | Custom `benchmark.py`: KMMLU, MMLU-Redux, + TPS / invalid-rate / token histograms |

**Write-up:** [`sehunkuim/studio` — `docs/LG_AIMERS_8th_Solution_Notes.md`](https://github.com/sehunkuim/studio/blob/main/docs/LG_AIMERS_8th_Solution_Notes.md)

---

## 📰 Press & official links

- [LG Aimers](https://www.lgaimers.ai/)
- [LG press release (KR)](https://www.lg.co.kr/media/release/29342)
- [AI Times — on-device lightweighting hackathon (KR)](https://www.aitimes.com/news/articleView.html?idxno=208841)
- [EXAONE 4.0 report — arXiv](https://arxiv.org/abs/2507.11407)

---

### Pinned repos

[**studio**](https://github.com/sehunkuim/studio) · [**start-of-ai**](https://github.com/sehunkuim/start-of-ai)
