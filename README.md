# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Desafio de projeto "Previsão de Estoque Inteligente" na AWS com SageMaker Canvas. Neste Lab do Bootcamp da DIO, o objetivo é conhecer e explorar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). 

## ☁️ SageMaker
Amazon SageMaker é um serviço de aprendizado de máquina (Machine Learning) totalmente gerenciado oferecido pela Amazon Web Services (AWS). Ele permite que desenvolvedores e cientistas de dados criem, treinem e implantem modelos de aprendizado de máquina rapidamente e em escala.<br>
O SageMaker oferece uma ampla gama de ferramentas e funcionalidades que cobrem todas as etapas do ciclo de vida do aprendizado de máquina, desde a preparação de dados até o treinamento, ajuste de hiperparâmetros, implantação e monitoramento de modelos.

## 📖 Aprendizados

- Conhecimento sobre IA Generativa e Machine Learning
- Conhecimento do SageMaker Canvas e suas funcionalidades
- Criar modelos de machine learning utilizando o SageMaker Canvas
- Utilizar IA Generativa (Amazon Bedrock) para criar um modelo de machine learning para fornecedor como DataSet ao SageMaker Canvas
- Desenvolver, sem código, um modelo de machine learning e treiná-lo configurando as variáveis de entrada e saída.

## 🚀 Passo a Passo

### 1. Selecionar Dataset (Select)

-   Escolher um dataset para treinar o modelo de previsão de estoque.
-   Realizar o upload do dataset no SageMaker Canvas.
-   Para este projeto, foi utilizado um dataset em formato .csv, porém a plataforma da AWS disponibiliza diversas fontes de dados, inclusives outros serviços da AWS (S3, RDS, DynamoDb)

  ![image](https://github.com/user-attachments/assets/9c399e18-85a2-447c-89cb-ca4d96822926)

### 2. Construir/Treinar (Build)

-   Configurar as variáveis de entrada e saída de acordo com os dados.
-   Iniciar o treinamento do modelo.

  ![image](https://github.com/user-attachments/assets/c678a56f-f694-4583-8cf9-92e83938febf)


### 3. Analisar (Analyze)

-   Examinar as métricas de performance do modelo.
-   Verificar as principais características que influenciam as previsões.

  ![image](https://github.com/user-attachments/assets/7d5f4b5a-fded-4903-9f13-e234770a49e2)


### 4. Prever (Predict)

-   Usar o modelo treinado para fazer previsões de estoque.
-   Exportar os resultados.

  ![image](https://github.com/user-attachments/assets/cf4e2f05-909a-4078-97ce-830c0cae4e70)


## 📈 Análise das Métricas 

Foram geradas três percentis de previsão (P10, P50 e P90) para o estoque dos produtos. Através dessas previsões, é possível observar as possibilidades de comportamento do estoque e traçar as estratégias adequadas para gestão do negócio.
<br>
Por utilizar a versão Free Tier da AWS, foi gerada uma versão simplificada da predição (single prediction). 
<br>
<br>
<b>Exemplo de análise gerada pelo SageMaker:<b>
<br>
![single_prediction_results](https://github.com/user-attachments/assets/2d885666-d553-41bf-971c-ae4d289ac742)


## 👩🏽‍💻 Tecnologias 

Amazon Web Services - SageMaker Canvas e Amazon Bedrock
