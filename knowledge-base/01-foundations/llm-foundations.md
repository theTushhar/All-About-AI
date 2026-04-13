# LLM Foundations

This note keeps the core transformer ideas in one place and acts as the landing page for the earliest material in the repo.

## What matters most
- The Transformer replaced recurrence with self-attention, which made training more parallel and scalable.
- Self-attention lets a token weigh other tokens in the sequence by relevance, even when they are far apart.
- Multi-head attention lets the model look at the same sequence through several learned views at once.
- This architecture became the base for modern LLMs and most of the agent stacks we build today.

## Why it is worth keeping
- It explains why modern models can handle long-context reasoning better than older RNN-based systems.
- It gives the mental model you need before RAG, tool use, and agents start making sense.

## Source material
- [Attention Is All You Need PDF](../../First/Attention%20is%20all%20you%20need.pdf)
- [Original foundation readme](../../First/README.md)
- [Week 1 Guided Learning LLM Foundations](../../code/Week%201%20Guided%20Learning%20LLM%20Foundations.txt)
