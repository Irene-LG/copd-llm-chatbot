# COPD Exacerbation Early Warning & Home Management Chatbot

This project implements a domain-specific healthcare chatbot designed to help individuals in Nova Scotia manage Chronic Obstructive Pulmonary Disease (COPD). Built using open-source LLMs and the AnythingLLM + Ollama framework, the chatbot uses Retrieval-Augmented Generation (RAG) to provide evidence-based guidance on early warning signs and home management strategies for COPD flare-ups.

---

## Disclaimer

> **This chatbot is for educational and research purposes only. It does not provide professional medical advice, diagnosis, or treatment. In the event of a medical emergency, please call 911 or seek immediate medical attention.**

---

## Project Structure
copd-llm-chatbot/
├── knowledge_base/
│ ├── knowledge_document_1.pdf
│ ├── knowledge_document_2.md
│ └── knowledge_document_3.txt
├── prompt/
│ └── system_prompt.txt
├── documentation/
│ ├── scenario_pack.pdf
│ └── use_case_description.md
├── demo/
│ ├── demo_video.mp4
│ └── chat_transcript.txt
└── README.md

---

## Features

- **Framework**: AnythingLLM + Ollama (local model: Mistral)
- **Knowledge Retrieval**: Embedded documents from Nova Scotia Health, Lung Association, and other COPD education sources
- **Prompt Design**: Custom system prompt with clear tone, crisis escalation, and ethical scope limitations
- **Query Examples**:
  - “My phlegm turned yellow and increased—should I see a doctor?”
  - “What can I do at home to help prevent COPD flare-ups?”
- **Ethical Safeguards**:
  - No diagnosis or hallucination
  - Clear medical disclaimers
  - Refusal response if answer is not grounded in sources

---

## Local Deployment Instructions

### Prerequisites
- [Ollama](https://ollama.com) (to run LLMs locally)
- [AnythingLLM](https://docs.anythingllm.com/) (frontend + RAG engine)

### Project Goal
To explore responsible AI in healthcare by building a conversational assistant that improves patient self-management and decision-making — while prioritizing safety, ethical guidance, and local context.

**Author**
Giang (Irene) Nguyen
Saint Mary’s University – Master of Business Analytics
July 31, 2025