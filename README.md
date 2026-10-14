# Victor Pena

**Engenharia de Dados · Ciência de Dados · Machine Learning**

Graduando em **Ciência de Dados na Universidade Federal do Ceará (UFC)**. Trabalho com coleta, transformação e análise de dados, automação de pipelines, dados geoespaciais e aplicações de machine learning. Meu foco é construir soluções de ponta a ponta, com **qualidade, testes, reprodutibilidade e decisões técnicas bem documentadas**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil_profissional-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/victor-cpena/)
[![Projetos](https://img.shields.io/badge/GitHub-Repositórios-24292F?style=flat-square&logo=github&logoColor=white)](https://github.com/VictorCPena?tab=repositories)

## Projetos em destaque

### 01. [Data Hub de Vendas — Engenharia e qualidade de dados](https://github.com/VictorCPena/datahub-vendas-confiavel)

[![CI Data Hub](https://github.com/VictorCPena/datahub-vendas-confiavel/actions/workflows/ci.yml/badge.svg)](https://github.com/VictorCPena/datahub-vendas-confiavel/actions/workflows/ci.yml)

Pipeline incremental com **Python, SQL, DuckDB e Parquet**, incluindo ledger de eventos, deduplicação, histórico SCD Type 2, reconciliação, auditoria e recuperação após falhas.

- **Evidência:** 4.631 eventos aceitos, 10 duplicatas identificadas e **zero divergências** entre DuckDB e Parquet no cenário validado.
- **Engenharia:** replay idempotente, testes de concorrência com escritor único, falhas antes/depois do commit, backup e restauração auditada.
- **Qualidade:** 26 testes locais aprovados, além de workflow de CI aprovado.

### 02. [Ceará Road Safety — Plataforma de Engenharia de Dados e Segurança Viária](https://github.com/VictorCPena/ceara-road-safety-data-platform)

Plataforma de dados para estudar a **segurança viária no Ceará**, combinando informações públicas da **PRF, IBGE e Open-Meteo** em pipelines de ingestão, transformação, modelagem analítica e visualização geográfica.

- **Arquitetura:** camadas Bronze, Silver e Gold em **Parquet**, consultas no **DuckDB**, transformações e testes com **dbt**, orquestração com **Apache Airflow** e ambiente reproduzível com **Docker Compose e PostgreSQL**.
- **Evidência:** processamento documentado de **194.443 ocorrências da PRF**, incluindo **3.559 registros no recorte do Ceará**, e integração de dados de **184 municípios do IBGE**.
- **Aplicação:** *Observatório Viário CE* em **Streamlit**, com mapas, indicadores, recortes territoriais e exploração de trechos críticos. O projeto também possui testes e integração contínua.
- **Extensão acadêmica:** [API pública de indicadores viários (repositório em equipe)](https://github.com/ayurireiscentraldedados/interface-grafica), construída separadamente com **FastAPI** e documentação OpenAPI.

### 03. [Previsão de Demanda — Machine Learning e MLOps](https://github.com/VictorCPena/previsao-demanda-mlops)

[![CI MLOps](https://github.com/VictorCPena/previsao-demanda-mlops/actions/workflows/ci.yml/badge.svg)](https://github.com/VictorCPena/previsao-demanda-mlops/actions/workflows/ci.yml)

Sistema de previsão diária com **scikit-learn, MLflow e FastAPI**, validação temporal, registro e promoção de modelos, monitoramento e API de inferência.

- **Evidência:** MAE de **5,95** e WAPE de **11,34%** no holdout sintético; redução de **55,61%** no MAE em relação ao baseline sazonal.
- **Avaliação:** backtesting recursivo de D+1 a D+14, cenários de promoção, intervalos calibrados por horizonte, cold start e testes locais de carga.
- **Qualidade:** 29 testes locais aprovados, além de workflow de CI aprovado.

### 04. [Experimentação A/B — Estatística e decisão](https://github.com/VictorCPena/experimentacao-ab-marketing)

[![CI A/B](https://github.com/VictorCPena/experimentacao-ab-marketing/actions/workflows/ci.yml/badge.svg)](https://github.com/VictorCPena/experimentacao-ab-marketing/actions/workflows/ci.yml)

Estudo de experimentação com **Python, pandas e SciPy**, testes de hipóteses, intervalos de confiança, análise de guardrails e simulações Monte Carlo.

- **Evidência:** aumento relativo simulado de **28,55% na conversão**, mas recomendação **REVISAR**, pois a segurança do guardrail de descadastro não foi demonstrada.
- **Avaliação:** randomização por clusters, correlação entre métricas e comparação de testes sequenciais com e sem controle de falsos positivos.
- **Qualidade:** 23 testes locais aprovados, além de workflow de CI aprovado.

> **Sobre os dados e resultados:** Data Hub, Previsão de Demanda e Experimentação A/B usam **dados sintéticos**, com métricas de execuções locais de outubro de 2026. O **Ceará Road Safety trabalha com bases públicas**, cujos recortes e tratamentos estão documentados no projeto. Nenhuma métrica representa resultado de cliente ou garantia de desempenho em produção.

## Tecnologias

| Área | Ferramentas |
| --- | --- |
| **Linguagens e análise** | Python, SQL, R, pandas, NumPy |
| **Engenharia de dados** | PostgreSQL, DuckDB, dbt, Apache Airflow, PySpark, Apache Parquet, AWS Lambda, Amazon Athena |
| **Machine Learning e NLP** | scikit-learn, MLflow, PyTorch, Transformers |
| **APIs e automação** | FastAPI, Streamlit, Selenium, Playwright |
| **Qualidade e entrega** | pytest, Git, GitHub Actions, Docker |

## Como trabalho

Procuro conectar o problema de negócio à implementação: **definir contratos → construir pipelines/modelos → validar com testes → medir resultados → documentar decisões e limites**.

Meu interesse profissional está em **Engenharia de Dados, Ciência de Dados e Machine Learning aplicado**.

**Contato:** [LinkedIn](https://www.linkedin.com/in/victor-cpena/) · [Repositórios públicos](https://github.com/VictorCPena?tab=repositories)
