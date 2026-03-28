## AI Health Assistant Chatbot
## Objective
To develop an intelligent, safe, and interactive health query chatbot using Large Language Models (LLMs) that provides structured medical information while implementing strict safety guardrails.
## Dataset & Model
- **Model Used**: Qwen/Qwen2.5-7B-Instruct
- **Infrastructure**: Hugging Face Inference API
- **Tech Stack**: Python, ipywidgets, python-dotenv
## Key Features
1. **Safety Guardrails**: A robust keyword filter that intercepts and blocks high-risk queries before model processing.
2. **AI Persona**: Configured as a "Senior Medical Assistant" to ensure professional and structured formatting.
3. **Structured Output**: Every response follows a strict 4-part framework: 
    - Direct Answer
    - Safety Guidelines
    - Conclusion
    - Medical Disclaimer
    ## Results
The chatbot delivers low-latency responses with high factual consistency using a low-temperature setting ($T=0.1$). Testing confirmed that the safety layer reliably triggers for harmful prompts, and the structured persona effectively organizes complex health information into a readable, professional format.
