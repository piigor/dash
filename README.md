# Dashboards de Business Intelligence para Operações de Telecomunicações

Portfólio público de dashboards desenvolvidos em Power BI para apoiar decisões de retenção, cancelamento, churn e performance operacional.

> **Nota de confidencialidade:** este repositório não contém os arquivos `.pbix`, bases corporativas, consultas internas ou dados identificáveis. Os PDFs são versões públicas e anonimizadas para demonstrar a estrutura analítica, o storytelling e os tipos de decisão apoiados pelos relatórios.

![Prévia do portfólio](https://github.com/user-attachments/assets/cfcaade0-9ccc-4fbe-b3fb-e12a3bf69e62)

## O que este portfólio demonstra

- Tradução de problemas operacionais em indicadores executivos.
- Organização de métricas de retenção, cancelamento e churn.
- Modelagem analítica com fatos e dimensões.
- Uso de Power Query (M) para preparação e transformação de dados.
- Uso de DAX para medidas, taxas e análises temporais.
- Storytelling com dados para diferentes públicos: operação, gestão e liderança.
- Cuidados de anonimização e publicação responsável de material corporativo.

## Relatórios públicos

| Relatório | Pergunta de negócio | Artefato |
| --- | --- | --- |
| **Funil de Cancelamentos** | Onde estão as perdas e quais solicitações avançam ou são retidas? | [Abrir PDF](./Funil_Cancelamento_Anonimizado.pdf) |
| **Pulso de Retenção** | Como a operação está performando no acompanhamento diário e semanal? | [Abrir PDF](./Pulso_Retencao_Anonimizado.pdf) |
| **Resultados Operacionais** | Como churn real, orçamento e composição da base evoluem no tempo? | [Abrir PDF](./Resultados_Operacionais_Anonimizado.pdf) |

## 1. Funil de Cancelamentos

Dashboard voltado para a operação de retenção, com visão do fluxo de solicitações de cancelamento, retenções realizadas e desconexões.

**Dimensões e indicadores demonstrados:**

- volume de solicitações;
- resultado do atendimento;
- taxa de retenção;
- portabilidade;
- fornecedor/parceiro operacional;
- motivo de saída.

**Decisão apoiada:** localizar etapas, parceiros ou motivos que exigem investigação e ação de retenção.

## 2. Pulso de Retenção

Visão executiva para acompanhar a performance diária e semanal das equipes de retenção.

**Dimensões e indicadores demonstrados:**

- acompanhamento de metas;
- evolução temporal;
- comparação entre tecnologias ou produtos;
- desempenho por parceiro operacional;
- leitura rápida de tendência e desvio.

**Decisão apoiada:** priorizar acompanhamento de performance e identificar desvios antes do fechamento do período.

## 3. Resultados Operacionais

Relatório histórico para análise de produtos de telefonia fixa e banda larga, com foco em evolução da base e churn.

**Dimensões e indicadores demonstrados:**

- churn real versus orçado;
- churn voluntário e involuntário;
- produto/tecnologia;
- ano, trimestre e mês;
- tendências e sazonalidade.

**Decisão apoiada:** comparar desempenho realizado e planejado, identificar mudanças de composição e orientar a investigação de tendências.

## Abordagem técnica

- **Ferramenta:** Power BI Desktop / Power BI Service.
- **Modelagem:** esquema estrela com tabelas fato e dimensões.
- **Preparação:** Power Query (M), com limpeza, padronização e transformação de fontes SQL/CSV.
- **Métricas:** DAX, incluindo medidas de volume, taxas, comparação temporal e acompanhamento de metas.
- **Visualização:** funil, cartões de KPI, indicadores de meta, barras empilhadas e séries temporais.
- **Storytelling:** hierarquia visual orientada à pergunta de negócio, com separação entre visão executiva e detalhamento operacional.

## Limites da publicação

Os arquivos `.pbix` originais permanecem fora do repositório porque podem conter dados, consultas, nomes de tabelas, conexões, medidas, recursos visuais e metadados pertencentes ao ambiente corporativo. O portfólio público preserva o raciocínio e a apresentação sem expor informações protegidas.

Para ver a descrição dos cases, decisões apoiadas e critérios de publicação, consulte [`docs/portfolio-cases.md`](./docs/portfolio-cases.md) e [`docs/publication-safety.md`](./docs/publication-safety.md).

## Sobre o autor

**Paulo Igor Pinheiro de Oliveira** — profissional de operações e negócios em transição para Data & AI, Analytics e automação, com experiência em Power BI, SQL, BigQuery, SAS e soluções orientadas a dados.

- [LinkedIn](https://www.linkedin.com/in/paulo-igor-pinheiro-de-oliveira-93164335)
- [GitHub](https://github.com/piigor)

---

Este repositório é um portfólio profissional. Os documentos públicos não representam uma autorização para reutilizar dados, marcas, regras internas ou materiais corporativos não publicados.
