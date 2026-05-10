<div align="center">

# Hi there! 👋 I'm **Sehun**

<h3>LG Aimers 8기 · On-device EXAONE 경량화 · 🥈 2nd place</h3>

<p>
<a href="https://github.com/sehunkuim"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="mailto:sehun7079@naver.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://www.linkedin.com/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</p>

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"/>
<img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA"/>
<img src="https://img.shields.io/badge/vLLM-222?style=flat-square&logoColor=white" alt="vLLM"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
</p>

<p>
<img src="https://github-readme-stats.vercel.app/api?username=sehunkuim&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&cache_seconds=86400" alt="GitHub Stats" width="49%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sehunkuim&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&cache_seconds=86400" alt="Top Languages" width="49%"/>
</p>

</div>

<br/>

## 📌 Highlights

| Category | Details |
|:--|:--|
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
|:--:|:--|:--|:--|
| **2026** | **LG Aimers 8기** · 온라인 해커톤 | DPO 정렬 → GPTQ(**FP8**) → **512-shot** calibration (MANTA, GSM8K, KMMLU-Redux, ES, WikiText, tool-schema) → **vLLM** contest benchmarks | [기술 노트](https://github.com/sehunkuim/studio/blob/main/docs/LG_AIMERS_8th_Solution_Notes.md) · [DACON](https://dacon.io/competitions/official/236673/overview/description) |

<!-- 학력 행은 필요 시 아래처럼 추가하세요.
| ... | University · Major | ... | — |
-->

---

## 🏆 LG Aimers — Solution snapshot

| Topic | Summary |
|:--|:--|
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

<div align="center">

### Pinned repos

[**studio**](https://github.com/sehunkuim/studio) · [**start-of-ai**](https://github.com/sehunkuim/start-of-ai)

<sub>프로필 README 저장소: <code>sehunkuim/sehunkuim</code> · LinkedIn URL은 본인 링크로 교체하세요.</sub>

</div>
