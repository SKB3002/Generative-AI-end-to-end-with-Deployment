# Generative AI end-to-end with Deployment

## Techstack 
LangChain | LangGraph | PEFT | Fine Tuning | LoRA/QLoRA | HuggingFace | LLM's | Streamlit

## 1. Transformer Based Hinglish-Hindi-English Translator | [Link](https://github.com/SKB3002/Transformer-Based-Hinglish-Hindi-English-Translator)
- **Fine-tuning** the MarianMT hi_xx to en_xx base model on **IIT Bombay Hindi-English Parallel Corpora** for **Multilingual Translation**.
- This project demonstrates a complete pipeline for translating **Hinglish (Hindi + English mix)** text into **English**, passing through an intermediate Hindi **transliteration** step.
- Deployed on **Hugging Face Spaces**, this model is accessible for both technical users (via API) and non-technical users (via Web UI).

## 2. Advanced RAG Pipeline with Hybrid Retrieval and Reranking | [Link](https://github.com/SKB3002/Advanced-RAG-with-Hybrid-Search-and-Reranking)
- End-to-End **Retrieval-Augmented Generation (RAG)** System with **ChromaDB, BM25**, and **Groq’s LLaMA Models** and **Langchain**.
- **10%** Better Retrieval than **Naive RAG**.
- Currently **deployed** on **HuggingFace Spaces**.

## 3. Fine-Tuning Gemma 2B with LoRA/QLoRA for Legal Document Summarization | [Link](https://github.com/SKB3002/Fine-Tuned-Gemma-2B-with-LoRA)
- This project demonstrates **parameter-efficient fine-tuning**, enabling lightweight summarization on **resource-limited GPUs**.
- **LoRA Fine-Tuning**: Trained Gemma-2B with **rank-8 LoRA adapters** (memory-efficient).
- **QLoRA (4-bit quantization)**: Fit large model training in a **15GB GPU** without OOM.
- Evaluation: Tested on sample BillSum test cases, showing strong summarization performance

## 4. Curriculum Kit Generator with OpenAI OSS 20B LLM via API and Streamlit | [Link](https://github.com/SKB3002/Curriculum_Kit_Generator)
- User Uploads a PDF of a chapter of any class and any subject
- The agent develops a Lesson Plan to follow for teachers each of 45-50 mins (1 Lecture).
- Each Section of the Lesson plan is dynamic and can be kept/removed.
- The user can always add new section like 'Aim of the topic' and so on.
