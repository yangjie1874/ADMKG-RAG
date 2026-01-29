# ADMKG-RAG

This repository contains the **official implementation of ADMKG-RAG**.

---

## Official Implementation (Partial Release)

> **Status:** Partial release.  
> This repository currently releases **only the multimodal knowledge graph (MMKG) component** constructed in our paper.  
> The **complete codebase will be publicly released after the paper is officially accepted**.

---

## Overview

This repository provides the official implementation of the **multimodal knowledge graph (MMKG)** module proposed in our paper.  
At the current stage, we **only open-source the MMKG construction part**, which focuses on multimodal entity extraction, cross-modal alignment, and structured knowledge graph generation.

The **full ADMKG-RAG system**, including dataset processing, model training, inference, and evaluation, is **not yet released** and will be made available upon paper acceptance.

The overall framework of our paper is **built upon and extended from MMGraphRAG**, while being adapted to the agricultural multimodal domain.

---

## Multimodal Knowledge Graph (MMKG)

We additionally provide the **constructed multimodal knowledge graph in HTML format**, which can be directly opened and explored in a web browser for visualization and analysis.

- **MMKG (HTML format):**  
  https://pan.baidu.com/s/17qhLBQfYDrSId9De432kFw  
  **Extraction code:** `1234`

This resource allows users to inspect the multimodal entities and their relationships used in ADMKG-RAG without running the full pipeline.

---

## Data and Framework Sources

- **Dataset:**  
  Our multimodal dataset is built upon **Agri-LLaVA**:  
  https://github.com/Kki2Eve/Agri-LLaVA

- **Framework Foundation:**  
  The overall ADMKG-RAG framework is based on and extended from **CMEL / MMGraphRAG**:  
  https://github.com/wanxueyao/CMEL-dataset

---

## Currently Released Components

- Multimodal knowledge graph (MMKG) construction code  
- Utilities for image–text entity extraction and alignment  
- Knowledge graph structure generation and export  
- Pre-constructed MMKG in HTML format for direct visualization  

> **Note:** This partial release is intended **only for transparency and reproducibility of the MMKG module**.  
> Training scripts, full datasets, inference code, and model weights are **not included** at this stage.

---

## Planned Full Release (After Paper Acceptance)

The following components will be released after the paper is accepted:

- Complete dataset preprocessing and construction pipeline  
- Full ADMKG-RAG training and inference code  
- Evaluation and benchmarking scripts  
- Pre-trained model weights  
- Comprehensive documentation and tutorials  

---

## Citation

If you use this repository, the released MMKG resources, or the HTML knowledge graph in your research, please cite our paper and the related datasets/frameworks.  
The BibTeX entry will be provided after the paper is officially published.

---

## Acknowledgements

This work is based on and extends the following open-source projects:

- **Agri-LLaVA dataset:** https://github.com/Kki2Eve/Agri-LLaVA  
- **CMEL / MMGraphRAG framework:** https://github.com/wanxueyao/CMEL-dataset  

We sincerely thank the authors for making their resources publicly available.

---

## License

The license for this repository will be specified upon the full release.  
Before that, all released materials are provided **for research and review purposes only**.
