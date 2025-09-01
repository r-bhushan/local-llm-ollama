# Local LLM with Ollama (Windows + Docker + Java)

Turn your **RTX 3090** into a local LLM workstation using **Ollama** in Docker. Test with **Postman** and call from **Java**. Perfect for developers who want **cloud-free AI** for coding and experimentation.

## Features
- Run Ollama LLMs locally on Windows
- Optimized for **RTX 3090**
- Pull & run large models (e.g., `qwen3:30b`)
- OpenAI-compatible API for Postman & Java
- Docker Compose setup for easy deployment
- Persistent volume for model storage

## Requirements
- Windows 10/11 with WSL2
- Docker Desktop with NVIDIA GPU support
- NVIDIA RTX 3090 (VRAM ≥ 24 GB recommended)
- Java 17+ (for sample Java client)
- Postman (optional, for testing API)
