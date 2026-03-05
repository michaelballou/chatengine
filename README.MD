# ChatEngine: Enterprise NLP Intent Routing & Dialog Platform

## Overview
ChatEngine is an open-source chatbot engine originally architected to enable industry collaboration on NLP technology. Designed to mirror a natural human conversation UX, the platform moves beyond simple keyword matching by implementing dynamic, intelligent intent routing and stateful dialog flow trees. 

## Architectural Philosophy
Before the widespread adoption of generative LLMs, building reliable, enterprise-grade conversational interfaces required strict deterministic routing combined with intelligent NLP. 

I architected ChatEngine to solve the "context-loss" problem in early chatbots. By building a custom JavaScript backend and highly structured dialog trees, the system can dynamically route user intents while maintaining the state of the conversation, ensuring users reach their goal without endless loops.

## Core Features
* **Dynamic Intelligent Intent Routing:** Parses raw user input to determine the core intent and automatically routes the conversation to the appropriate dialog node.
* **Stateful Dialog Flow Trees:** Manages complex, multi-turn conversations by tracking user state and context throughout the session.
* **Custom JavaScript Backend:** A lightweight, highly scalable backend designed for low-latency message processing.
* **Human-Centric UX:** Engineered specifically to mirror a true dialogue experience rather than a static command-line interface.

## Evolution to Modern AI
While the AI landscape has shifted massively toward Large Language Models (LLMs) and RAG architectures, the core principles of ChatEngine remain highly relevant. The intelligent intent routing established here serves as the foundational logic for modern AI Agent orchestration—routing a user's prompt to the correct tool, API, or sub-agent. 

## Tech Stack
* **Backend:** JavaScript / Node.js
* **Architecture:** Intent Routing, Dialog Trees