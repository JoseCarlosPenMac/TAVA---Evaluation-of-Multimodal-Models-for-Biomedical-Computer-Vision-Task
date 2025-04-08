# 🧠 Multimodal Biomedical Vision-Language Architectures

## 📌 Project Overview

This project focuses on the **analysis and evaluation of multimodal architectures** that process 2D and 3D biomedical data—such as medical images and CT scans—to solve a variety of key computer vision tasks in the biomedical domain. These tasks include:

- **Classification**: Accuracy, F1-score, Precision-Recall  
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
- **F1-score prioritization**: Instead of relying solely on accuracy as the primary evaluation metric, we chose to prioritize the F1-score, particularly for the positive class. This decision is based on the fact that, in the medical domain, it is more critical to correctly identify positive cases, minimizing false negatives — cases where a condition is present but the model fails to detect it.

    Accuracy can be misleading in imbalanced datasets, which are common in medical applications. For example, if only 10% of patients have a disease, a model that always predicts "healthy" would achieve 90% accuracy but completely fail to detect any true cases. Therefore, we use the F1-score, which is the harmonic mean of precision and recall, offering a more balanced view of the model's performance, especially for the minority (positive) class.

---

## 🧬 Datasets

Biomedical datasets covering multiple modalities have been used, including **2D X-rays**, **3D CT scans**, and **textual data**. Publicly available datasets have been prioritized for reproducibility and accessibility.

---

## 🧪 Multimodal Innovation

The project includes experimentation with combining image and text modalities using various fusion techniques. While most models operate on dual-modality inputs, the design encourages the exploration of architectures capable of handling more than two modalities in future work.

---

## 🚀 Getting Started

To run and evaluate all models, follow these steps:

1. **Create the environment** by running:
    ```bash
    conda env create -f requirements.yml
    ```
    This will create a new environment with all the necessary dependencies.

2. **Activate the environment** using:
    ```bash
    conda activate clip_torch_env
    ```
    This will activate the environment where all the required libraries are installed.

3. **Run the notebook** containing all the models to evaluate:
    ```bash
    Models.ipynb
    ```
    This notebook includes all the models and tasks that need to be executed for the analysis and evaluation.

---

## ✍️ Authors

This project was developed by:

- Mario Jerez Tallón  
- Francisco García Gómez  
- José Carlos Penalva Maciá

Master's in Artificial Intelligence  
**University of Alicante**
