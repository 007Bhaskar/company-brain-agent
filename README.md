# 🧠 Company Brain Agent

An AI agent designed to act as a centralized "Company Brain," leveraging graph schemas and LLMs to query organizational data, retrieve insights, and streamline information access. Built for the WeMakeDevs Hackathon.

## 🚀 Features
* **Graph-Based Data Representation:** Structures company information using a robust schema for contextual querying.
* **Interactive Notebook Workflow:** Powered by Jupyter Notebooks for rapid prototyping and easy visualization of query results.
* **LLM-Powered Retrieval:** Natural language interface to look up company knowledge seamlessly.

## 🛠️ Tech Stack
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Core Libraries:** LangChain / LlamaIndex / OpenAI (update based on what you used)
* **Database/Schema:** Graph Database / Custom Schema

## 📦 Getting Started Locally

### Prerequisites
Make sure you have Python and Jupyter installed on your machine.

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/007Bhaskar/company-brain-agent.git](https://github.com/007Bhaskar/company-brain-agent.git)
   cd company-brain-agent

2. Install Dependencies:
      pip install jupyter openai langchain

3. Set up your environment variables:
Create a .env file in the root directory and add your API keys:

   OPENAI_API_KEY=your_actual_api_key_here

4. Launch Jupyter Notebook:

   jupyter notebook company_brain_agent.ipynb
