# Syllable Analysis Data Augmentation (SADA)

This repository supports two research projects focused on syllable-based data augmentation for ancient Southeast Asian scripts. These efforts aim to improve recognition systems for palm leaf manuscripts by integrating linguistic grammar into visual recognition models.

---

## 📄 Papers

- **Paper 1:** *Khmer Syllable Analysis Data Augmentation (KH-SADA)*  
- **Paper 2:** *Multi-Low Resource Languages Syllable Analysis Data Augmentation (PALM-SADA)* (Under Review – *Pattern Recognition Letters*)

---

##  Paper 1: KH-SADA – Khmer Syllable Analysis Data Augmentation

###  Introduction

This project introduces a glyph dictionary and grammar-aware augmentation strategy designed to enhance Khmer palm leaf manuscript recognition. By modeling the language's grammatical structure, we support more robust OCR performance in low-resource settings.

###  Background

Inspired by publicly available datasets from the ICFHR 2018 competition, we built this dictionary to capture essential grammar forms of Khmer syllables. This linguistic grounding is critical for generating valid word formations and improving recognition accuracy.

###  Repository Contents

- **Khmer Grammar Structures** – Core grammar forms (CV, CVC, etc.) used in valid word formations.
- **Glyph Classes & Types** – Categorized glyphs (e.g., base consonants, subscript, vowels) to facilitate structured augmentation.
- **Ground Truth Training Data** – Labeled glyph image dataset used for training and evaluation.
- **Latin Transliterated Dictionary** – Mapping of Khmer glyphs to Latin script for cross-linguistic comparison.
- **Baseline Recognition System (DenseNet + GRU)** – Implementation and results of our ICFHR 2018-winning model using DenseNet and GRU.

###  Downloads

- **Pre-trained Model Weights**  
  [Download Weights](https://drive.google.com/file/d/15km1riGn19twubZQoGFhvfsXFphGJP1R/view?usp=sharing)

- **Dataset**  
  [Download Dataset](https://drive.google.com/drive/folders/16-mLPE8QSGB4-tKpUS2q7_V2L-VgjVhi?usp=sharing)

---

##  Paper 2: PALM-SADA – Multi-Low Resource Languages Syllable Analysis Data Augmentation

> **Status:** Under review at *Pattern Recognition Letters*

This paper extends our work from KH-SADA to **multi-script analysis**, including **Khmer, Balinese, and Sundanese**. It introduces a grammar-aware augmentation framework for multi-script palm leaf manuscripts and an improved recognition architecture.

- **New grammar forms**
- **Expanded datasets**
- **Combines linguistic rules with deep visual models**
- **Includes an interactive grammar-based post-processing mechanism.**: 

📦 **Documentation and dataset for PALM-SADA will be released upon publication.**

---



## Conclusion

This glyph dictionary serves as a foundational resource for researchers and developers working on text recognition in low-resource scripts. By integrating grammatical structures and providing a rich, linguistically-informed dataset, we aim to support the advancement of Khmer palm leaf manuscript recognition.

We welcome feedback, collaboration, and contributions to further enhance the tools and resources available for historical text recognition and classification. Thank you for your interest and support!

---

## Reference

If you use this work, please cite the following publication:



