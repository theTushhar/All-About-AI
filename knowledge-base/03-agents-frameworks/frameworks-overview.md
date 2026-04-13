# Agents and Frameworks Overview

This is the current high-level map for the agent ecosystem.

## Quick comparison

| Framework | Best for | Current shape |
| --- | --- | --- |
| LangChain | Building custom LLM apps with integrations | Open source framework with a prebuilt agent architecture and broad model/tool support. |
| LangGraph | Controllable agent orchestration | Low-level orchestration with long-running workflows, memory, streaming, and human-in-the-loop control. |
| CrewAI | Collaborative multi-agent systems | Crews plus Flows for production-ready multi-agent automation. |
| LlamaIndex | Data-centric agents and workflows | Strong for context augmentation, RAG, agents over your data, and workflow composition. |
| AutoGen | Conversational multi-agent apps | Python-first framework with AgentChat, Core, Studio, and extensions. |
| OpenAI Agents SDK | Lightweight agent apps with handoffs | Small primitive set: agents, handoffs, guardrails, tracing, and runtime control. |
| PageIndex | Long-document reasoning and retrieval | Vectorless, reasoning-based RAG for traceable document intelligence. |
| Feynman | Research and literature workflows | Open-source research agent that reads papers, searches the web, writes drafts, and cites claims. |

## How to choose
- Use **LangChain** when you want the broadest general-purpose app framework.
- Use **LangGraph** when orchestration, state, and human approval matter.
- Use **CrewAI** when you want clear role-based collaboration between agents.
- Use **LlamaIndex** when your app is centered on private data, retrieval, and knowledge workflows.
- Use **AutoGen** when you want conversational multi-agent patterns in Python.
- Use **OpenAI Agents SDK** when you want a lightweight production path with handoffs and tracing.
- Use **PageIndex** when the problem is long-document understanding rather than generic vector search.
- Use **Feynman** when the task is research-heavy and citation quality matters.

## Suggested structure in this repo
- Put conceptual comparisons here.
- Put framework-specific deep dives in their own notes.
- Keep source links in the reference section so the overview stays readable.
