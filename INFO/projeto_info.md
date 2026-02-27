# Projeto: Análise de Dados - YouTube Top 100 Songs 2025

## Objetivo
Analisar o dataset das 100 músicas mais populares do YouTube em 2025 utilizando PySpark e SQL, gerando um arquivo com as 25 músicas mais tocadas.

## Tecnologias
- Python 3.x
- PySpark (Apache Spark)
- Jupyter Notebook / IPython

## Estrutura do Dataset
O arquivo `youtube-top-100-songs-2025.csv` contém as seguintes colunas:
- `title`: Título do vídeo
- `fulltitle`: Título completo
- `description`: Descrição do vídeo
- `view_count`: Número de visualizações
- `categories`: Categoria do vídeo
- `tags`: Tags associadas
- `duration`: Duração em segundos
- `duration_string`: Duração formatada
- `live_status`: Status de transmissão ao vivo
- `thumbnail`: URL da thumbnail
- `channel`: Nome do canal
- `channel_url`: URL do canal
- `channel_follower_count`: Número de seguidores do canal

## Saída Esperada
Arquivo `top_25_musicas_2025.txt` contendo a lista das 25 músicas mais tocadas ordenadas por `view_count`.
