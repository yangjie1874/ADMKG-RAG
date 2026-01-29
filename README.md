# ADMKG-RAG
This is the official implementation of ADMKG-RAG.
# Official Implementation (Partial Release)

> **Status:** Partial release.  
> This repository currently releases **only the multimodal knowledge graph (MMKG) component** of our work.  
> The **complete codebase will be made publicly available after the paper is officially accepted**.

---

## Overview

This repository provides the official implementation of the **multimodal knowledge graph (MMKG)** module proposed in our paper.  
At this stage, we **only open-source the MMKG construction part**, which is responsible for multimodal entity extraction, cross-modal alignment, and graph construction.

The full system—including dataset processing, model training, inference, and evaluation—is **not yet released** and will be published upon paper acceptance.

This project is **built upon and extends** the CMEL dataset / MMGraphRAG framework:

- https://github.com/wanxueyao/CMEL-dataset

---

## Currently Released Components

- Multimodal knowledge graph (MMKG) construction code  
- Basic utilities for image–text entity alignment  
- Graph structure generation and export  
- Minimal examples for MMKG usage  

> **Note:** This partial release is intended for **transparency and reproducibility of the MMKG module only**.  
> It does not include training scripts, full datasets, or model weights.

---

## Planned Full Release (After Paper Acceptance)

The following components will be released after the paper is accepted:

- Complete dataset processing and preparation pipeline  
- Full model training and inference code  
- Evaluation and benchmarking scripts  
- Pre-trained model weights  
- Detailed documentation and usage tutorials  

---

## Citation

If you use this repository in your research, please cite our paper and the CMEL / MMGraphRAG dataset.  
The BibTeX entry for our paper will be added after publication.

---

## Acknowledgements

This work is based on the **CMEL dataset and MMGraphRAG framework**.  
We sincerely thank the authors for making their resources publicly available:

- https://github.com/wanxueyao/CMEL-dataset

---

## License

The license for this repository will be clarified upon the full release.  
Before that, this code is provided **for research and review purposes only**.
