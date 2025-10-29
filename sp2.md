# 📌 MVP - [Sprint 2 GesTec VI]

## 🎯 Objetivo do MVP
Dar continuidade à análise das exportações brasileiras (2020–2025), aprimorando o tratamento dos dados e ampliando a visualização analítica.
Nesta sprint, o foco foi realizar a importação, leitura e tratamento avançado dos arquivos CSV no Google Colab utilizando a biblioteca Pandas, e desenvolver painéis interativos no Power BI para identificar os principais produtos, estados e países envolvidos nas exportações brasileiras.

---

## 📝 Descrição da Solução
Etapa 1 – Google Colab (Python + Pandas)

Realizada a leitura de todos os arquivos de exportação dos anos de 2020 a 2025, além das tabelas auxiliares de País, URF, NCM e Via.

Padronização dos dados utilizando sep=';', encoding='UTF-8' e latin1 quando necessário.

Inspeção dos DataFrames com .info() para verificar a estrutura e integridade das informações (11 colunas principais e mais de 1,6 milhão de registros).

Estrutura das colunas analisadas: ano, mês, NCM, país, unidade, valor FOB e peso líquido.

Esses dados tratados foram exportados para o Power BI, servindo de base para os dashboards analíticos.

Etapa 2 – Power BI (Visualização e Análise)

Criado dashboard interativo com diferentes visões sobre o comércio exterior brasileiro.

Painel FOB/KG: energia elétrica, ouro, pedras preciosas e produtos químicos lideram em volume exportado; os principais destinos são Argentina, EUA e Hong Kong.

Identificação dos principais estados exportadores: Paraná e São Paulo se destacam em peso, e São Paulo, Rio de Janeiro e Minas Gerais em valor financeiro.

Visualização do modal de transporte: predominância dos modais aéreo e marítimo, além da rede de transmissão.

Painel KPI – Fluxo de Cargas: picos de exportação observados em maio e julho, com destaque para o transporte rodoviário.

As análises transformaram grandes volumes de dados em insights estratégicos para a tomada de decisão.

---

## 👥 Personas / Usuários-Alvo
- **Persona 1:**  Secretário de Comércio Exterior
Necessidade: Obter informações organizadas e confiáveis para tomar decisões estratégicas, responder à imprensa, negociar com outros países e orientar políticas públicas.

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1 | .Como Secretário de Comércio Exterior, quero mapear as 10 mercadorias com maior valor agregado para identificar oportunidades estratégicas no mercado internacional.         | Alta       | 3 pontos   |
| US2 |   Como Secretário de Comércio Exterior, quero identificar os 5 estados brasileiros que mais exportam mercadorias com maior valor agregado para compreender a distribuição geográfica das exportações.     |   média     | 2 pontos   |
| US3 |   Como Secretário de Comércio Exterior, quero conhecer os 10 principais países de destino das exportações brasileiras com maior valor agregado para entender dependências e oportunidades internacionais..     |   Alta      | 5 pontos   |
| US4 |  Como Secretário de Comércio Exterior, quero mapear as principais mercadorias exportadas por cada estado brasileiro para analisar a relevância comercial..     |   Alta      | 5 pontos   |


---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     |     Importação, limpeza e tratamento dos dados de exportação (Python e Pandas no Google Colab). Criação das primeiras tabelas com informações de países, estados, mercadorias e valores FOB.                 | Concluido|
| 02     |    Desenvolvimento dos dashboards interativos no Power BI com indicadores FOB, peso (KG), principais produtos, estados e países exportadores. Criação dos KPIs de fluxo de cargas e análise temporal das exportações.                     | Concluido |

---

## 📊 Critérios de Aceitação
O MVP deve permitir que o usuário:

-Identifique oportunidades estratégicas no mercado internacional;

-Compreenda a distribuição geográfica das exportações brasileiras;

-Entenda dependências e oportunidades internacionais;

-Analise a relevância comercial por estado, país e tipo de mercadoria;

-Visualize picos e tendências mensais no fluxo de exportações.
---

## 📈 Métricas de Validação
- Número de usuários que testaram o MVP  
- Feedback qualitativo (positivo/negativo)  
- Indicadores de negócio (exemplo: % de adesão, redução de custo, etc.)  

---

## 🚀 Próximos Passos
- Melhorias planejadas após feedback  
- Ajustes de usabilidade  
- Expansão de funcionalidades para próximo incremento  
