# 📄 Event-Driven Agentic Document Workflows  

## 🔍 Overview  
This project enables **agentic workflows** for **resume analysis**. It parses a resume and allows a **question-answering agent** to provide insights based on user queries. Additionally, it integrates **voice-based feedback**, allowing users to respond via speech.

---

## ⚙️ Features  
✔️ **Resume Parsing** – Extracts key details using `LlamaParse`.  
✔️ **Agentic Q&A** – Answers user questions based on the resume.  
✔️ **Retrieval-Augmented Generation (RAG)** – Enhances responses with contextual information.  
✔️ **Event-Driven Workflow** – Supports branching, loops, concurrent execution, and streaming.  
✔️ **Human in the Loop** – Integrates feedback mechanisms to refine responses.  
✔️ **Voice-Based Feedback** – Uses `Whisper` for speech-to-text conversion.

---

## 🚀 Project Flow  

### 🏗️ 1. Building a Workflow  
- 📌 **Creating a Workflow**  
- 👁️ **Visualizing Workflow**  
- ✏️ **Creating Custom Results**  
- 🔁 **Loops & Branching**  
- ⚡ **Concurrent Execution & Streaming**  

### 📚 2. Adding RAG (Retrieval-Augmented Generation)  
- 📜 **Parsing Resume Document** (`LlamaParse`)  
- 🗂️ **Creating Vectorstore Index**  
- 🔍 **Query Engine for Resume**  
- 💾 **Storing Index to Disk**  
- 🦾 **Making RAG Agentic**  
- 🛠️ **Wrapping Agentic RAG into a Workflow**  
- 🎭 **Workflow Visualization**  

### 📝 3. Form Parsing  
- 📃 **Processing Application Forms** (`LlamaParse`)  
- 🤖 **Adding a Form Parser to Workflow**  
- ❓ **Generating Relevant Questions**  
- 👀 **Workflow Visualization**  

### 🏷️ 4. Human in the Loop  
- 🔄 **Adding a Feedback Loop**  
- 🧠 **Utilizing User Feedback**  
- 🖥️ **Workflow Visualization**  

### 🎙️ 5. Use Your Voice  
- 🎤 **Getting Voice Feedback** (`Whisper Model`)  
- 💾 **Storing Transcriptions**  
- 📢 **Analyzing Voice Feedback**  

---

## 🛠️ Tech Stack  
- 🐍 **Python**  
- 🤗 **LlamaIndex**   
- 🧠 **LlamaParse**  
- 🔍 **Vector Databases (VectorStoreIndex)**  
- 🎤 **OpenAI Whisper (Voice Recognition)**  
- ⚡ **OpenAI API / Llama Cloud API**  
- 🎨 **Gradio (UI Components)**  

---

## 🚀 Getting Started  

### 1️⃣ Clone Repository  
```bash
git clone https://github.com/dhashyanth/Event-Driven-Resume-ChatAgent.git
cd Event-Driven-Resume-ChatAgent
