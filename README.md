# GenAI Legal Assistant for Indian SMEs

Sophisticated contract analyzer for employment/vendor/lease/etc. Risk scoring, clause extraction, summaries, templates. Local, confidential.

## Setup
1. `pip install -r requirements.txt`
2. `python -m spacy download en_core_web_sm`
3. `streamlit run app.py`

## Features
- Contract classification & entity extraction (spaCy/NLTK)
- Risk scoring (rule-based, extensible to LLM)
- Multilingual (English/Hindi normalization)
- PDF/DOCX/TXT input
- PDF reports & templates
- Audit trails (JSON)

## LLM Integration
Replace `llm_prompt` with Claude 3/GPT-4 API calls.

## Hosting
- GitHub repo: Upload folder
- Streamlit Cloud: Connect GitHub repo[citation:24][cite:33]
