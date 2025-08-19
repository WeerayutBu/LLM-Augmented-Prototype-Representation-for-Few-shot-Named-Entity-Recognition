LLM-Augmented Prototype Representation for Few-shot Named Entity Recognition
============================================================================

This repository supports our work on **LLM-Augmented Prototype Representation** for **Few-shot Named Entity Recognition (NER)**. In this paper, we propose a new LLM-based data augmentation method and a representation learning objective from the augmented dataset for the FS-NER task. Our method aims to handle new entity types and increase inference efficiency in this setting.

Datasets
--------

- Few-NERD (General-domain Few-shot NER):  
  https://ningding97.github.io/fewnerd/

- Cross-domain NER Dataset (includes CoNLL-2003, GUM, WNUT, and OntoNotes):  
  https://github.com/AtmaHou/FewShotTagging?tab=readme-ov-file

Baseline Resources
------------------

- DecomMeta (Few-shot NER baseline):  
  https://aclanthology.org/attachments/2022.findings-acl.124.software.zip

- Baseline Data Augmentation (COLING 2020):  
  https://github.com/boschresearch/data-augmentation-coling2020?tab=readme-ov-file

LLM Models for In-Context Learning (ICL)
----------------------------------------

For the in-context learning (ICL) experiments, we conducted all evaluations using Ollama version 0.1.45, relying on the default LLM models provided by Ollama without any additional fine-tuning. The following models were used:

- Llama3 (70B-instruct and 8B-instruct): https://ollama.com/library/llama3  
- Gemma3 (4B and 27B): https://ollama.com/library/gemma3  
- Mixtral (8x22B): https://ollama.com/library/mixtral
