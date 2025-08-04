# 🔬 ResearchMate: An Agentic AI Academic Assistant

**ResearchMate** is an agentic AI system designed to assist students and researchers with academic tasks such as summarizing topics, generating hypotheses, suggesting research subtopics, drafting introductory paragraphs, and formatting citations.  
Built using **IBM Watsonx AgentLab** with **Granite LLM**, it simulates the behavior of a research assistant capable of performing structured multi-step reasoning.

---

## 🚀 Features

- 🧠 Academic topic summarization  
- 🔍 Hypothesis generation  
- 📚 Research subtopics/question suggestions  
- 📝 Drafting of introductory paragraphs  
- 🔖 APA-style dummy citation generation  
- 🎓 Formal academic tone and section-wise output

---

## 🧱 Architecture

- **Platform:** IBM Watsonx AgentLab  
- **Model:** Granite LLM (LangGraph + ReAct architecture)  
- **Prompt Type:** Multi-step instruction prompt  
- **Input:** Predefined or static topic  
- **Output:** Structured academic response with headings

---

## ⚙️ How It Works

The agent executes the following sequence:
1. Simulates academic context (no external retrieval)
2. Generates a formal summary (100–150 words)
3. Proposes a testable hypothesis
4. Suggests 2–3 research subtopics
5. Drafts an introductory paragraph
6. Provides a realistic dummy citation (APA format)

---

## 🖥️ Deployment Status

> The project was built and tested within IBM Watsonx AgentLab.  
Due to variable-binding limitations in AgentLab's current beta version, user-input-based deployment was not completed.  
All agent behavior was validated using static topic testing.  
Screenshots of inputs and outputs are included in the documentation.

---

## 📸 Sample Output

**Input Topic:** Quantum Computing in Medicine  
**Output Sections:**  
- Summary  
- Hypothesis  
- Research Questions  
- Introductory Paragraph  
- APA Citation  

📷 *See `/screenshots` folder for full examples.*

---

## 🔮 Future Scope

- Dynamic user input via form or chatbot  
- Integration with academic databases (e.g., Semantic Scholar)  
- Retrieval-Augmented Generation (RAG)  
- Deployment via IBM Cloud Lite with UI  
- Multi-language and accessibility support

---

## 📚 References

- [IBM Watsonx](https://www.ibm.com/cloud/watsonx)  
- OpenAI. (2023). *Agentic AI Documentation*  
- Sample dummy citation sources used in generated outputs

---

## 📜 License

This project is part of the **AICTE–IBM Virtual Internship Capstone Project** and is for educational and demonstration purposes only.

---

## 🙋‍♀️ Author

**Shreya Padmakumar**  
AICTE–IBM Virtual Internship (2025)  
ResearchMate – Academic Agent Project

