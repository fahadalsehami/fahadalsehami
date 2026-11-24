# Fahad Alsehami

**AI engineer building clinical AI for mental health, end to end and in English and Arabic:** from raw voice and physiological signals, through speech recognition and multi-agent LLMs with a clinician in the loop, to the EHR. I also research how to certify what language models emit, and I build vision transformers on cell complexes.

M.S. in Bioinformatics, University of San Francisco. San Francisco Bay Area. About me: [fahadama.info](https://fahadama.info). Research: [fahadalsehami.github.io](https://fahadalsehami.github.io).

---

### Now: Founder & CEO, Medera (2024 – present)

AI co-therapy OS for behavioral health and primary care.

- **[Medera BH-ASR](https://huggingface.co/Medera/medera-bh-asr)**, a CPU-only English/Arabic clinical speech engine: VAD, TitaNet diarization, per-region language ID, and word-level fusion of Parakeet-TDT, Qwen3-ASR and Cohere Transcribe, with a Whisper verifier and a hallucination guard.
  - Lowest word error rate of 13 systems on English mock consultations: **11.02% on PriMock57**, level with Qwen3-ASR (p = 0.15) and ahead of Whisper large-v3 (13.55%).
  - **0 drug names inserted** under a medication prompt, where the prompted recognizer alone inserted 71.
  - **97.9%** of transcribed speech assigned to the speaker's true role (clinician or patient) on held-out single-channel consultations.
- **A 23-agent clinical LLM platform** that runs the work from the intake packet to the claim under a Care Orchestrator, with a clinician approving every step.
- **Real-time biomarkers in the browser:** webcam rPPG for heart rate and HRV, and about 70 vocal, physiological and linguistic markers mapped to 15 RDoC constructs.
- **EHR integration:** a SMART on FHIR app registered with Epic (FHIR R4), with notes, ICD-10/CPT codes and tasks filed into the practice's EHR.

### Research

| Work | What it shows |
| --- | --- |
| **Certify the Gate, Not the Generator** (sole author, manuscript, 2026) | Certified emission of LLM claims with Learn-then-Test and betting p-values: on 81,414 MedLFQA claims it keeps 77.8% at a 3% unsupported rate, with no violation in 100 splits. |
| **CELLO** (sole author, manuscript in preparation, 2026) | Vision transformers on oriented cell complexes with certified early exits: 89.54% on CIFAR-10 at about 0.1 GMACs, against at most 88.56% for ViT and HgVT (one seed so far); early exits cut MACs 2.18×. |
| **Perimeter** (sole author, research in progress, 2026) | Region tokens from an oriented cell complex beat patch tokens in a CPU pilot on Imagewoof, on all three seeds (64.7% vs 62.8% top-1), with 69% of the multiply-adds. |
| **[Signal & Symptom](https://alsehami.substack.com)** (essays, 2025 – ) | Building and verifying AI for behavioral health, including "The Epistemological Crisis of LLMs in Psychiatry". |

### Open work on this profile

| Repository | Focus |
| --- | --- |
| [Interactive-Rag](https://github.com/fahadalsehami/Interactive-Rag) | Retrieval-augmented clinical analysis: maps a presentation to NIMH RDoC constructs, retrieves passages from a Bedrock knowledge base, and has Claude write a cited analysis with a follow-up question. |
| [multi-tasks-learning](https://github.com/fahadalsehami/multi-tasks-learning) | Racial disparities in U.S. heart-disease mortality: CDC and census data joined by county, and a multi-task network prototype that classifies disease and estimates age at death. |
| [BoneAgePrediction](https://github.com/fahadalsehami/BoneAgePrediction) | Age estimation from adult pubic symphysis images: ImageNet VGG16 features with a logistic-regression classifier. |
| [fahadalsehami.github.io](https://github.com/fahadalsehami/fahadalsehami.github.io) | Source of my research page, with an oriented cell complex drawn live in the browser. |
| [fahadama.info](https://github.com/fahadalsehami/fahadama.info) | Source of my personal site. |

### Toolbox

- **Speech and signals:** ASR fusion, diarization, language ID, ONNX Runtime on CPU, rPPG and HRV, vocal features
- **LLMs and safety:** multi-agent orchestration, RAG, hallucination detection, conformal prediction, Learn-then-Test
- **ML research:** PyTorch, Hugging Face, topological deep learning, vision transformers
- **Bioinformatics:** NGS workflows (alignment, variant calling), R, SQL
- **Clinical data:** FHIR R4, SMART on FHIR, HL7 v2, ICD-10, CPT, HIPAA, SOC 2 Type II
- **Engineering:** Python, TypeScript, FastAPI, PostgreSQL, Docker, Azure, AWS, GCP

### Background

Co-founder and Chief Product Officer of **BOTIM**, the Middle East's first VoIP unicorn (90 million registered users). Grand Prize, **MIT Hacking Medicine** (New York, 2018). Grand Award Judge, **Regeneron ISEF** (2024).

**Contact:** [fahadama.info](https://fahadama.info) or [LinkedIn](https://linkedin.com/in/alfahadama).
