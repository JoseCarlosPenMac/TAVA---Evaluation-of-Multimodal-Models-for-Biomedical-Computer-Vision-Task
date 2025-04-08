# 🧠 Multimodal Biomedical Vision-Language Architectures

## 📌 Project Overview

This project focuses on the **analysis and evaluation of multimodal architectures** that process 2D and 3D biomedical data—such as medical images and CT scans—to solve a variety of key computer vision tasks in the biomedical domain. These tasks include:

- **Classification**: Accuracy, F1-score, Precision-Recall  
- **Segmentation**: Intersection over Union (IoU), Dice coefficient  
- **Image Generation**: FID, SSIM  
- **Retrieval**: Mean Average Precision (mAP), Recall@K  
- **Grounding**: IoU, Precision  
- **Visual Question Answering (VQA)**: Exact Match, BLEU, METEOR  

The evaluation emphasizes the use of **multiple modalities** and explores innovative techniques for **multimodal fusion**, beyond those directly available in pretrained models.

---

## 🤖 Selected Models

**8 models** have been selected and analyzed. The full list includes:

1. **CLIP**: `openai/clip-vit-base-patch32`  
2. **PubMedCLIP**: `flaviagiammarino/pubmed-clip-vit-base-patch32`  
3. **ClipMD**: `Idan0405/ClipMD`  
4. **BLIP2**: `Salesforce/blip2-flan-t5-xl`  
5. **BiomedCLIP**: `microsoft/BiomedCLIP-PubMedBERT_256-vit_base_patch16_224`  
6. **GIT**: `microsoft/git-large`  
7. **SmolVLM**: `HuggingFaceTB/SmolVLM-256M-Instruct`  
8. **BiomedVLP**: `microsoft/BiomedVLP-BioViL-T`

These models are benchmarked across different datasets and tasks using relevant metrics.

---

## 📊 Evaluation Criteria

Models are compared based on:

- ✅ **Quantitative Performance** (task-specific metrics)  

---

## 🧬 Datasets

Biomedical datasets covering multiple modalities have been used, including **2D X-rays**, **3D CT scans**, and **textual data**. Publicly available datasets have been prioritized for reproducibility and accessibility.

---

## 🧪 Multimodal Innovation

The project includes experimentation with combining image and text modalities using various fusion techniques. While most models operate on dual-modality inputs, the design encourages the exploration of architectures capable of handling more than two modalities in future work.

---

## 🚀 Getting Started

To run and evaluate all models, open and execute the notebook:

```bash
models.ipynb
