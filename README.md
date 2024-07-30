# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)
Experiência desse novo desafio:
1 - Acompanhei passo a passo de cada etapa de como configurar a AWS e ML e achei um absurdo de legal como uma plataforma usa a forma de NoCODE.
2 - Usei a tabular PREÇO PROMOCIONAL E RENOVAÇAO DE ESTOQUE
3 - Selecionei a coluna PREÇO para análise.
4 - Fiz a análise dos dados, obtendo as seguintes métricas:
Métricas de avaliação que ajudam a entender a performance do modelo de previsão.

Avg. wQL (Average Weighted Quantile Loss):
É uma métrica usada para avaliar modelos de previsão quantílica. Ela mede a qualidade das previsões ao comparar os quantis previstos com os valores reais. Valores mais baixos indicam melhor performance.

MAPE (Mean Absolute Percentage Error):
É a média dos erros percentuais absolutos entre os valores previstos e os valores reais. Um MAPE de 1.000 indica que, em média, o modelo tem um erro de 100%. Idealmente, esse valor deve ser o mais baixo possível.

WAPE (Weighted Absolute Percentage Error):
É uma variação do MAPE que leva em consideração o peso dos diferentes itens. Ele oferece uma visão ponderada do erro percentual absoluto. Assim como o MAPE, valores mais baixos indicam uma melhor performance.

RMSE (Root Mean Square Error):
É a raiz quadrada da média dos erros quadráticos. Ele mede a magnitude do erro entre os valores previstos e os valores reais. Valores mais baixos indicam previsões mais precisas.

MASE (Mean Absolute Scaled Error):
Compara o erro absoluto médio do modelo com o erro absoluto médio de um modelo de referência simples, como a média histórica. Um valor de MASE menor que 1 indica que o modelo de previsão é melhor que o modelo de referência.
Essas métricas ajudam a avaliar a precisão e a confiabilidade do modelo de previsão usado na análise dos dados. Aqui está um resumo para facilitar:

Avg. wQL (0.794): Avaliação da qualidade das previsões quantílicas.
MAPE (1.000): Média dos erros percentuais absolutos (100% de erro em média).
WAPE (1.090): Erro percentual absoluto ponderado.
RMSE (615.634): Magnitude do erro entre valores previstos e reais.
MASE (0.958): Comparação do erro com um modelo de referência (menos de 1 indica boa performance).
Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Siga os passos abaixo para completar o desafio!

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).


## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

- Dê um fork neste projeto e reescreva este `README.md`. Sinta-se à vontade para detalhar todo o processo de criação do seu Modelo de ML para uma "Previsão de Estoque Inteligente".
- Para isso, siga o [passo a passo] descrito a seguir e evolua as suas habilidades em ML no-code com o Amazon SageMaker Canvas.
- Ao concluir, envie a URL do seu repositório com a solução na plataforma da DIO.


## 🚀 Passo a Passo

### 1. Selecionar Dataset

-   Navegue até a pasta `datasets` deste repositório. Esta pasta contém os datasets que você poderá escolher para treinar e testar seu modelo de ML. Sinta-se à vontade para gerar/enriquecer seus próprios datasets, quanto mais você se engajar, mais relevante esse projeto será em seu portfólio.
-   Escolha o dataset que você usará para treinar seu modelo de previsão de estoque.
-   Faça o upload do dataset no SageMaker Canvas.

### 2. Construir/Treinar

-   No SageMaker Canvas, importe o dataset que você selecionou.
-   Configure as variáveis de entrada e saída de acordo com os dados.
-   Inicie o treinamento do modelo. Isso pode levar algum tempo, dependendo do tamanho do dataset.

### 3. Analisar

-   Após o treinamento, examine as métricas de performance do modelo.
-   Verifique as principais características que influenciam as previsões.
-   Faça ajustes no modelo se necessário e re-treine até obter um desempenho satisfatório.

### 4. Prever

-   Use o modelo treinado para fazer previsões de estoque.
-   Exporte os resultados e analise as previsões geradas.
-   Documente suas conclusões e qualquer insight obtido a partir das previsões.

## 🤔 Dúvidas?

Esperamos que esta experiência tenha sido enriquecedora e que você tenha aprendido mais sobre Machine Learning aplicado a problemas reais. Se tiver alguma dúvida, não hesite em abrir uma issue neste repositório ou entrar em contato com a equipe da DIO.
