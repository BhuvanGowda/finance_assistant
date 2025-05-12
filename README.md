# finance_assistant
 a multi-source, multi-agent finance assistant that delivers spoken  market briefs via a Streamlit app.

## structure

/finance_assistant
│
├── /data_ingestion
│   ├── api_agent.py
│   ├── scraping_agent.py
│   └── retriever_agent.py
│
├── /agents
│   ├── analysis_agent.py
│   ├── language_agent.py
│   └── voice_agent.py
│
├── /orchestrator
│   └── main.py
│
├── /streamlit_app
│   └── app.py
│
├── Dockerfile
├── requirements.txt
└── README.md