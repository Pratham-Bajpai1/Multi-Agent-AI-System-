# AI-Powered Multi-Agent Use Case Generator
---

## Overview
The AI-Powered Multi-Agent Use Case Generator is a dynamic and intelligent system designed to assist companies and industries in exploring innovative AI/ML use cases tailored to their specific needs. This system employs multiple agents for market research, use case generation, and resource asset collection, delivering insights in a professional report format. Built using Python and Streamlit, the system ensures an interactive and user-friendly experience.

### Live URL: [Multi Agent AI System](https://wbewqc4bzmvbpugiwnlp7y.streamlit.app/)

### Screenshot:

![Screenshot 2024-12-09 003210](https://github.com/user-attachments/assets/67c97b05-de8a-48bb-be46-2297b0d8fb86)

---

## Features

**1. Market Research Agent:**
- Conducts in-depth market research for a given company and industry.
- Analyzes key findings, market positioning, and competitor strategies.
- Sources credible data from industry reports and expert analyses.

**2. AI Use Case Generator:**
- Leverages large language models (LLMs) like Cohere or Hugging Face.
- Generates tailored AI/ML use cases with descriptions, benefits, and strategic 
  alignments.
- Outputs the top 10 use cases based on company goals and industry challenges.

**3.Dataset Collector:**
- Identifies relevant datasets from platforms like Kaggle and Hugging Face.
- Provides links to datasets for further exploration and development.

**4. Professional Reporting:**
- Generates a **Market Research Report** in Excel format.
- Creates a Use **Case Feasibility Report** in Word format with structured headings, 
  descriptions, and datasets.

**5. Streamlit Interface:**
- Interactive form-based input for user details (company and industry).
- Displays generated use cases in a visually organized layout.
- Provides downloadable reports for easy access and sharing.

---

## Project Structure
```
Multi Agent AI System/
├── main.py               # Main Streamlit application
├── agents.py             # Implementation of ResearchAgent, UseCaseGenerator, and DatasetCollector
├── report_generator.py   # Report generation logic for Excel and Word formats
├── utils.py              # Utility functions for API integrations
├── requirements.txt      # Python dependencies
├── .env                  # Environment variables for API keys
└── README.md             # Project documentation (this file)
```
---

## Architecture Flowchart

![Blank diagram - Page 1](https://github.com/user-attachments/assets/b314cb0d-e8f7-4db1-ba49-8601aa48dbc4)


---

## Prerequisites
Ensure the following dependencies are installed on your system:

- Python 3.8 or above
- Required libraries (listed in `requirements.txt`)

Set up environment variables in a `.env` file with your API keys:

```
COHERE_API_KEY=<Your Cohere API Key>
SERP_API_KEY=<Your SerpAPI Key>
```
---

## Installation and Usage

**1. Clone the Repository:**
```
git clone https://github.com/Pratham-Bajpai1/Multi-Agent-AI-System-
cd Multi-Agent-AI-System
```

**2. Install Dependencies:**
```
pip install -r requirements.txt
```

**3. Run the Application:**
```
streamlit run main.py
```

**4. Input Details:**
- Enter the company name and industry in the provided 
  form.
- Click **Generate Use Cases** to start the process.

**5. Download Reports:**

- After generation, download the **Market Research 
  Report (Excel)** and **Use Case Feasibility Report 
  (Word)** using the download buttons.

---

##  Outputs
**1. Market Research Report (Excel)**
- Key findings on the company's market positioning, 
  strategies, and innovations.
- Includes data on AI/ML adoption, competitor 
  strategies, and industry trends.

**2. Use Case Feasibility Report (Word)**
- Detailed descriptions of AI/ML use cases with associated benefits.
- Includes datasets from Kaggle and Hugging Face for 
  implementation.

---

## Key Components

**1. Market Research Agent (ResearchAgent)**
- Uses SerpAPI for web search and extracts key 
  findings 
  from organic results.
- Example Query: "Conduct market research for OpenAI 
  in Artificial Intelligence."

**2. AI Use Case Generator (UseCaseGenerator)**
- Integrates with Cohere API for generating innovative 
  use cases.
- Produces structured outputs with titles, 
  descriptions, and benefits.

**3. Dataset Collector (DatasetCollector)**
- Collects datasets relevant to the specified 
  industry.
- Example Outputs:
  - Platform: Kaggle, URL: https://www.kaggle.com/search?q=artificial+intelligence
  - Platform: Hugging Face, URL: https://huggingface.co/models?search=artificial+intelligence

**4. Report Generator (report_generator.py)**
- Formats reports using pandas (Excel) and python-docx 
  (Word).
- Implements professional styling and structured content for clarity.

---

## Acknowledgments

- **Streamlit** for providing a seamless UI framework.
- **Cohere, Hugging Face,** and **SerpAPI** for their 
  APIs and services.
- **Python Libraries:** pandas, python-docx, requests, dotenv, and more.

---
