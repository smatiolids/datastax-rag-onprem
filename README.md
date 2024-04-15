# DataStax Retrieval Augmented Generation - On Premise

## Stack

- Langchain
- CassIO
- Streamlit
- DataStax Enterprise (with Vector Search)
- Ollama + Mistral

## Como executar:

- Download Ollama
- Executar `ollama run mistral`
- Copiar o _env_sample para .env
- Preencher as variáveis
- Instalar dependencias com `pip install -r requirements.txt`
- Executar com `streamlit run app.py`