# Course-specific-Chatbot


This repository contains an end-to-end implementation of a Natural Language Processing (NLP) application enhanced with Retrieval-Augmented Generation (RAG). The project aims to create a chatbot for [CNN Course by stanford](https://www.youtube.com/watch?v=vT1JzLTH4G4&list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv) by comparing between Tiny llama and Flan-T5.


## Table of Contents

1. [Data Extraction Pipeline](#1-data-extraction-pipeline)
2. [Prompting and comparing the two models](#2-prompting-and-comparing-the-two-models)

---


## 1. Data Extraction Pipeline

**File:** `Data_Collecting.ipynb`

### Overview
This Notebook uses Langchain YoutubeLoader to scrape and transcript Lectures

---


## 2. Prompting and comparing the two models

**File:** `nlp-project.ipynb`

### Overview
This Notebook chunks Transcripts into manageable sizes (500 characters) and embedded using all-MiniLM-L6-v2, Prompts Tiny LLama and Flan-T5 with RAG and saves the output result into a csv from both models to be later evaluated by GPT4
