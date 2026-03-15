# Miniguia de Estudos — Agentes de Inteligência Artificial

Projeto desenvolvido como parte do desafio da DIO - Bootcamp GenAI & Dados (Bradesco), com o objetivo de explorar o uso da Inteligência Artificial como ferramenta de aprendizagem ativa utilizando o NotebookLM.

---

# Contexto e Objetivos

Este projeto tem como objetivo estudar e organizar conhecimentos sobre Agentes de Inteligência Artificial, utilizando ferramentas de IA (NotebookLM) para apoiar o aprendizado e a organização do conhecimento.

Objetivos do projeto:

* Compreender o conceito de agentes de Inteligência Artificial
* Identificar os principais tipos de agentes
* Entender como funcionam raciocínio e planejamento
* Explorar desafios éticos e de segurança
* Criar um material de estudo estruturado com apoio da IA

---

# Curadoria de Fontes

As seguintes fontes abertas foram utilizadas no estudo e adicionadas ao NotebookLM:

1. https://cloud.google.com/discover/what-are-ai-agents?hl=pt-BR
2. https://www.ibm.com/br-pt/think/topics/ai-agents
3. https://aws.amazon.com/pt/what-is/ai-agents/
4. https://www.dio.me/articles/ai-agents-a-revolucao-dos-sistemas-autonomos-087e57a8fc01

Esses materiais foram selecionados por apresentarem conteúdos introdutórios confiáveis sobre Inteligência Artificial e agentes inteligentes.

---

# Engenharia de Prompts

OBS: Durante o uso do NotebookLM foram realizados testes com diferentes prompts para obter respostas mais claras e organizadas.

### Prompt 1 

**Qual é a principal diferença entre IAs básicas e agentes?**

Resultado: A principal diferença está na autonomia e na capacidade de planejamento.

* IA básica (Executa tarefas específicas, Responde apenas a comandos e Possui pouca adaptação)

* Agentes de IA (Operam com autonomia, Planejam etapas para atingir objetivos e Interagem com ferramentas externas)

---

### Prompt 2

**Como funcionam o raciocínio e o planejamento dos agentes autônomos?**

Resultado: Os agentes utilizam modelos de linguagem (LLMs) para dividir tarefas complexas em subtarefas, planejar a sequência de ações e avaliar os resultados obtidos.

* Ciclo contínuo de decisão: Pensar → Agir → Observar → Ajustar
* Esse modelo é conhecido como ReAct (Reasoning + Acting).

---

### Prompt 3

**Quais são os maiores desafios éticos e de segurança dos agentes?** 

Resultado:

* Desafios de Segurança (risco de vazamento de dados sensíveis, comportamentos imprevisíveis, vulnerabilidades em sistemas multiagentes e possibilidade de ciclos infinitos de execução)

* Desafios Éticos (viés nos dados de treinamento, ausência de julgamento moral, dificuldade de interpretar emoções humanas e desafios de responsabilidade legal)

---

### Prompt 4

Crie um glossário com os principais termos relacionados a agentes de IA.

Resultado:
Foram geradas definições dos principais conceitos relacionados com o tema.

---

# Dificuldades Encontradas

* Foi observado na prática que dependendo do prompt utilizado, a IA retorna respostas muito genéricas e/ou muito extensas.
* Soluções aplicadas: tornar os prompts mais específicos e solicitar a saída de dados estruturadas em tópicos

Exemplo de melhoria de prompt:

* **Antes:** Explique sistemas multiagentes.
* **Depois:** Explique sistemas multiagentes em três partes: definição, benefícios e exemplos de aplicação no mercado. 

Resposta mais didática, bem estruturada e contendo exemplos práticos de aplicação no mercado.

---

# Miniguia de Estudo

Este Miniguia de Estudo foi consolidado com base nas fontes fornecidas para oferecer uma visão abrangente e técnica sobre o universo dos agentes de IA.

--------------------------------------------------------------------------------

## Resumos Estruturados do Assunto
**O que são Agentes de IA?**
* Um agente de inteligência artificial é um sistema de software que utiliza a IA para alcançar objetivos e concluir tarefas em nome dos usuários, demonstrando autonomia, planejamento e memória
* Diferente das IAs básicas (ou Narrow AI), que são estáticas e reativas a comandos específicos, os agentes são dinâmicos e proativos, capazes de decompor metas complexas em subtarefas e agir de forma independente para atingir o resultado final

**Arquitetura e Funcionamento**
* A estrutura de um agente inteligente é composta por quatro pilares principais:
* O "Cérebro" (LLM): Modelos de fundação (como GPT ou Claude) que permitem ao agente interpretar linguagem, raciocinar e tomar decisões
* Módulo de Planejamento: Permite que o agente divida metas em etapas menores e sequenciadas logicamente
* Módulo de Memória: Retém informações de curto prazo (histórico imediato) e de longo prazo (conhecimentos acumulados e dados históricos) para garantir continuidade e personalização
* Integração de Ferramentas: Conecta o agente a APIs, bancos de dados e softwares externos, permitindo que ele execute ações no mundo real, como enviar e-mails ou consultar o clima

**Paradigmas de Raciocínio**
* ReAct (Reasoning + Acting): O agente alterna entre pensar e agir, criando ciclos de "pensar-agir-observar" para resolver problemas passo a passo e corrigir rotas iterativamente
* ReWOO (Reasoning Without Observation): O agente planeja todas as etapas de uma vez antes de executá-las, o que economiza recursos computacionais ao evitar redundâncias no uso de ferramentas

**Desafios e Ética**
* Apesar dos benefícios em produtividade e redução de custos, a implementação enfrenta barreiras como preocupações com a privacidade de dados, risco de alucinações (respostas incorretas) e a falta de bússola moral em decisões de alto risco (saúde ou judiciário)
* A prática de Human-in-the-Loop (HITL) é recomendada para garantir supervisão humana em decisões críticas


--------------------------------------------------------------------------------

## Glossário de Conceitos Principais

* **Autonomia:** Capacidade de agir e tomar decisões de forma independente, sem supervisão humana contínua

* **Sistemas Multiagentes (MAS):** Um conjunto de vários agentes que colaboram ou competem para resolver problemas complexos que um único agente não conseguiria lidar sozinho

* **Proatividade:** Capacidade de antecipar eventos e tomar iniciativa com base em previsões, em vez de apenas reagir a entradas

* **Tool Calling (Chamada de Ferramenta):** O processo pelo qual o agente identifica e utiliza funções externas (como APIs) para coletar dados ou realizar tarefas

* **LangChain:** Framework utilizado para orquestrar agentes, permitindo "encadear" módulos de memória, prompts e ferramentas

* **RAG (Retrieval-Augmented Generation):** Técnica que permite ao agente consultar documentos externos atualizados para embasar suas respostas, aumentando a confiabilidade

* **Persona:** Definição do papel, personalidade e estilo de comunicação do agente para garantir comportamento consistente
  

--------------------------------------------------------------------------------

## Conjunto de Prompts Reutilizáveis para Revisão

Estes prompts podem ser utilizados em ferramentas de IA para aprofundar ou revisar o conteúdo deste guia:

* **Para Comparação:** "Explique as 3 principais diferenças entre um chatbot reativo básico e um agente de IA autônomo, utilizando a analogia do chef de cozinha citada nas fontes."

* **Para Arquitetura:** "Liste os quatro componentes principais da arquitetura de um agente de IA e descreva a função do módulo de memória de longo prazo."

* **Para Tipologia:** "Quais são as diferenças entre um agente de reflexo simples e um agente baseado em utilidade? Dê um exemplo prático para cada um."

* **Para Ética e Segurança:** "Quais são os principais riscos de segurança ao integrar agentes de IA a bancos de dados corporativos e quais estratégias podem mitigar o vazamento de dados?"

* **Para Metodologia:** "Compare os paradigmas ReAct e ReWOO. Em que situação o ReWOO seria mais vantajoso para uma empresa em termos de custo computacional?"

--------------------------------------------------------------------------------

# Conclusão

* O desenvolvimento deste projeto permitiu explorar de forma prática o conceito de Agentes de Inteligência Artificial, compreendendo como esses sistemas evoluem além das IAs tradicionais ao incorporar autonomia, raciocínio e capacidade de interação com diferentes ferramentas e ambientes.

* O uso de ferramentas de IA como o NotebookLM mostrou-se útil para analisar conteúdos de diferentes fontes, realizar experimentos com prompts, organizar conhecimento, gerar resumos e criar materiais de revisão de forma eficiente. Esse processo demonstra como a Inteligência Artificial pode ser utilizada como uma ferramenta de aprendizado.

* Além disso, este projeto também destacou a importância da engenharia de prompts, da curadoria de fontes confiáveis e da reflexão crítica sobre desafios éticos e de segurança associados a essas tecnologias.

* Como resultado final, foi construído um miniguia contendo um resumo estruturado de estudo, um glossário técnico e um conjunto de prompts reutilizáveis que possam apoiar futuras revisões sobre o tema.

* Esse exercício reforça como o uso estratégico de ferramentas de IA pode potencializar o aprendizado contínuo na área de tecnologia.

---
