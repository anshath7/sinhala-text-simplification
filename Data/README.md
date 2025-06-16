This repository contains the data and code for the paper "Prompt Training Large Language Models for Low-Resource Text Simplification: A Comprehensive Evaluation on the Sinhala SiTSE Dataset". The same is in HF: https://huggingface.co/datasets/NLPC-UOM/SiTSE

## Abstract of the Paper (Not published yet)

Sinhala, a morphologically rich and low-resource language, presents significant challenges for automatic text simplification due to limited parallel corpora. This work explores a novel approach using instruction-tuned large language models (LLMs), specifically Gemma-2B, combined with parameter-efficient fine-tuning via LoRA. Unlike traditional supervised methods, our framework leverages strategically crafted Sinhala prompts to enable effective simplification with minimal training overhead. We evaluate the model using the SiTSE dataset, which contains 1,000 complex Sinhala sentences, each paired with three human-written simplifications. Our approach achieves strong performance, with a SARI score of 61.11 and a BERTScore F1 of 0.8603, while training only 0.4% of the model parameters. This work offers three main contributions: (1) the first prompt-based framework for Sinhala text simplification, (2) a parameter-efficient fine-tuning strategy requiring significantly fewer computational resources, and (3) a robust evaluation protocol for low-resource language scenarios. Our findings demonstrate that high-quality simplification is possible even with limited annotated data, and provide a scalable pathway for adapting LLMs to other underrepresented languages. These results have implications for accessibility, education, and public communication in linguistically diverse communities



## Referenced research paper belongs to

**BibTeX:**
```bibtex
@article{10.1145/3723160,
author = {Ranathunga, Surangika and Madhusanka, Rumesh and Rathnayake, Himashi and de Silva, Lahiru and Aluthwala, Thamindu and Peramuna, Saman and Shekhar, Ravi},
title = {SiTSE: Sinhala Text Simplification Dataset and Evaluation},
year = {2025},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
issn = {2375-4699},
url = {https://doi.org/10.1145/3723160},
doi = {10.1145/3723160},
journal = {ACM Trans. Asian Low-Resour. Lang. Inf. Process.},
month = {mar}
}
```
