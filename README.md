# 📊 Data Science DC – Code Examples

Code exammples from Data Science DC in May  2025.

---

### Baseline API (`/api`)

**Run this API** to provide data to the lessons 

- ✅ **FastAPI** framework written in Python
- 🔁 **SQLite3** database for sample data

### 🛠 Skill 1 – Create a Python SDK (`/sdk`)

**Develop a Python SDK** to interface with your FastAPI-based API. This example demonstrates:

- ✅ **Pydantic** models for robust data validation and serialization  
- 🔁 **Exponential backoff** with retry mechanisms for fault tolerance  
- 🪵 Integrated **logging** for observability and diagnostics

Ideal for those building internal or public-facing API client libraries.

📂 Folder: [`/sdk`](./sdk)

---

### 🤖 Skill 2 – Create an AI Agent (`/ai_agent`)

**Construct an interactive AI agent** using state-of-the-art tools:

- 🧠 **LangGraph** for defining structured agent workflows  
- ✨ **Anthropic APIs** (e.g., Claude) for LLM-driven interaction  
- 📓 **Jupyter Notebooks** for iterative development and demonstration

(Also uses SDK from step 1)

A must-see if you're exploring generative AI, reasoning agents, or tool-using LLMs.

📂 Folder: [`/ai_agent`](./ai_agent)

### 📦 Skill 3 – Deploy a Machine Learning Model (`/ml_model`)

**Serve a trained scikit-learn model** via a production-grade API using:

- ⚙️ **ONNX Runtime** for optimized inference across environments  
- 🌐 **FastAPI** to expose the model as a performant RESTful service  
- 🧪 Example pre- and post-processing code for online inference

This project is a blueprint for transitioning from local notebooks to scalable deployment.

📂 Folder: [`/ml_model`](./ml_model)

---
