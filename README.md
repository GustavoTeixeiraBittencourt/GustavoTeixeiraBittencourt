# Gustavo Teixeira Bittencourt de Oliveira

**Software Engineer com foco em GenAI**

Atuando como Engenheiro de Software no Comando Geral da Polícia Militar do Pará, onde desenvolvo sistemas internos de ponta a ponta com foco educacional (como o PICC, com mais de 10 mil usuários).

---

## Projetos em destaque

### [Sistema multiagente com RAG e busca web como fallback](https://github.com/GustavoTeixeiraBittencourt/processo-seletivo-2026)

Seis agentes em LangGraph respondem perguntas sobre documentação, com busca híbrida (BM25 + RRF) e um verificador de fundamentação. No teste, 100% de acerto na decisão de fallback e 83,3% de respostas fundamentadas. `Python` `LangGraph` `ChromaDB` `Groq` `Tavily` `Streamlit` `Docker`

### [Agente de atendimento ao cliente com function calling](https://github.com/GustavoTeixeiraBittencourt/emporio-agent)

Agente conversacional em português para uma loja de instrumentos musicais fictícia, com 7 ferramentas sobre dados em CSV e um manual de políticas. O modelo decide quando chamar cada ferramenta; o código decide o que é permitido e faz todo o cálculo (preço, estoque, parcelamento, prazo de devolução). Recuperação de políticas com BM25 próprio, privacidade garantida em código (o modelo nunca vê contato do cliente nem estoque exato) e mais de 60 testes automatizados que rodam sem rede. `Python` `Function calling` `BM25` `Groq` `pytest`

### [Simulated Annealing vs. Gradient Boosting](https://github.com/GustavoTeixeiraBittencourt/simulated-annealing-vs-gradient-boosting)

Comparação de algoritmos de busca local (roteamento de veículos elétricos) e de classificação de crédito (C4.5, CART e Gradient Boosting), com testes estatísticos e 60 testes automatizados. Projeto acadêmico em grupo. `Python` `scikit-learn` `SciPy` `Pandas` `pytest`

### [Maré: analisador léxico e sintático de uma linguagem própria](https://github.com/GustavoTeixeiraBittencourt/Mare-analisador-lexico-e-sintatico)

Scanner com expressões regulares e parser descendente recursivo, em Python puro (sem ANTLR, PLY ou Bison), para uma linguagem imperativa tipada com palavras-chave em português. Gera a árvore sintática, reporta erros com linha e coluna e se recupera deles em modo pânico. Projeto acadêmico em grupo. `Python` `Regex` `Parser descendente recursivo` `AST` `unittest`

### [Aplicação de analytics com assistente em linguagem natural](https://github.com/GustavoTeixeiraBittencourt/Cambara-Empreendimentos)

Aplicação full stack sobre uma base de negócio com mais de 9 mil registros e inconsistências reais: 4 indicadores auditáveis, registro transacional de vendas e distratos, painel de qualidade de dados e um assistente text-to-SQL (LLM) restrito a consultas de leitura, com log de auditoria da consulta usada em cada resposta. `Python` `Streamlit` `SQLite` `Groq` `pandas` `pytest`

### [ACERVO: leilão online com lances em tempo real e histórico auditável](https://github.com/GustavoTeixeiraBittencourt/Acervo-leilao)

Casa de leilões full stack com obras do acervo aberto do Cleveland Museum of Art, com [demo no ar](https://acervo-leilao.vercel.app). Lances em tempo real via SSE, anti-sniping, carteira com saldo comprometido, liquidação idempotente por worker e auditoria pública do histórico de lances com cadeia de hash HMAC-SHA256. A transação do lance usa travas pessimistas (`FOR UPDATE`) para evitar condições de corrida, e a API é documentada em Swagger. Mais de 300 testes automatizados. `TypeScript` `Fastify` `React` `PostgreSQL` `Prisma` `Docker` `Vitest`

---

## Stack

| Área            | Tecnologias                                                                         |
|-----------------|-------------------------------------------------------------------------------------|
| **IA e LLMs**   | LangChain, LangGraph, RAG, function calling, sistemas multiagente, embeddings, ChromaDB, Groq, OpenAI |
| **Dados e ML**  | Python, Pandas, NumPy, scikit-learn, SciPy, EDA, web scraping                       |
| **Backend**     | TypeScript, Node.js, Fastify, Prisma, Zod, REST, OpenAPI/Swagger, JWT, SSE, Streamlit |
| **Bancos e BI** | PostgreSQL, MySQL, SQLite, SQL, Power BI, Looker Studio                             |
| **Frontend**    | React, TypeScript, Vite, TanStack Query, HTML, CSS, JavaScript                      |
| **Engenharia**  | Git, Docker, GitHub Actions, Linux, pytest, Vitest, Render, Vercel, Scrum           |
| **Idiomas**     | Português (nativo), inglês (C1), espanhol (avançado)                                |

---

## Estudos

- [rag-langchain-chromadb](https://github.com/GustavoTeixeiraBittencourt/rag-langchain-chromadb): primeiro pipeline de RAG sobre PDFs.
- [EDA-telecom](https://github.com/GustavoTeixeiraBittencourt/EDA-telecom): análise exploratória de dados de churn.
- [ai-engineering-from-scratch](https://github.com/GustavoTeixeiraBittencourt/ai-engineering-from-scratch): fork do currículo de engenharia de IA que estou acompanhando.

## Publicação

**Domestic Violence-Related Head and Neck Injuries: Social Media Web-Scraping**, *Dental Traumatology* ([PubMed](https://pubmed.ncbi.nlm.nih.gov/40799068)). Coautoria, com a coleta, limpeza e análise dos dados em Python.

---

## Contato

[LinkedIn](https://www.linkedin.com/in/gustavo-teixeira-044262266/) · gustavoteixeirabdeoliveira@outlook.com
