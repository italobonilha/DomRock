## 2° Sprint

## 📌 DOR - Definition of Ready
-	1 - User Stories: As user storys devem estar claras e objetivas com critérios de aceitação bem definidos.
-	2 - Dados: Os dados precisam estar separados em grupos para que seja possível realizar o comparativo entre produtos
-	3 - Ambiente:  O ambiente de todos os integrantes deve estar configurado para testes de aplicação (inserção de datasets e modelos a serem usados).


## 🎯 Sprint Backlog

### 📄 User Stories e Critérios de Aceitação

| Rank | User Story | Critério de Aceitação |
|---|---|---|
| 2 | Desenvolvimento RAG/ FAISS: Como um representante da marca eu quero conseguir fazer perguntas sobre os detalhes (qualidade, performance, eficiência etc) dos produtos disponíveis na base de dados da B2W.| O sistema deve ser capaz de identificar na review características técnicas dos produtos de acordo com o paramêtro requisitado e devolver em linguagem natural.| 
| 3 | Integração com a base de dados/ Criação de Ranking com base nas avaliações: Como um representante da marca eu quero visualizar as médias de avaliação dos produtos disponíveis na base de dados da B2W e gerar rankings crescentes e decrescentes usando parâmetros como média geral, sentimentos, e atributos.|- O sistema deve gerar rankings com base nos parâmetros indicados <br>- O sistema deve separar os produtos em grupos e permitir o comparativo direto entre produtos de um mesmo grupo.| 
| 4 | Integração com a base de dados/ Análise de sentimento das reviews: Como um representante da marca eu quero saber quais produtos são mais e menos recomendados, identificando os sentimentos das reviews (positivo, neutro, negativo), para entender melhor as motivações dos consumidores.| O sistema deve classificar as reviews dos produtos em sentimentos (positivo, neutro, negativo) e gerar um texto justificando a classificação.| 
| 5 | Análise de padrões e satisfação do cliente: Como um representante da marca eu quero poder identificar padrões nas reviews sobre os produtos a fim de encontrar problemas recorrentes.| O sistema deve ser capaz de identificar palavras chaves recorrentes nas reviews dos produtos e fazer associações de termos (produto e defeito por ex.) para gerar um texto indicando o padrão encontrado.|
| 6 | Análise demográfica: Como um representante da marca eu quero entender a relação entre as avaliações e as características demográficas dos consumidores para poder personalizar minhas ações de vendas com base nas preferências e características de diferentes segmentos de público-alvo.| O sistema deve considerar os parâmetros demográficos (idade, sexo, região) requisitados a fim de gerar um gráfico que indique a relação demográfica x consumo do produto.|
  
#### 🖼️ Mockup
- Tela de Introdução
  ![Introdução](https://github.com/user-attachments/assets/1652c455-b996-4614-8db9-53f36e6ddc0d)

- Tela Home
  
![Principal](https://github.com/user-attachments/assets/b7342ee0-6e38-4633-9cac-6e1afcb1b72f)

- Exemplo de pergunta
![Pergunta](https://github.com/user-attachments/assets/adec5ef4-4edd-4ebb-92ff-4350650f42e4)

- Exemplo de Interação com o ChatBot 
![Exemplo de Resposta](https://github.com/user-attachments/assets/8d6e6a6f-f1be-4bbc-8686-aa9297f5bc08)

#### :cd: Dados 
Nessa entrega, usamos para a construção do chatbot com IA os dados do seguinte link: https://huggingface.co/datasets/ruanchaves/b2w-reviews01


#### 🖥️ Entrega

