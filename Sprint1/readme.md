## 1° Sprint

## 🎯 Backlog da Sprint

| Rank | Prioridade | User Story                                                                                                                                                                                                                 | Sprint | Estimativa | Requisitos Relacionados          |
|------|------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|------------|----------------------------------|
| 1    | Alta       | Como um representante da marca, eu quero que o sistema colete dados de reviews de produtos da base da B2W, para garantir que as informações sejam atualizadas e precisas.                                                 | 1      | 8          | RF1                              |
| 2    | Alta       | Como um representante da marca, eu quero que o sistema realize a limpeza de dados, eliminando duplicatas e corrigindo valores ausentes, para que eu tenha dados confiáveis para análise.                                   | 1      | 34          | RF1                               |
| 3    | Alta       | Como um representante da marca, eu quero que o sistema converta os reviews pré-processados em embeddings, para facilitar a recuperação de informações relevantes.                                                             | 1      | 8          | RF2                               |
| 4    | Média       | Como um representante da marca, eu quero visualizar a média de avaliação geral do produto solicitado para que eu possa ter uma visão clara do desempenho dos consumidores sobre a marca.                                  | 1      | 5          | RF6, RF4                          |
| 5    | Alta       | Como um representante da marca, eu quero identificar os produtos com as melhores e piores médias de avaliação para que eu possa direcionar ações de melhoria e destaque para os produtos.                                | 1      | 3          | RF6, RF4                          |
| 6  | Alta       | Como um representante da marca, eu quero que o sistema classifique os produtos com base em sentimentos extraídos dos reviews, para que eu possa entender melhor as motivações dos consumidores.                           | 1      | 8          | RF6                               |

## 📌 DOR - Definition of Ready

### 📄 User Stories e Critérios de Aceitação

#### US1: Como um representante da marca, eu quero que o sistema colete dados de reviews de produtos da base da B2W, para garantir que as informações sejam atualizadas e precisas.
Critérios de Aceitação:
- CA1: O sistema deve conectar-se à base da B2W e coletar os dados de reviews de produtos.
- CA2: Os dados coletados devem ser verificados para garantir que não estão desatualizados.
- CA3: O sistema deve informar ao usuário se a coleta foi bem-sucedida ou se houve algum erro.
  
#### US2: Como um representante da marca, eu quero que o sistema realize a limpeza de dados, eliminando duplicatas e corrigindo valores ausentes, para que eu tenha dados confiáveis para análise.
Critérios de Aceitação:
- CA1: O sistema deve identificar e remover duplicatas nos dados coletados.
- CA2: O sistema deve corrigir valores ausentes de forma adequada, utilizando regras definidas.
- CA3: O sistema deve gerar um relatório detalhando as ações de limpeza realizadas.
  
#### US3: Como um representante da marca, eu quero que o sistema converta os reviews pré-processados em embeddings, para facilitar a recuperação de informações relevantes.
Critérios de Aceitação:
- CA1: O sistema deve converter os reviews em embeddings utilizando técnicas de processamento de linguagem natural.
- CA2: Os embeddings devem ser armazenados em um banco de vetores (ex: ChromaDB ou FAISS).
- CA3: O sistema deve validar a integridade dos embeddings gerados.
  
#### US4: Como um representante da marca, eu quero visualizar a média de avaliação geral do produto solicitado para que eu possa ter uma visão clara do desempenho dos consumidores sobre a marca.
Critérios de Aceitação:
- CA1: O sistema deve permitir que o usuário faça perguntas sobre a média de avaliações de produtos específicos.
- CA2: O sistema deve buscar as avaliações do produto solicitado e calcular a média corretamente.
- CA3: A resposta deve ser apresentada em linguagem natural, indicando a média de avaliação do produto.

#### US5: Como um representante da marca, eu quero identificar os produtos com as melhores e piores médias de avaliação para que eu possa direcionar ações de melhoria e destaque para os produtos.
Critérios de Aceitação:
- CA1: O sistema deve entender perguntas sobre a identificação de produtos com melhores e piores médias de avaliação.
- CA2: O sistema deve calcular as médias de avaliação de todos os produtos disponíveis.
- CA3: A resposta deve apresentar os produtos com as melhores e piores médias de forma clara em linguagem natural.
  
#### US6: Como um representante da marca, eu quero que o sistema classifique os produtos com base em sentimentos extraídos dos reviews, para que eu possa entender melhor as motivações dos consumidores."
Critérios de Aceitação:
- CA1: Identificar produtos com maior e menor número de recomendações  
- CA2: Deve apresentar as razões por trás das recomendações de forma clara 
- CA3: O sistema deve permitir perguntas sobre produtos recomendados, com respostas claras e concisas
  
#### 🖼️ Wireframe

#### :cd: Dados 
Nessa entrega, usamos para a construção do chatbot com IA os dados do seguinte link: https://huggingface.co/datasets/ruanchaves/b2w-reviews01


#### 🖥️ Entrega