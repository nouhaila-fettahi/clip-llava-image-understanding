# clip-llava-image-understanding
A multimodal AI lab exploring CLIP for zero-shot image classification and semantic image retrieval, and LLaVA for image description, visual question answering, and hallucination analysis.

## Overview

This project explores multimodal image understanding using two vision-language models: CLIP and LLaVA. It investigates image classification, text-to-image retrieval, prompt engineering, image description, visual question answering (VQA), and visual hallucination.

The project was developed as part of a practical laboratory on multimodal AI.

## Objectives

- Evaluate CLIP for zero-shot image classification.
- Explore how prompt formulation affects similarity scores.
- Retrieve images using natural-language queries.
- Use LLaVA to describe images and answer visual questions.
- Evaluate VQA responses through human assessment.
- Investigate visual hallucinations in multimodal models.
- Compare CLIP and LLaVA in terms of capabilities and use cases.

## Models and Technologies

- **CLIP:** `openai/clip-vit-base-patch32`
- **LLaVA:** `llava-hf/llava-1.5-7b-hf`
- Python
- PyTorch
- Hugging Face Transformers
- PIL (Pillow)
- Google Colab and Jupyter Notebook

## Experiments

### 1. CLIP Experiments

The CLIP experiments cover image and text embeddings, image-text similarity, zero-shot classification, classification accuracy, prompt engineering, and semantic image retrieval.

### 2. LLaVA Experiments

The LLaVA experiments cover image description, visual question answering, and the analysis of visual hallucinations.

### 3. Model Comparison

The project compares CLIP and LLaVA in terms of classification, image retrieval, natural-language generation, and visual question answering.

## Results

- **CLIP classification accuracy:** 100% on the evaluated set of 10 labeled images.
- **Prompt engineering:** Different text prompts produced different similarity scores.
- **Image retrieval:** CLIP ranked the five images most similar to a natural-language query.
- **LLaVA VQA accuracy:** 60% (15 correct answers out of 25 questions in the evaluated sample).
- **Hallucination analysis:** The experiment investigates whether LLaVA generates unsupported descriptions of objects absent from an image.

These results apply to the specific images and questions used in this laboratory and should not be interpreted as general benchmark performance.

## Repository Contents

- `LAB_CLIP_LLaVA_Full_Lab_Statement_.ipynb`: Notebook containing the laboratory experiments, code, outputs, and written answers.

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required Python dependencies.
3. Make the image dataset available in the expected directory.
4. Run the notebook cells in order.
5. For LLaVA experiments, use a compatible runtime with sufficient GPU memory.

The LLaVA model may require substantial GPU resources. Some setup steps or paths may need to be adapted to the execution environment.

## Conclusion

This laboratory demonstrates complementary capabilities of CLIP and LLaVA. CLIP is useful for zero-shot classification and semantic image retrieval, while LLaVA generates natural-language image descriptions and answers visual questions. The experiments also highlight the importance of evaluating model outputs and checking for hallucinations.

## Author

Nouhaila Fettahi
