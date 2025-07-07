Instalar ollama

ollama pull nomic-embed-text
ollama pull deepseek-r1:14b
ollama pull deepseek-r1:32b

Usando python 3.12.3

Desde la carpeta backend: chroma run --host localhost --port 8001
Desde la carpeta backend: uvicorn main:app --reload
Desde la carpeta frontend: streamlit run app.py


