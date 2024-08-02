# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Este é um repositório de estudo, criado a partir de um fork da DIO, com o objetivo de praticar os conhecimentos propostos no Bootcamp Nexa - Machine Learning na AWS. Mais especificamente, a proposta era o desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas.
## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

## 🚀 Passo a Passo

### 1. Selecionar Dataset

-  Da pasta `datasets` deste repositório, foi utilizado o arquivo *dataset-1000-com-preco-variavel-e-renovacao-estoque.csv*. 
-  Feito o upload do dataset no SageMaker Canvas.

### 2. Construir/Treinar

-   No SageMaker Canvas, importei o dataset.
-   Configurei as variáveis de entrada e saída de acordo com os dados.
-   Iniciei o treinamento do modelo, tendo como coluna-alvo, a QUANTIDADE_ESTOQUE
-   Para treinamento, foi utilizado o calendário de feriados do Brasil (HOLIDAY_BR) disponível.
-   O Quick build foi o método utilizado.

### 3. Analisar

-   Após o treinamento, as métricas de performance do modelo:
-     Avg. wQL: 0.344| MAPE: 0.936 | WAPE: 0.569 | RMSE: 34.950 | MASE: 0.832 | -   
- De acordo com a análise, a coluna PREÇO foi a que teve maior impacto na previsão da QUANTIDADE_ESTOQUE
- HOLIDAY_BR também apresentou impacto razoável: 12,5%

### 4. Prever

-   Use o modelo treinado para fazer previsões de estoque.
-   Exporte os resultados e analise as previsões geradas.
-   Documente suas conclusões e qualquer insight obtido a partir das previsões.

## 🤔 Dúvidas?

Esperamos que esta experiência tenha sido enriquecedora e que você tenha aprendido mais sobre Machine Learning aplicado a problemas reais. Se tiver alguma dúvida, não hesite em abrir uma issue neste repositório ou entrar em contato com a equipe da DIO.
