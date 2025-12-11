
Lab 08 – Visual Language Models (VLM)

Course: ITAI 1378
Student: Elijah Raines

📌 Overview

In this lab, I explored Visual Language Models (VLMs) — AI systems that can understand both images and text together.
The lab had two paths:

Path A: CLIP (lightweight, works on CPU)

Path B: BLIP / BLIP-2 (heavier models, image captioning + VQA)

I worked through model loading, running experiments, observing results, and answering reflection questions.

-----------

🖼️ What I Did

-----=
✅ 1. Environment Setup

Installed PyTorch, Transformers, and supporting libraries.

Checked for GPU availability since VLMs run much faster with GPU.

✅ 2. Understanding Core VLM Concepts

Learned how images and text become embeddings.

Saw how models align two different modalities in the same vector space.

✅ 3. CLIP Experiments (Path A)

Zero-shot image classification

Image–text retrieval (searching images using text queries)

Visualizing embedding similarity

Answered reflection questions on accuracy and limitations

✅ 4. BLIP Experiments (Path B)

Image caption generation

Visual Question Answering (VQA)

Conditional vs. unconditional captions

Compared model-generated captions with real captions

✅ 5. Fine-Tuning Concepts

Learned what model parameters are

Explored freezing layers and why it matters

Reviewed training loops, contrastive loss, and evaluation metrics

Completed reflections on data quality and model risks

---------

💡 Key Things I Learned

CLIP is great for matching text and images (classification + search).

BLIP is better for generating text from images (captioning + Q&A).

Embeddings allow AI to compare text and visuals using similarity scores.

Data quality is extremely important when fine-tuning.

VLMs can hallucinate or give incorrect details if prompts are unclear.

-------

🎯 Skills Gained

Working with HuggingFace VLM models

Understanding embeddings and similarity

Running inference for classification, retrieval, captioning, and VQA

Thinking critically about model limitations

Interpreting VLM outputs and evaluating model behavior


-------


📁 Files in This Lab

This README refers to the notebook:
👉 Lab_08_2025_VLM_Lab_Exercise.ipynbhttps://github.com/Eraines12/Elijah-Raines-AI-Portfolio/blob/main/ComputerVision-AI/Labs/L08%20Visual%20Language%20Models%20(VLMs)/Lab_08_Raines_Elijah_ITAI1378%20(1).ipynb

