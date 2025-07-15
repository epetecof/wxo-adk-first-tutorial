# Aprendendo a utilizar o ADK (Agent Development Toolkit) do watsonx Orchestrate

## Introdução
Neste guia, exploraremos como utilizar o ADK (Agent Development Toolkit) do watsonx Orchestrate para criar e gerenciar agentes de forma programática. Vamos abordar a configuração do ambiente, a criação de componentes essenciais como Knowledge Bases, Tools e Agents, e como testar esses agentes através da API.

Este guia é é especialmente relevante para:
1. **Desenvolvedores de IA**: Que desejam automatizar a criação de agentes e integrá-los em suas aplicações.
2. **Profissionais de TI**: Que buscam entender como o watsonx Orchestrate pode ser utilizado para criar soluções de automação.
3. **Entusiastas de Tecnologia**: Que querem explorar as capacidades do watsonx Orchestrate e do ADK.

## O que são Agentes, Tools e Knowledge Bases?
Agentes de IA são sistemas que realizam tarefas de forma autônoma, utilizando ferramentas e bases de conhecimento para responder pergunta, tomar decisões e executar ações. Eles são compostos por:
1. **Tools**: Ferramentas que os agentes utilizam para realizar suas tarefas, como APIs ou funções específicas.
2. **Knowledge Bases**: Bases de conhecimento que armazenam informações relevantes para os agentes, permitindo que eles acessem dados e informações necessárias para suas operações.

## O que é o ADK?
O Agent Development Kit (ADK) é uma ferramenta fornecida pela IBM para criar agentes e ferramentas para o watsonx Orchestrate. O ADK permite que os desenvolvedores criem agentes personalizados e escaláveis de forma programática, utilizando uma interface de linha de comando e uma estrutura de desenvolvimento.

## O que existe nesse repositório:
Este repositório contém o notebook [Aprendendo a utilizar o ADK (Agent Development Toolkit) do watsonx Orchestrate](https://github.com/epetecof/wxo-adk-first-tutorial/blob/main/Aprendendo%20a%20utilizar%20o%20ADK%20(Agent%20Development%20Toolkit)%20do%20watsonx%20Orchestrate.ipynb) que demonstra como utilizar o ADK para criar e gerenciar agentes no watsonx Orchestrate. O notebook aborda a configuração do ambiente, a criação de componentes essenciais como Knowledge Bases, Tools e Agents, e como testar esses agentes através da API.
Além disso, o repositório também contém um arquivo PDF de exemplo da bula do medicamento Buscoduo, que é utilizado como base de conhecimento para o agente criado no notebook. Esse arquivo foi obtido no [bulário do Ministério da Saúde](https://consultas.anvisa.gov.br/#/bulario/q/?nomeProduto=BUSCODUO). Você pode usar e testar outros documentos de sua escolha também.

## Requisitos
Para executar o notebook, você precisará:
1. Ter uma conta na IBM Cloud com acesso ao watsonx Orchestrate.
2. Ter uma chave de API válida para autenticação.
3. (Opcional) Ter acesso ao watsonx.ai Studio para execução do Notebook na IBM Cloud