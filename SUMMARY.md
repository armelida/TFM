# Summary of the Master´s Thesis

## Title: Evaluation Framework for Spanish Medical Applications of Large Language Models

### Author: Alberto Ramón Mélida Asensio
**Type of work**: Methodology Development  
**Advisor**: Óscar Fernández Mora  
**Date**: January 19, 2025  

## Abstract
This research examines the multilingual performance of **Large Language Models (LLMs)** in **medical applications**, focusing on Spanish. The study evaluates the medical understanding of various models, including **ChatGPT-4, Claude Sonnet, Grok 2, and DeepSeek V3**, using **MIR exam questions**. 

### Key Findings:
- **All models passed** the minimum passing score of the MIR exam.
- **Nine models** outperformed the top 10% of human test-takers.
- **OpenAI's o1-preview** achieved the highest accuracy (**96%**).
- We developed an **automated evaluation pipeline** to extract and assess medical questions.
- Experiments with **smaller open-source models (FLAN T5)** showed improvements but remained insufficient for clinical use.

## Methodology
The methodology involved:
- **Data Collection**: Extracting 180 medical questions from the latest **MIR exam** in Spanish.
- **Model Selection**: Evaluating top-performing proprietary LLMs (ChatGPT-4, Claude Sonnet, Grok 2, DeepSeek V3) and smaller open-source models (FLAN T5).
- **Evaluation Metrics**: Comparing accuracy, bias, and reliability using a structured scoring system.
- **Automation**: Developing a Python-based pipeline to automate the extraction and evaluation process.

## Challenges Faced
- **Multilingual Bias**: Many LLMs perform better in English than in Spanish, affecting medical terminology accuracy.
- **Question Complexity**: Some models struggled with nuanced medical reasoning.
- **Open-Source Limitations**: FLAN T5 showed improvements but still lags behind proprietary models in medical understanding.

### Future Work:
- Enhancing multilingual evaluation methodologies.
- Training specialized **Spanish medical models**.
- Improving AI safety for clinical applications.
- Expanding the dataset to include **more diverse medical cases**.
- Investigating **explainability methods** to ensure model transparency in medical decision-making.
