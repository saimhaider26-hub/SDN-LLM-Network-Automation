# SDN Network Automation using Large Language Models (LLMs)

## Overview
This project explores the integration of **Generative AI (CodeLlama-7b)** with **Software Defined Networking (SDN)** controllers (Ryu/ONOS). The goal is to translate natural language network intents (e.g., "Block traffic from Host A to Host B") into executable OpenFlow rules.

## Architecture
- **LLM Engine:** CodeLlama-7b (Quantized 4-bit) running locally via `llama.cpp`.
- **SDN Controller:** Ryu Controller (Python-based).
- **Communication:** REST API bridge between the LLM inference engine and the SDN Northbound API.

## Key Features (In Development)
- [x] Natural Language Processing of Network Intents.
- [ ] Automated generation of OpenFlow Table Entries.
- [ ] Real-time verification of generated rules.

## Tech Stack
- **Python 3.10**
- **LangChain** (for prompt engineering)
- **Mininet** (for network topology simulation)
