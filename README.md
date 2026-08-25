# GenAI Notebook

A running log and summary of everything I'm learning about Generative AI

Each repo is a playground for a specific idea or cancept rather than a polished product, so expect notes, scripts, and "getting it to work" energy over production code.

---

## LangChain

Core building blocks of the LangChain framework, each isolated into its own repo so the concept is easy to revisit.

| Repo | What it covers |
|---|---|
| [tui-chatbot](https://github.com/24thAbhinav/tui-chatbot) | A terminal (TUI) chatbot used to learn **prompts, dynamic prompts, prompt templates, and `ChatPromptTemplate`**. |
| [Paper-Summarizer](https://github.com/24thAbhinav/Paper-Summarizer) | Summarizes a set of hard-coded paper titles — early practice with chaining prompts and LLM calls into a small utility. |
| [document_loaders](https://github.com/24thAbhinav/document_loaders) | Working with LangChain **document loaders** to ingest different data sources. |
| [text_splitters](https://github.com/24thAbhinav/text_splitters) | Practicing **text splitting** strategies for chunking documents before embedding/retrieval. |
| [vector_stores](https://github.com/24thAbhinav/vector_stores) | Storing and querying embeddings using LangChain **vector store** integrations. |
| [OutputParsers](https://github.com/24thAbhinav/OutputParsers) | Structuring LLM responses with LangChain **output parsers**. |
| [chains](https://github.com/24thAbhinav/chains) | Composing multi-step LLM logic using LangChain **chains**. |
| [Runnables](https://github.com/24thAbhinav/Runnables) | Learning the **Runnable** interface (LCEL) — piping, batching, and composing LangChain components. |
| [tool-call](https://github.com/24thAbhinav/tool-call) | Giving LLMs access to external functions via **tool calling**. |

---

## RAG

Retrieval-Augmented Generation experiments -> combining the pieces above (loaders, splitters, vector stores) into working retrieval pipelines.

| Repo | What it covers |
|---|---|
| [pdf-chatbot](https://github.com/24thAbhinav/pdf-chatbot) | A **PDF chatbot** implementing basic RAG — load a PDF, chunk it, embed it, retrieve relevant context, and answer questions grounded in the document. |

---

## LangGraph

Moving from linear chains to stateful, graph-based agentic workflows.

| Repo | What it covers |
|---|---|
| [Langgraph](https://github.com/24thAbhinav/Langgraph) | Repo where im logging all langgraph fundamental learnings |

---

## MCP (Model Context Protocol)

Building and using MCP servers to connect LLMs to real tools and data.

| Repo | What it covers |
|---|---|
| [obsidian-mcp](https://github.com/24thAbhinav/obsidian-mcp) | A TypeScript MCP server exposing an Obsidian vault to MCP clients (Claude Desktop/Code) with hybrid full-text + semantic search and an Anki-style spaced-repetition (SM-2) active recall system. |
| [CitreaMesh](https://github.com/24thAbhinav/CitreaMesh) | An MCP server for the **Citrea testnet**, letting an LLM perform on-chain actions — checking balances, using a faucet, deploying/transferring ERC20 tokens, and analyzing wallet activity. |

---

## Roadmap

- [x] LangChain fundamentals (prompts → tool calling)
- [x] Basic RAG pipeline
- [x] LangGraph fundamentals
- [x] First MCP servers
- [ ] Multi-agent workflows
- [ ] Advanced RAG (hybrid search, re-ranking, evaluation)
- [ ] Fine-tuning / model customization

---

*This repo is a personal learning index — each linked repo is self-contained with its own setup instructions.*
