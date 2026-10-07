<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/cabecalho-escuro.svg">
  <img alt="Vinicius Candido, engenheiro de software: backend em Python e Node, IA aplicada a produto e chatbots de atendimento" src="assets/cabecalho-claro.svg" width="100%">
</picture>

<p>
  <a href="https://vlfcandido.github.io"><img alt="Portfólio" src="https://img.shields.io/badge/portf%C3%B3lio-vlfcandido.github.io-0b6b62?style=flat-square"></a>
  <a href="https://www.linkedin.com/in/viniciusf-candido"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-viniciusf--candido-0b6b62?style=flat-square&logo=linkedin&logoColor=white"></a>
</p>

Trabalho com backend há 13 anos e, nos últimos, com IA aplicada a produto: agentes, RAG e avaliação de LLM. Levo para isso o hábito de quem mantém sistema em produção: teste automatizado, observabilidade, segredo fora do código e nenhum efeito colateral no import.

## Stack

| | |
|---|---|
| **Backend** | <img alt="Python" src="https://img.shields.io/badge/Python-0b6b62?style=flat-square&logo=python&logoColor=white"> <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-0b6b62?style=flat-square&logo=fastapi&logoColor=white"> <img alt="SQLAlchemy 2.0" src="https://img.shields.io/badge/SQLAlchemy%202.0-0b6b62?style=flat-square&logo=sqlalchemy&logoColor=white"> <img alt="Pydantic v2" src="https://img.shields.io/badge/Pydantic%20v2-0b6b62?style=flat-square&logo=pydantic&logoColor=white"> <img alt="Node.js" src="https://img.shields.io/badge/Node.js-0b6b62?style=flat-square&logo=nodedotjs&logoColor=white"> <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-0b6b62?style=flat-square&logo=typescript&logoColor=white"> <img alt="Java" src="https://img.shields.io/badge/Java-0b6b62?style=flat-square&logo=openjdk&logoColor=white"> |
| **IA aplicada** | <img alt="LangGraph" src="https://img.shields.io/badge/LangGraph-0b6b62?style=flat-square&logo=langgraph&logoColor=white"> <img alt="LangChain" src="https://img.shields.io/badge/LangChain-0b6b62?style=flat-square&logo=langchain&logoColor=white"> <img alt="Google ADK" src="https://img.shields.io/badge/Google%20ADK-0b6b62?style=flat-square&logo=google&logoColor=white"> <img alt="LiteLLM" src="https://img.shields.io/badge/LiteLLM-0b6b62?style=flat-square"> <img alt="MCP" src="https://img.shields.io/badge/MCP-0b6b62?style=flat-square&logo=modelcontextprotocol&logoColor=white"> <img alt="Ragas e DeepEval" src="https://img.shields.io/badge/Ragas%20e%20DeepEval-0b6b62?style=flat-square"> |
| **Dados** | <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-0b6b62?style=flat-square&logo=postgresql&logoColor=white"> <img alt="pgvector" src="https://img.shields.io/badge/pgvector-0b6b62?style=flat-square&logo=postgresql&logoColor=white"> <img alt="Redis" src="https://img.shields.io/badge/Redis-0b6b62?style=flat-square&logo=redis&logoColor=white"> <img alt="SQLite" src="https://img.shields.io/badge/SQLite-0b6b62?style=flat-square&logo=sqlite&logoColor=white"> |
| **Infra** | <img alt="Docker" src="https://img.shields.io/badge/Docker-0b6b62?style=flat-square&logo=docker&logoColor=white"> <img alt="Google Cloud" src="https://img.shields.io/badge/Google%20Cloud-0b6b62?style=flat-square&logo=googlecloud&logoColor=white"> <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-0b6b62?style=flat-square&logo=githubactions&logoColor=white"> <img alt="Firebase" src="https://img.shields.io/badge/Firebase-0b6b62?style=flat-square&logo=firebase&logoColor=white"> |
| **Atendimento** | <img alt="WhatsApp Cloud API" src="https://img.shields.io/badge/WhatsApp%20Cloud%20API-0b6b62?style=flat-square&logo=whatsapp&logoColor=white"> <img alt="Chatbots" src="https://img.shields.io/badge/Chatbots-0b6b62?style=flat-square"> |

## Projetos em destaque

| projeto | o que é | stack |
|---|---|---|
| [**aprovaos**](https://github.com/vlfcandido/aprovaos) | Agente que conduz o estudo para concursos: diagnóstico, trilha, questões no estilo da banca e revisão espaçada. 1.622 testes. | FastAPI, SQLAlchemy 2.0, Pydantic |
| [**nexus-clips**](https://github.com/vlfcandido/nexus-clips) | Agente que monitora fontes, escolhe o assunto e gera cortes de vídeo com legenda e narração. | LangGraph, FastAPI, React |
| [**revisor-ia**](https://github.com/vlfcandido/revisor-ia) | Revisor de código em que cada resposta da IA é medida, não só gerada. | LangGraph, RAG, pgvector, MCP, Ragas |
| [**varredura-voos**](https://github.com/vlfcandido/varredura-voos) | Busca de passagens que ordena por duração total da viagem, não só por preço. 109 testes. | Python 3.13, httpx, Amadeus |
| [**engenharia-de-agentes**](https://github.com/vlfcandido/engenharia-de-agentes) | O mesmo agente em Pydantic puro, LangGraph e Google ADK, mais versões multiagente. Roda offline. | Pydantic, LangGraph, Google ADK |
| [**bot-pedidos-whatsapp-llm**](https://github.com/vlfcandido/bot-pedidos-whatsapp-llm) | Bot de pedidos por WhatsApp com roteador LLM, tools tipadas e transbordo humano (MVP). | Flask, SQLAlchemy, Postgres |

<details>
<summary><b>Estudos e exercícios técnicos</b></summary>

<br>

| projeto | o que é |
|---|---|
| [benchmark-litellm-sdk-proxy](https://github.com/vlfcandido/benchmark-litellm-sdk-proxy) | Latência, TTFT, erros e custo do LiteLLM SDK contra o LiteLLM Proxy, com painel em Streamlit. |
| [api-intervalo-premios-filmes](https://github.com/vlfcandido/api-intervalo-premios-filmes) | API REST que calcula o menor e o maior intervalo entre prêmios de produtores a partir de um CSV. |
| [previsao-tempo-chatbot](https://github.com/vlfcandido/previsao-tempo-chatbot) | Microserviço que reduz a previsão de três dias da WeatherAPI ao JSON que um chatbot exibe. |

</details>

## Como trabalho

- Decisão baseada na documentação oficial, registrada por escrito quando muda a arquitetura.
- Teste automatizado faz parte da entrega; o número de testes nos READMEs é o da última execução.
- Função pública com docstring, código tipado, configuração e segredo pelo ambiente.
- Com IA, o que conta é o que dá para medir: avaliação automática antes de trocar prompt ou modelo.

---

<sub>Mais detalhes, cases e contato em <a href="https://vlfcandido.github.io">vlfcandido.github.io</a>.</sub>
