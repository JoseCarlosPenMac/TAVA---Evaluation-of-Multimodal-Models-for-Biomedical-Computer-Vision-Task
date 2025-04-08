# 🧠 Multimodal Biomedical Vision-Language Architectures

## 📌 Project Overview

This project focuses on the **analysis and evaluation of multimodal architectures** that process 2D and 3D biomedical data—such as medical images and CT scans—to solve a variety of key computer vision tasks in the biomedical domain. These tasks include:

- **Classification**: Accuracy, F1-score, Precision-Recall  
- **Segmentation**: Intersection over Union (IoU), Dice coefficient  
- **Image Generation**: FID, SSIM  
- **Retrieval**: Mean Average Precision (mAP), Recall@K  
- **Grounding**: IoU, Precision  
- **Visual Question Answering (VQA)**: Exact Match, BLEU, METEOR  
- **Molecular Description Generation**: ROUGE, BLEU, Molecular Similarity  

The evaluation emphasizes the use of **multiple modalities** and explores innovative techniques for **multimodal fusion**, beyond those directly available in pretrained models.

---

## 🤖 Selected Models

**8 models** have been selected and analyzed. The full list includes:

1. `openai/clip-vit-base-patch32`  
2. `flaviagiammarino/pubmed-clip-vit-base-patch32`  
3. `Idan0405/ClipMD`  
4. `Salesforce/blip2-flan-t5-xl`  
5. `microsoft/BiomedCLIP-PubMedBERT_256-vit_base_patch16_224`  
6. `microsoft/git-large`  
7. `HuggingFaceTB/SmolVLM-256M-Instruct`  
8. `microsoft/BiomedVLP-BioViL-T`

These models are benchmarked across different datasets and tasks using relevant metrics.

---

## 📊 Evaluation Criteria

Models are compared based on:

- ✅ **Quantitative Performance** (task-specific metrics)  
- 🧪 **Dataset Coverage**  
- 🧠 **Model Innovation**  
- ⚙️ **Inference Time**  
- 🧾 **Code Availability & Usability**  
- 📦 **Model Size**

---

## 🧬 Datasets

Biomedical datasets covering multiple modalities have been used, including 2D X-ray, 3D CT scans, textual descriptions, and molecular data. Publicly available datasets are prioritized.

---

## 🧪 Multimodal Innovation

The project includes experimentation with combining data from multiple modalities (image, text, molecular) using novel fusion techniques. The use of **more than two modalities** in inference or learning pipelines is specifically explored and positively valued.

---

## 🚀 Getting Started

> 🛠️ Instructions for environment setup, model loading, and running experiments will be added soon.

---

## 📄 License

This project is released under the MIT License.

---

## ✍️ Author
 
Master in Artificial Intelligence  
[University of Alicante]
