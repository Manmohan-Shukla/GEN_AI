# GEN_AI



This is a comprehensive, vendor-agnostic course covering the entire Generative AI development lifecycle — from fundamentals to building real applications with LLMs, RAG, agents, deployment, and optimization.

---

## Official Code Repository

All hands-on code, notebooks, and examples from the course:

**→ https://github.com/ExamProCo/GenAI-Essentials**

### Repository Structure
Gen_AI/
├── README.md



## Quick Start

1. **Clone the official code repo**
   ```bash
   git clone https://github.com/ExamProCo/GenAI-Essentials.git
   cd GenAI-Essentials

Create a virtual environment (recommended)Bashpython -m venv .venv
source .venv/bin/activate   # Linux/Mac
# or
.venv\Scripts\activate      # Windows
Install common packages (many folders have their own requirements.txt)Bashpip install openai anthropic groq huggingface_hub transformers \
            langchain langchain-community streamlit gradio \
            pinecone-client python-dotenv jupyter
Set up API keys
Create a .env file in the root or in specific folders:envOPENAI_API_KEY=sk-...
ANTHROPIC_API_KEY=sk-ant-...
GROQ_API_KEY=gsk_...
HF_TOKEN=hf_...
PINECONE_API_KEY=...
Open the relevant folder (e.g. openai/, hugging-face/, crewai/, etc.) and follow the notebooks or scripts.


Essential Tools & Platforms

Playgrounds: OpenAI Playground, Anthropic Console, Google AI Studio, Groq Console, Hugging Face Spaces
Local LLMs: Ollama, llama.cpp, LM Studio, GPT4All
Vector DBs: Pinecone, pgvector, Chroma, Weaviate, Qdrant
Frameworks: LangChain, LlamaIndex, CrewAI, Haystack, Semantic Kernel
UI: Streamlit, Gradio, Chainlit, FastHTML
Serving: vLLM, TGI, Ollama, Hugging Face Inference Endpoints

Great Repositories

ExamProCo/GenAI-Essentials ← Official course code
microsoft/generative-ai-for-beginners
langchain-ai/langchain
run-llama/llama_index
crewAIInc/crewAI

Books & Papers (Free / Open)

“Prompt Engineering Guide” – https://www.promptingguide.ai
“Hands-On Large Language Models” (O’Reilly – free chapters available)
Attention Is All You Need (Transformer paper)
RAG papers (Lewis et al., 2020)


Certification
You can optionally take the ExamPro GenAI Essentials Certification (EXP-GENAI-001).

More details: https://www.exampro.co/exp-genai-001

License & Credits

Course content by Andrew Brown / ExamPro and freeCodeCamp.org
Code repository: ExamProCo/GenAI-Essentials
This README is community-maintained for easy reference.

Happy building!

If you find this useful, star the official repo and share the course.