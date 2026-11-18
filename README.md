# Marcos Barbosa

**Engenharia de Dados · evolução para Arquitetura de Dados**

Meu foco é construir pipelines de dados confiáveis, com atenção à qualidade, à operação e às decisões de arquitetura. Este portfólio reúne minha formação e entregas práticas em Engenharia de Dados, com Ciência de Dados e DevOps como conhecimentos complementares.

## Projeto principal — airflow-dbt-postgres-elt

[**Pet Event Analytics Platform — conhecer o projeto**](https://github.com/Barbo541/airflow-dbt-postgres-elt)

Pipeline ELT que integra registros sintéticos de saúde e atividade de pets com atributos de seus responsáveis, produzindo uma tabela de eventos para consultas analíticas.

**Fluxo:** CSVs sintéticos → ingestão Python orquestrada pelo Airflow → PostgreSQL → transformações e testes dbt → tabela analítica com 1.878 eventos na base de referência.

**Stack:** Python, SQL, Apache Airflow, dbt, PostgreSQL, Docker Compose e GitHub Actions.

O trabalho de engenharia demonstra:

- Ingestão atômica das tabelas brutas, com rollback em caso de falha.
- Contratos de entrada e testes de qualidade, relacionamentos e reconciliação dos dados.
- Execução repetível e validação ponta a ponta em ambiente descartável.
- Integração contínua com lint, testes Python e execução real do pipeline.
- Logs de ingestão, documentação operacional e decisões de performance apoiadas em medições.

**V1 finalizada e congelada.** A validação documentada registra 18 testes Python e 42 resultados dbt aprovados: 4 modelos, 36 testes de dados e 2 testes unitários, além da repetibilidade e da recuperação após falha forçada.

[CI aprovado do commit 06a8853](https://github.com/Barbo541/airflow-dbt-postgres-elt/actions/runs/43599810089) · [Arquitetura](https://github.com/Barbo541/airflow-dbt-postgres-elt/blob/main/docs/architecture.md) · [Operação](https://github.com/Barbo541/airflow-dbt-postgres-elt/blob/main/docs/runbook.md) · [Performance](https://github.com/Barbo541/airflow-dbt-postgres-elt/blob/main/docs/performance.md)

O escopo é local, em lote e em um único nó, com dados sintéticos. O projeto foi derivado de uma implementação de Vincent Crescente sob licença MIT; o trabalho posterior concentra-se em robustez, testes, segurança e operação. A origem e as contribuições estão descritas no [NOTICE](https://github.com/Barbo541/airflow-dbt-postgres-elt/blob/main/NOTICE.md).

## Competências demonstradas no portfólio

| Área | Aplicação prática |
| --- | --- |
| Python e SQL | Ingestão, transformação, validação e consultas |
| Airflow e dbt | Orquestração, dependências, modelos e testes |
| PostgreSQL | Transações, integridade e organização dos dados |
| Docker Compose | Ambiente local reproduzível |
| Git e GitHub Actions | Versionamento, pull requests e integração contínua |
| Qualidade e operação | Contratos, rollback, logs, troubleshooting e documentação |

## Formação concluída

- Pós-graduação em Engenharia de Dados.
- Pós-graduação em DevOps.
- Formação em Arquitetura de Dados.
- Formação profissionalizante em Ciência de Dados — EBAC.

## Evolução profissional

Meu próximo foco é ampliar a prática em cloud, Spark e modelagem dimensional, além de aprofundar observabilidade e otimização de pipelines. São objetivos de desenvolvimento alinhados à evolução para Arquitetura de Dados.

## Idiomas e contato

Português nativo · Inglês básico

[LinkedIn](https://www.linkedin.com/in/barbosa-data)
