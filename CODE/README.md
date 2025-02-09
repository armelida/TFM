# CODE Folder - Overview

This folder contains the various Jupyter notebooks used in the evaluation, training, and analysis of Large Language Models (LLMs) for this work. The files are categorized based on their primary function: evaluation, training, data extraction, and API-based testing.

## 📌 **Contents of the CODE Folder**

### **1️⃣ Evaluation Notebooks**
These notebooks assess the performance of various LLMs on **medical MIR exam questions**. A different file was created for each evaluation. This is a selection of the :
- **EVALUATOR2_FLAN_T5_MIRfulltextPromptingenglishOKOK.ipynb** – Evaluates **FLAN-T5** with full-text prompting.
- **EVALUATOR_Claude3_5_sonnet.ipynb** – Evaluates **Claude 3.5 Sonnet** on MIR questions.
- **EVALUATOR2_FLAN_T5_MIRQAok_bad.ipynb** – Tests **FLAN-T5** using QA-format MIR questions.
- **EVALUATOR2_FLAN_T5_Vainilla.ipynb** – Baseline evaluation of **FLAN-T5** without modifications.
- **EVALUATOR2_SpanishMedicalMT5Evaluator.ipynb** – Evaluation of **mT5 model** for Spanish medical questions.
- **EVALUATOR2_o1_preview_2024_09_12.ipynb** – Evaluation of OpenAI’s **o1-preview model**.
- **EVALUATOR_Claude3opus.ipynb** – Evaluation of **Claude 3 Opus**.
- **TogetherAPIEvaluator_Nvidia_Llama3_1_70bHF.ipynb** – Evaluates **NVIDIA LLaMA 3 70B** via API.

### **2️⃣ Training Notebooks**
These notebooks contain custom training implementations for fine-tuning models:
- **CustomTrainerBothModels.ipynb** – Custom trainer for two models.
- **MELI_TRAINER_MIRFlanT5TrainerFullFormatOK.ipynb** – Trainer for **FLAN-T5** using full MIR dataset.
- **MELI_TRAINER_MIRFlanT5TrainerQAFormatOK.ipynb** – Trainer for **FLAN-T5** in **QA format**.

### **3️⃣ Data Processing & Extraction Notebooks**
These notebooks extract, clean, and structure the medical questions for evaluation:
- **Copy_of_EvaluationFilesLoader.ipynb** – Loads evaluation files for processing.
- **Scrapper1OK.ipynb** – Scrapes medical datasets for use in the thesis.
- **TFM2_Extract_and_structure_questions2.ipynb** – Extracts and structures MIR questions.

## 🚀 **Usage Guide**
- Google Colab has been used to create and run the noteboks, You can open the notebooks in Colab.
- Open and run any **evaluation notebook** to test the performance of different models.
- Use **training notebooks** to fine-tune models on medical datasets.
- Run **data extraction notebooks** before evaluation to ensure structured input data.

