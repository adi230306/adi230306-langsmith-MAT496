# LangSmith  Project

**Author:** Aditya Singh (2410110023)

---


## Learnings from Module 1 (Lec 1)
- This Jupyter notebook demonstrates how to use LangSmith's @traceable decorator for tracing and monitoring AI applications. It shows how to instrument RAG pipeline functions for automatic tracing and how to add metadata to runs for better organization and filtering in LangSmith. The notebook includes practical examples of tracing document retrieval, response generation, and OpenAI API calls.
- 
- (What I implemented) The examples demonstrate how to progressively instrument Python functions with LangSmith's @traceable decorator, starting from basic function tracing and advancing to adding static metadata, runtime metadata, and finally chaining multiple traced functions to monitor complete workflows for comprehensive observability

---
## Learnings from Module 1 (Lec 2)
- This notebook demonstrates how to use LangSmith's specialized run types (LLM, Retriever, Tool, Chain) with proper formatting for optimal tracing and visualization. It covers LLM run requirements for chat models, streaming responses with reduce functions, document retrieval formatting, and tool calling workflows. Each section shows how to configure different run types with appropriate metadata and output structures for LangSmith's enhanced trace rendering
- 
- These examples demonstrate specialized run types - the first creates an LLM run with a comedian personality that generates political humor, while the second implements a retriever run that fetches Trump jokes from a simulated database, both properly formatted for LangSmith's specialized tracing and visualization features

---
## Learnings from Module 1 (Lec 3)
- This notebook explores alternative LangSmith tracing methods beyond the @traceable decorator, including automatic tracing for LangChain/LangGraph with environment variables, context managers for granular code block tracing, OpenAI client wrapping for automatic LLM call tracing, and the advanced RunTree API for manual trace construction with maximum control.
  
- These examples demonstrate alternative tracing methods - the first uses a context manager for granular control over specific code blocks, while the second shows automatic tracing with wrapped OpenAI clients that eliminates the need for manual decorators.
