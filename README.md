# Text-to-Image-Generation-Multimodal-Analysis
This project focuses on implementing LoRA finetuning from scratch on Stable Diffusion-1.4 model. The model is finetuned on the midjourney dataset (publically available in kaggle). The <b>main goal</b> of the project is implement a text-to-image pipeline for generating high quality images in the style of the midjourney dataset using text prompts. 

The secondary tasks focuses on:
- Evaluating the text-image alignment the CLIP score metric is used.
- Extracting key regions-of-interest using SAM-2 model.

<b>Goals:</b>
- Evaluate how closely generated images reflect the textual input.
- Understand the semantic fidelity using multimodal embeddings.
- Segment and analyze components within the generated images for deeper insights.

<b>Framework and Tools:</b>
- PyTorch
- HuggingFace Transformers,Diffusers
- Segment-Anything-Model-2
- OpenCV
- Supervision
- Accelerate
- Pandas
- Numpy
- Tensorboard
