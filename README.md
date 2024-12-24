
---

### **Repo 2: LlamaIndex-CrewAI-Assistant**  

```markdown
# LlamaIndex + CrewAI Assistant

<a href="https://colab.research.google.com/github/run-llama/llama_index/blob/main/docs/docs/examples/cookbooks/crewai_llamaindex.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

This cookbook demonstrates how to build an advanced research assistant by plugging LlamaIndex-powered tools into a CrewAI-powered multi-agent setup.

## 🌟 LlamaIndex Overview  
LlamaIndex is a framework enabling developers to easily build LLM-powered applications over their data. It includes production modules for indexing, retrieval, and prompt/agent orchestration. The primary use case is building a generalized QA interface that enables knowledge synthesis over complex questions.

## 🌟 Agent Setup Example  

### 1. **Setup a Simple Calculator Agent:**  
We begin by porting over a set of tools available on LlamaHub (https://llamahub.ai/). This allows for the creation of a basic calculation agent, demonstrating fundamental agent setups.

### 2. **Setup a Financial Analyst Agent:**  
Next, we integrate a RAG (Retrieval-Augmented Generation) query engine into the CrewAI agent. The agent can query databases, synthesize data, and offer financial analysis seamlessly. Learn how to implement this advanced research assistant.

## 🌟 Key Features  

- **LlamaIndex Integration**: Using LlamaIndex’s powerful querying capabilities, agents are empowered to retrieve and synthesize data more effectively.
  
- **CrewAI Multi-Agent Setup**: The CrewAI framework enables seamless agent interaction, enhancing productivity in collaborative research environments.

- **Real-time Communication**: This cookbook covers the integration of advanced conversation and task management across multiple agents powered by LlamaIndex.

## Installation  

To set up your environment for CrewAI and LlamaIndex, follow these steps:

1. Clone this repository:  
   ```bash
   git clone https://github.com/chaimaaskri/LlamaIndex-CrewAI-Assistant.git  
