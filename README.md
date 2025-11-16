# ProLoG: Hybrid Prompt and LoRA Based Adaptation of Vision-Language Models for OOD Generalization [AAAI 2026, Oral]

> **Authors:** Jungwuk Park, Dong-Jun Han, Jaekyun Moon

This is the official repository for our AAAI 2026 paper, **“ProLoG: Hybrid Prompt and LoRA Based Adaptation of Vision-Language Models for OOD Generalization.”**  

This repository includes the technical appendix and code. The code will be released soon.

---

## Abstract
<p align="justify">
While vision-language models (VLMs) achieve remarkable performance when fine-tuned on downstream in-distribution (ID) data, this process often compromises their generalization ability on out-of-distribution (OOD) samples due to overfitting. To address this, we present <b>ProLoG</b>, a new adaptation framework that effectively fine-tunes VLMs on downstream tasks while preserving strong OOD generalization. Specifically, we design a unique integration of prompt tuning and LoRA, forming a robust hybrid architecture that improves both ID and OOD performance. During training, we introduce an augmentation-based regularization loss that enhances generalization by leveraging augmented image features aligned with LLM-generated texts encoding key class attributes. Leveraging our hybrid design, we also propose an adaptive inference strategy that flexibly applies trained prompts and LoRA based on a task similarity score to handle both ID and OOD data effectively. Extensive experiments demonstrate that ProLoG consistently outperforms existing methods across multiple datasets, confirming its effectiveness.
</p>

---

## Contact
If you have any questions, feel free to contact at savertm9@gmail.com.


## Acknowledgements
Our code is based on [PromptSRC](https://github.com/muzairkhattak/PromptSRC), [CoPrompt](https://github.com/ShuvenduRoy/CoPrompt) and [CoCoOp](https://github.com/KaiyangZhou/CoOp) repositories. We appreiciate the authors for releasing their code.

