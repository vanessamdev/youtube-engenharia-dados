# YouTube Top 100 Songs 2025 - Análise com PySpark

Projeto de análise de dados utilizando PySpark e SQL para identificar as 25 músicas mais tocadas do YouTube em 2025.

## Requisitos do Sistema

- Python 3.8+
- Java 8, 11 ou 17 (necessário para Apache Spark)
- JAVA_HOME configurado nas variáveis de ambiente

## Dependências Python

| Pacote | Versão | Descrição |
|--------|--------|-----------|
| pyspark | >=3.5.0 | API Python para Apache Spark |
| jupyter | >=1.0.0 | Ambiente de notebooks interativos |
| ipykernel | >=6.0.0 | Kernel Python para Jupyter |
| py4j | >=0.10.9.7 | Ponte entre Python e Java (usado pelo PySpark) |

## Instalação

```bash
pip install -r requirements.txt
```

## Estrutura do Projeto

```
├── INFO/
│   └── projeto_info.md         # Documentação do projeto
├── analise_youtube.ipynb       # Notebook com a análise
├── youtube-top-100-songs-2025.csv
├── top_25_musicas_2025.txt     # Resultado da análise
├── requirements.txt
└── README.md
```

## Execução

1. Instale as dependências: `pip install -r requirements.txt`
2. Abra o notebook: `jupyter notebook analise_youtube.ipynb`
3. Execute todas as células
4. O resultado será salvo em `top_25_musicas_2025.txt`

## Observações

- O CSV contém campos multilinhas, por isso usamos `multiLine=True` na leitura
- A coluna `view_count` é convertida para `BIGINT` no SQL para ordenação correta

## Autor

Projeto desenvolvido para prática de PySpark e análise de dados.
