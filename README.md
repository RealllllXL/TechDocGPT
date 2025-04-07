# TechDocGPT - Automated Product Documentation Generator

**TechDocGPT** is a lightweight natural language processing (NLP) project that use OpenAI's GPT-3.5 to generate professional product descriptions from structured technical specifications. The tool simulates the process of drafting user manuals or datasheet content by leveraging prompt engineering and large language models (LLMs).



## :page_with_curl: Features

- Generates formal product descriptions from input specs
- Supports Chinese input and output
- Uses OpenAI GPT-3.5 Turbo API for language generation
- Simple and clean Gradio interface for live demo
- Customizable prompt structure for different technical writing styles


## :notebook: Tech Stack

- Python 3
- OpenAI GPT-3.5 Turbo (via OpenAI Python SDK)
- Prompt Engineering
- Gradio (for web UI)


## :file_folder: Setup & Installation
1. Install Dependencies
```bash
pip install openai gradio
```

2. Gain your own openai_api_keys
Enter site: https://platform.openai.com/
In API Dashboard, you can create your own api key

## :memo: Sample Input & Output
Input:
```bash
Product Name: SmartSensor  
Function: Real-time temperature monitoring  
Communication: ZigBee  
Application: Industrial automation environment  
```

Output:
```bash
SmartSensor is an industrial-grade temperature sensor that supports real-time monitoring via the ZigBee protocol. Designed for harsh environments, it ensures reliable data transmission and seamless integration with automation systems.
```



