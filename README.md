# AREP-RAGproject

## Sistema RAG -> Cómo Entrenar a tu Dragón

## Descripción

Sistema RAG que responde preguntas sobre la saga animada usando Pinecone y OpenAI.

## Arquitectura

- **Vector DB**: Pinecone (serverless)
- **Embeddings**: OpenAI text-embedding-3-small
- **LLM**: GPT-3.5-turbo
- **Retriever**: Top-2 similarity search

## Instalación

```bash
python -m venv venv
venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

Crear `.env`

Ejecutar:

```bash
python rag_system.py
```

## Ejemplo Output

- temperature=0
- temperature=0.7
- temperature=1

## Estructura

```
AREP-RAGproject/
├── .env
├── requirements.txt
├── rag_system.py
├── data/
│   └── documento.txt
└── README.md
```
