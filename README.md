# GPHyena: Genomic Pretrained Model with Hyena Operation

This repository contains the code and results for my final project in **GENE46100**. The project focuses on building, training, and fine-tuning a genomic language model using the Hyena operator, which provides an alternative to the attention mechanism for dealing with long-context sequence information. The python notebook contains the full implementation and training process. The pretrained model checkpoint is saved in the out directory.

### Project Overview
- Implemented a **GPH (Genomic Pretrained Hyena)** model, adapted from:
    - The Annotated Hyena blog and notebook
    - Henry’s nanoGPT notebook and Andrej Karpathy's nanoGPT framework
- Pretrained the model on human genome FASTQ sequences
- Fine-tuned the pretrained model on a three-class **enhancer classification** task

### Results Summary
- GPH achieved ~70% accuracy on enhancer classification, outperforming nano-GPT (~50%)
- GPH has ~8.1M parameters, slightly larger but more efficient at scaling to long context
- Training time doubled compared to GPT, which is expected according to the HyenaDNA paper.

### External References
- Annotated Hyena Blog Post: https://medium.com/autonomous-agents/evo2-demystified-the-ultimate-technical-guide-to-genomic-language-modeling-a75b0afe7b87  
- Annotated Hyena Notebook: https://github.com/expz/annotated-hyena/blob/master/annotated_hyena.ipynb  
- Henry’s nanoGPT notebook (class resource)  
- Andrej Karpathy's nanoGPT: https://github.com/karpathy/nanoGPT  
- Hugging Face Hyena Introduction: https://huggingface.co/learn/computer-vision-course/unit13/hyena  
- Hyena Hierarchy paper: https://arxiv.org/pdf/2302.10866 
- HyenaDNA paper: https://arxiv.org/abs/2306.15794  
- HyenaDNA Talk (YouTube): https://www.youtube.com/watch?v=haSkAC1fPX0&t=862s  
- GLM Benchmark in the context of Human Genetics: https://pubmed.ncbi.nlm.nih.gov/39990426/  