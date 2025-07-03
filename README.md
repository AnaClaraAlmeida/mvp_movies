# MVP - Análise Exploratória de Filmes (Letterbox)

##  Objetivo do Projeto

Este projeto tem como finalidade explorar o comportamento de popularidade dos filmes a partir de dados extraídos do dataset di Letterboxd. A análise é totalmente exploratória e busca verificar padrões de engajamento e avaliação com base em variáveis como gênero, idioma, duração e estúdio de produção.

## Dataset Utilizado

- **Fonte:** [Kaggle - Letterbox Dataset]([https://www.kaggle.com/](https://www.kaggle.com/datasets/sahilislam007/letterbox-movie-classification-dataset)
- **Registros:** 10.002 filmes
- **Atributos principais:**
  - Gênero
  - Duração (Runtime)
  - Idioma original
  - Número de visualizações, curtidas, fãs e avaliações (de 1★ a 5★)

## Hipóteses Investigadas

1. **Filmes do gênero Drama** são os que mais recebem curtidas.
2. **Filmes com duração entre 90 e 120 minutos** concentram mais avaliações 5★.
3. **Grandes estúdios priorizam filmes em inglês.**

## Metodologia

- Limpeza e pré-processamento dos dados
- Mapeamento e tratamento de valores nulos
- Padronização de variáveis categóricas
- Visualizações com gráficos para validação das hipóteses

## Conclusão

- Hipótese 1 (Drama como gênero mais engajador): Falsa. Apesar de popular, o gênero Musical tem maior média de curtidas por visualização.
- Hipótese 2 (Filmes entre 1h30 e 2h mais bem avaliados): Falsa. Filmes longos (3h ou mais) recebem proporcionalmente mais avaliações máximas.
- Hipótese 3 (Grandes estúdios priorizam filmes em inglês): Verdadeira. Estúdios como Warner, Disney e Universal produzem majoritariamente em inglês, reforçando foco global.

---

📎 Notebook completo: 
[MPV_AnaClara_4052025000825.ipynb](https://github.com/AnaClaraAlmeida/mvp_movies/blob/main/MPV_AnaClara_4052025000825.ipynb)
