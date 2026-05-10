<div align="center">

# Hi there! 👋 I'm **Sehun** (@sehunkuim)

**LG Aimers 8기** · On-device **EXAONE** 경량화 · **🥈 2위** 솔루션

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sehunkuim)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sehun7079@naver.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)

<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-111?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

<br/>

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=sehunkuim&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=sehunkuim&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

<table>
<tr>
<td width="50%" valign="top">

### 📌 Highlights

| | |
|:---|:---|
| **Contest** | LG Aimers **8기** — 모델 경량화 (DACON) · **2nd place** |
| **Model** | EXAONE **4.0 ~1.2B** · on-device 타깃 |
| **Stack** | TRL **DPO** + PEFT **LoRA**, **llmcompressor** GPTQ, **vLLM** 벤치 |

**Certificates / scores** 등은 필요 시 위 표를 채워 넣으면 됩니다.

</td>
<td width="50%" valign="top">

### 🔬 Research / Engineering interests

- **Alignment**: Direct Preference Optimization (**DPO**), LoRA (**r=64**, **α=128**), pairwise JSONL (Ultrafeedback 등)
- **Compression**: **FP8** GPTQ, **W8A8** / **W4A16** 스킴, calibration **512×2048**, MANTA / KMMLU-Redux / GSM8K 믹스
- **Inference**: **vLLM** TPS·정확도 로깅, **SM120+**에서 Int8 경로 한계 시 **FP8** 폴백
- **Eval**: KMMLU, MMLU-Redux, reasoning·non-reasoning 듀얼 트랙

</td>
</tr>
</table>

---

### 📋 Education & Experience

| 기간 | 기관 · 역할 | 내용 | 관련 링크 |
|:---:|:---|:---|:---|
| 🎯 **2026** | **LG Aimers 8기** · 온라인 해커톤 | EXAONE **경량화**: DPO 정렬 → GPTQ(**FP8**) 양자화 → **512 샘플** 캘리브레이션(MANTA·GSM8K·KMMLU·다국어·툴 스키마) → **vLLM** 대회 벤치 | [📝 기술 노트](https://github.com/sehunkuim/studio/blob/main/docs/LG_AIMERS_8th_Solution_Notes.md) · [DACON 대회](https://dacon.io/competitions/official/236673/overview/description) |
| 🎓 *TBD* | *학교 · 전공 (직접 수정)* | *학위 과정 / GPA / 동아리 등* | — |

---

### 🏆 LG Aimers — Solution snapshot

| 항목 | 요약 |
|:---|:---|
| **DPO** | TRL `DPOTrainer`, **781 steps**, 손실 ~**0.68→0.59**, 선호 정확도 로그 ~**0.76** 구간 |
| **Quant** | `GPTQModifier` **FP8** (`block_size` **128**, damp **0.01**); 실험: **W8A8**, **W4A16**(256×512 캘리브) |
| **Calibration** | **512** 샘플 · **max_len 2048** · `manta_plain/reasoning`, `gsm`, `kmmlu`, `teleia_es`, `wikitext_long`, `agent_tools` |
| **Bench** | `benchmark.py`: KMMLU·MMLU-Redux 등 + TPS / invalid-rate / 토큰 분포 CSV |

**Repo:** [`sehunkuim/studio`](https://github.com/sehunkuim/studio) — 상세 마크다운은 [`docs/LG_AIMERS_8th_Solution_Notes.md`](https://github.com/sehunkuim/studio/blob/main/docs/LG_AIMERS_8th_Solution_Notes.md)

---

### 📰 Featured in the News · Official

- [LG Aimers 공식 사이트](https://www.lgaimers.ai/)
- [LG 보도자료 — 경량화 해커톤](https://www.lg.co.kr/media/release/29342)
- [AI타임스 — LG 온디바이스 AI 경량화 해커톤](https://www.aitimes.com/news/articleView.html?idxno=208841)
- [EXAONE 4.0 기술 리포트 (arXiv)](https://arxiv.org/abs/2507.11407)

---

<div align="center">

✨ *Profile README — 마음에 드는 문구·학력·LinkedIn URL은 직접 수정해서 사용하세요.*

</div>
