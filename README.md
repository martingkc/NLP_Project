# NLP_Project

Part of the submission for the NLP course at Polimi. We worked with the [NIH-CXR14-BiomedCLIP](https://huggingface.co/datasets/Yasintuncer/NIH-CXR14-BiomedCLIP-Features) dataset, which consists of X-ray images, pathology labels, short descriptive texts, and their corresponding embeddings extracted using the BiomedCLIP model by Microsoft.

This repository includes the following notebooks:

- **clip_caption_gpt.ipynb**: Implements an MLP that maps CLIP embeddings to the input space of a GPT-2 transformer, enabling caption generation from the embeddings.  
- **medgemma_finetune.ipynb**: Contains the fine-tuning of Google's MedGemma model (4B parameters) using the X-ray images and their associated captions.  
- **QWEN2.5VL_finetune.ipynb**: Covers the fine-tuning of the Qwen2.5 VL model, both the 3B and 7B parameter versions, on a subset of our dataset.

