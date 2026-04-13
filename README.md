# LangChain Multi-Agent AI System

A modular Generative AI framework built with LangChain. This repository serves as a proof of concept (PoC) for prototyping advanced edge-case LLM application architectures and agent orchestration.

## Features

- **Model Integration Layer:** Establish foundational connections and interact with various Large Language Models.
- **Autonomous Agents:** Build intelligent agents with custom tool-calling capabilities to independently perform real-world tasks and workflows.
- **Structured Outputs:** Create reliable data pipelines leveraging LangChain's structured parsers to receive guaranteed, type-safe schema schemas.
- **Middleware & Memory:** Handle sophisticated conversational context tracking to optimize tokens during multi-turn encounters.
- **Multi-Agent Workflows:** Combine individual tools into cohesive, multi-agent frameworks.

## Getting Started

1. Clone this repository locally.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up your `.env` file with the relevant API keys (e.g., `OPENAI_API_KEY`, `TAVILY_API_KEY`).
4. Walk through the `genai/` notebooks to view the layer-by-layer architectural implementation.