# 🌊 Diagnóstico Socioeconômico de Rio das Ostras (2010–2025)
### Aplicação da metodologia DMAIC para análise de desenvolvimento turístico e econômico municipal

---

## 📌 Sobre o projeto

Este projeto é uma análise comparativa entre **Rio das Ostras**, **Cabo Frio** e **Macaé** (Região dos Lagos, RJ), estruturada segundo a metodologia **DMAIC** (Define, Measure, Analyze, Improve, Control) do Lean Six Sigma.

O objetivo central é responder à pergunta:

> **Como Rio das Ostras pode desenvolver seu setor turístico, aumentar a arrecadação e o PIB per capita, ao mesmo tempo em que mantém os ganhos recentes em segurança pública?**

O projeto combina **8 fontes de dados públicos** (IBGE, ISP-RJ, RAIS/MTE, PNUD, SICONFI, Google Trends), tratamento estatístico (correlação de Pearson, taxas por habitante, normalização entre municípios de tamanhos distintos) e visualização para chegar a um plano de ação fundamentado em evidências.

---

## 🧭 Metodologia: DMAIC

| Fase | O que foi feito |
|---|---|
| **Define** | SIPOC, VOC (Voice of Customer) e fluxograma causal — identificando o morador como cliente principal e "qualidade de vida" como output central |
| **Measure** | Coleta, limpeza e documentação de 8 indicadores ao longo de até 22 anos, com notas metodológicas e limitações explícitas |
| **Analyze** | Respostas às hipóteses do Define com base em dados reais, cálculo de correlações de Pearson e Diagrama de Ishikawa |
| **Improve** | Matriz de priorização de ações (PDSA) derivadas diretamente das causas raiz identificadas |
| **Control** | Indicadores de monitoramento e roadmap de curto, médio e longo prazo |

---

## 📊 Principais achados

### 1. Crescimento populacional explosivo, mas instável

Rio das Ostras cresceu **238%** entre 2006 e 2025 — um crescimento muito acima de Cabo Frio (+47%) e Macaé (+52%). Esse boom está diretamente ligado à expansão da indústria do petróleo na Bacia de Campos, que transformou RO em uma "cidade dormitório" para trabalhadores do setor.

![Crescimento populacional](charts/03_populacao.png)

---

### 2. PIB per capita: o boom e o colapso do pré-sal

Entre 2010 e 2014, o PIB per capita de Rio das Ostras chegou a ser o **maior dos três municípios** (pico de R$ 128 mil em 2012). Com a crise da Petrobras (2014–2016), o PIB per capita despencou **72% em apenas 4 anos** — a queda mais abrupta entre as três cidades. Em 2023, RO está atrás de Cabo Frio e Macaé.

![PIB per capita](charts/01_pib_per_capita.png)

---

### 3. Empregos no turismo: a divergência estrutural

Ao normalizar por mil habitantes, RO e Cabo Frio começaram em patamares parecidos em 2010 (4,9 vs 6,6). Mas enquanto CF **cresceu** sua base de empregos formais em turismo, RO **caiu 55%** entre 2013 e 2021 — e nunca se recuperou. A distância entre as duas cidades só aumentou.

![Empregos no turismo](charts/02_empregos_turismo.png)

---

### 4. Segurança pública: a melhor notícia do projeto

Furtos, roubos e homicídios dolosos em RO caíram de forma consistente, ficando **abaixo da média da Região dos Lagos a partir de 2024** — um resultado positivo real.

![Violência](charts/04_violencia.png)

---

### 5. IDHM: o salto educacional

O IDHM de Rio das Ostras saiu de **0,659 (2000)** para **0,797 (2021)** — a maior evolução entre as três cidades, ultrapassando Cabo Frio e Macaé já em 2010. O destaque é o subíndice de **Educação**, que cresceu **38%** no período — embora ainda seja o componente mais fraco do IDHM da cidade, representando a maior oportunidade de melhoria.

![IDHM](charts/05_idhm.png)

---

## 🔗 Correlações identificadas (Pearson)

| Variáveis | Pearson | Interpretação |
|---|---|---|
| PIB per capita × Empregos no Turismo | **0,80** | Correlação forte — turismo tem peso desproporcional na renda per capita |
| PIB per capita × Empregos Totais | 0,31 | Correlação fraca — emprego genérico não explica o PIB |
| Interesse Digital × Empregos no Turismo | **0,83** | Correlação forte — visibilidade digital acompanha a saúde do setor |
| Furtos × Empregos no Turismo | **0,93** | Correlação muito forte — furto é majoritariamente crime de oportunidade ligado ao turismo |
| Roubos × Empregos no Turismo | 0,13 | Correlação quase nula — roubo segue dinâmica própria, não relacionada ao turismo |

> ⚠️ **Nota metodológica:** os coeficientes foram calculados com amostras pequenas (n = 8 a 12 observações anuais). Dado que várias séries compartilham tendência declinante no período 2013–2021, os valores devem ser interpretados como **indicativos de associação**, não de causalidade.

---

## 🐟 Diagrama de Ishikawa

**Pergunta central:** Por que os empregos formais no setor de turismo de Rio das Ostras caíram 55% entre 2013 e 2021?

![Diagrama de Ishikawa](charts/07_ishikawa.png)

As causas foram agrupadas em 6 categorias adaptadas para o contexto de gestão pública (em vez do tradicional 6M industrial):

- **Gestão e Planejamento** — ausência de estratégia municipal de turismo
- **Conjuntura Econômica** *(fora do controle municipal)* — crise da Petrobras 2014-2016
- **Monitoramento e Dados** — sem KPIs de turismo definidos
- **Capital Humano** — qualificação atrelada ao setor petróleo
- **Infraestrutura Urbana** — pontos turísticos sem manutenção
- **Oferta e Posicionamento** — identidade fraca como destino turístico

---

## 🎯 Plano de Ação (Improve)

As recomendações seguem o ciclo **PDSA (Plan-Do-Study-Act)** e foram priorizadas em uma matriz de Impacto × Esforço:

| Prioridade | Ação | Indicador-alvo |
|---|---|---|
| **P1** | Estratégia de marketing digital municipal | Índice de Interesse Digital (Google Trends) |
| **P1** | Incentivo fiscal (ISS reduzido) para hospedagem/lazer | Empregos no Turismo / 1k hab |
| **P1** | Cadastramento assistido em plataformas (Booking, Airbnb) | Empregos no Turismo / 1k hab |
| **P2** | Revitalização da orla | Arrecadação per capita |
| **P2** | Reforço sazonal de policiamento turístico | Furtos / 100k hab |
| **P3** | Educação técnica em turismo e hospitalidade | IDHM — Educação |

---

## 🗂️ Fontes de dados

| Indicador | Fonte | Período |
|---|---|---|
| População | IBGE — Censos + Estimativas Anuais (DOU) | 1996–2025 |
| PIB per capita | IBGE — Sistema de Contas Regionais (Tabela 5938) | 2010–2023 |
| Violência | ISP-RJ — Base Municipal Mensal | 2014–2025 |
| IDHM | PNUD/Atlas do Desenvolvimento Humano no Brasil | 2000, 2010, 2021 |
| Empregos no Turismo | MTE — RAIS via Base dos Dados | 2010–2021 |
| Arrecadação Municipal | SICONFI — Tesouro Nacional | 2013–2024 |
| Interesse Digital | Google Trends | 2004–2025 |

Todas as fontes, notas metodológicas e limitações estão documentadas na aba **MEASURE & FONTES** da planilha.

---

## 🛠️ Ferramentas utilizadas

- **Excel** — tratamento de dados, tabelas dinâmicas, gráficos, cálculo de correlações
- **Lean Six Sigma (DMAIC)** — estrutura metodológica do projeto
- **Google Trends** — proxy de demanda turística digital
- **APIs e bases públicas** — IBGE (SIDRA), ISP-RJ, Base dos Dados (RAIS), SICONFI, Atlas Brasil

---

## 📁 Estrutura do repositório
