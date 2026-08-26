# AI Delivery Assistant 

Select Language:
*  [English](#english) :us:
*  [Português](#português) :brazil:
---

## *English* :us:

## About
This repository contains an **AWS Step Functions** state machine definition using **JSONata** and **Amazon Bedrock (Nova Lite)** to automate a delivery service workflow.

The agent is responsible for:
1. **Extracting the customer order**: Analyzes the raw customer text and structures items, delivery address, and notes into JSON format.
2. **Planning the route**: Processes the extracted data to generate optimized delivery instructions.
3. **Generating the customer message**: Writes a polite, concise, and personalized communication based on the logistics plan.


<br><br>
## 🛠️ Technologies Used

* **AWS Step Functions**: Serverless workflow orchestration.
* **JSONata**: Native data query and transformation language for Step Functions.
* **Amazon Bedrock**: Generative AI platform.
* **Amazon Nova Lite (`amazon.nova-lite-v1:0`)**: Efficient foundation model used for natural language processing.


<br><br>
## 📂 Project Structure

* `assistente_delivery.json`: File containing the complete State Machine definition (Amazon States Language).


<br><br>
## 🚀 How to Run

1. Open the **AWS Step Functions** console.
2. Click **Create state machine**.
3. Select the option to author your code in **Definition** and choose the **JSONata** query language format.
4. Paste the contents of the `assistente_delivery.json` file into the editor.
5. Follow the prompts to create the machine, attaching the required permissions for Bedrock (`bedrock:InvokeModel`), and run a test execution with the default input.
<br><br>
---



## *Português* :brazil:

## Sobre

Este repositório contém a definição de uma máquina de estados do **AWS Step Functions** utilizando **JSONata** e **Amazon Bedrock (Nova Lite)** para automatizar o fluxo de atendimento de delivery. 

O agente é responsável por:
1. **Extrair o pedido do cliente**: Analisa o texto bruto do cliente e estrutura os itens, o endereço de entrega e as observações em formato JSON.
2. **Planejar a rota**: Processa os dados extraídos para gerar instruções de rota otimizadas.
3. **Gerar a mensagem para o cliente**: Redige uma comunicação educada, enxuta e personalizada com base no plano logístico.

<br><br>

## 🛠️ Tecnologias Utilizadas

* **AWS Step Functions**: Orquestração serverless do fluxo de trabalho.
* **JSONata**: Linguagem de consulta e transformação de dados nativa do Step Functions.
* **Amazon Bedrock**: Plataforma de IA generativa.
* **Amazon Nova Lite (`amazon.nova-lite-v1:0`)**: Modelo de fundação eficiente utilizado para o processamento de linguagem natural.

<br><br>

## 📂 Estrutura do Projeto

* `assistente_delivery.json`: Arquivo contendo a definição completa da Máquina de Estados (Amazon States Language).

<br><br>

## 🚀 Como Executar

1. Acesse o console do **AWS Step Functions**.
2. Clique em **Create state machine**.
3. Selecione a opção para escrever o código em **Definition** e escolha o formato **JSONata**.
4. Cole o conteúdo do arquivo `assistente_delivery.json` no editor.
5. Siga as instruções para criar a máquina associando as permissões necessárias para o Bedrock (`bedrock:InvokeModel`) e execute um teste com a entrada padrão.
