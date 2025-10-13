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
- The examples demonstrate specialized run types - the first creates an LLM run with a comedian personality that generates political humor, while the second implements a retriever run that fetches Trump jokes from a simulated database, both properly formatted for LangSmith's specialized tracing and visualization features

---
## Learnings from Module 1 (Lec 3)
- This notebook explores alternative LangSmith tracing methods beyond the @traceable decorator, including automatic tracing for LangChain/LangGraph with environment variables, context managers for granular code block tracing, OpenAI client wrapping for automatic LLM call tracing, and the advanced RunTree API for manual trace construction with maximum control.
  
- These examples demonstrate alternative tracing methods - the first uses a context manager for granular control over specific code blocks, while the second shows automatic tracing with wrapped OpenAI clients that eliminates the need for manual decorators.

---
## Learnings from Module 1 (Lec 4)
- This notebook demonstrates how to use LangSmith's Threads feature to group related traces into conversational sequences for multi-turn chatbot applications. It shows how to create unique thread IDs and associate multiple traces together using metadata fields like thread_id, session_id, or conversation_id to maintain conversation context across interactions
  
- The examples demonstrate conversational threading - the first creates a customer support chat that maintains context across multiple turns, while the second shows a recipe assistant that tracks a cooking session through sequential steps, both using thread IDs to group related traces in LangSmith.



---
## Learnings from Module 2 (Lec 1)
- The notebook demonstrates how to programmatically create and populate datasets in LangSmith using the Python SDK. It shows how to bulk upload examples with structured inputs and outputs, create datasets from application traces, and manage training/evaluation data outside the LangSmith UI for scalable dataset management.
  
- The examples demonstrate dataset creation and bulk uploading - the first creates a product FAQ dataset with question-answer pairs, while the second builds a customer feedback dataset for sentiment analysis, both showing how to structure inputs/outputs and use the LangSmith client to populate datasets programmatically.

---
## Learnings from Module 2 (Lec 2)
- This demonstrates LLM-as-judge evaluation - using an LLM to automatically score and evaluate AI responses against expected outputs, which is fundamental for automated testing and quality assurance of AI systems

---
## Learnings from Module 2 (Lec 3)
- This demonstrates running experiments in LangSmith - systematically testing AI applications against datasets with custom evaluators to measure performance, compare model versions, and track improvements over time through automated evaluation workflows.

<img width="2878" height="1638" alt="image" src="https://github.com/user-attachments/assets/13a2ecaa-ced4-413e-bb2d-6204264b1ced" />

---
## Learnings from Module 3 (Lec 1)
-  learned that prompt templates are better than fixed prompts because you can change parts of them easily. I used the LangSmith Playground to test different AI models and instructions. I saw that changing the main instruction completely changes the result. I also learned how to make the AI give me answers in a specific format, and how to test it with different questions to see how well it works.
- Link: https://github.com/adi230306/adi230306-langsmith-MAT496/blob/main/playground_experiments.ipynb
