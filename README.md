# Hi, I'm Joshua Stein 👋

## 🔬 About Me

I'm a **PhD Candidate in Chemistry and Chemical Biology** with a specialized skillset in **lipid nanoparticle (LNP) chemistry**—from compound identification and formulation development through preclinical studies. My research bridges classical pharmaceutical chemistry with modern AI/ML techniques to accelerate drug delivery platform design.

I'm passionate about leveraging computational tools to solve complex problems in drug discovery, formulation science, and metabolomics.

---

## 🧬 Scientific Projects

### [AgentLNP - Lipid Nanoparticle Formulation AI](https://github.com/JoshuaBStein/AgentLNP)

**AI-powered knowledge extraction pipeline for LNP research literature**

This project demonstrates advanced **Natural Language Processing (NLP)** applied to pharmaceutical sciences. The pipeline uses local Large Language Models (LLMs via MLX) to perform **Named Entity Recognition (NER)** and **Relationship Extraction** on complex research PDFs, converting unstructured scientific text into structured knowledge graphs.

**Key ML Concepts:**
- **Domain-specific NER** with custom ontology engineering for lipid chemistry
- **Evidence-based validation** to eliminate hallucinations and ensure 100% source fidelity
- **Graph consolidation** for multi-document knowledge synthesis
- Zero-shot learning with instruction-tuned models (Gemma 3 27B)

**Scientific Impact:** Automates literature curation for LNP formulation parameters, accelerating rational design cycles.

---

### [ChEMBL Kinase QSAR Pipeline](https://github.com/JoshuaBStein/ChEMBL-Kinase-QSAR)

**Predicting lipophilicity of cancer pathway inhibitors using molecular descriptors**

This end-to-end **Quantitative Structure-Activity Relationship (QSAR)** pipeline targets the PI3K/AKT/mTOR signaling pathway—critical in cancer biology. The project showcases supervised machine learning applied to drug discovery, transforming chemical formulas into predictive models.

**Key ML Concepts:**
- **Feature engineering** from molecular formulas using regex-based elemental parsing
- **Decision Tree Regression** with hyperparameter optimization via Grid Search CV
- **Model interpretability** through sensitivity analysis and complexity-RMSE trade-off curves
- Achieved **R² = 0.87** on lipophilicity prediction

**Scientific Impact:** Enables rapid in silico screening of kinase inhibitors for optimal ADME properties before synthesis.

---

### [Metabolomics HPC Pipeline](https://github.com/JoshuaBStein/Metabolomics-HPC)

**High-throughput metabolic pathway analysis on Rutgers Amarel HPC cluster**

This project applies **unsupervised learning** and **pathway enrichment algorithms** to mass spectrometry data from prostate cancer macrophage models. It demonstrates scalable bioinformatics workflows for multi-omics data.

**Key ML Concepts:**
- **Peak detection and alignment** using adaptive algorithms (OptiLCMS)
- **Mummichog pathway enrichment** - a probabilistic algorithm that maps m/z features to metabolic networks
- **Dimensionality reduction** for high-dimensional MS data
- Batch processing on HPC infrastructure for reproducible science

**Scientific Impact:** Identified dysregulated metabolic pathways in tumor-associated macrophages, revealing potential therapeutic targets.

---

## 🤖 AI/ML Engineering Projects

**[Slack AI Worker Bot](https://github.com/JoshuaBStein/Slack-AI-Bot)** - Distributed vision-language model system using MLX and Gemma 3 27B with broker-worker architecture for scalable multimodal processing (image analysis, document QA, and file generation).

**[YouTube to Instagram Reel Converter](https://github.com/JoshuaBStein/YouTube-Reel-Converter)** - Content automation pipeline with ML-powered face tracking (OpenCV/MediaPipe), Whisper ASR for captions, edge-TTS voice synthesis, and Manim/Remotion integrations for programmatic B-roll generation.

**[LyricLingQ](https://github.com/JoshuaBStein/LyricLingQ)** - Language learning tool leveraging API orchestration to auto-import song lyrics into spaced-repetition systems, demonstrating practical ML integration for educational workflows.

---

## 📫 Let's Connect

- 💼 [LinkedIn](in/joshua-stein-3401b7129)

---
