# 📊 Análise Multidimensional de Rio das Ostras/RJ: Uma Abordagem Lean Six Sigma Yellow Belt (Framework DMAIC)

[![Lean Six Sigma](https://img.shields.io/badge/Metodologia-Lean%20Six%20Sigma%20%7C%20Yellow%20Belt-yellow)](https://github.com/)
[![Analysis](https://img.shields.io/badge/Analise-Análise%20Exploratória%20de%20Dados-blue)]()
[![Target](https://img.shields.io/badge/Foco-Gestão%20Pública%20%26%20Turismo-green)]()

## 📌 Sobre o Projeto
Este repositório contém um projeto de inteligência territorial e análise exploratória de dados focado no município de **Rio das Ostras/RJ**. O grande diferencial deste estudo é a aplicação prática do framework **DMAIC** (proveniente da metodologia Lean Six Sigma), comumente utilizado na indústria para melhoria de processos, transposto aqui para a **gestão pública estratégica e o desenvolvimento socioeconômico**.

O objetivo principal foi diagnosticar a evolução dos indicadores macroeconômicos, turísticos e de segurança da cidade entre 2010 e 2024, comparando-a com seus principais *benchmarks* regionais (**Cabo Frio** e **Macaé**), para identificar as causas raiz da retração econômica local e propor soluções acionáveis.

---

## 🛠️ O Framework DMAIC Aplicado

O projeto foi estruturado rigorosamente seguindo as fases do ciclo DMAIC, garantindo que nenhuma recomendação fosse baseada em intuição, mas sim em evidências estatísticas.

### 1. 🎯 DEFINE (Definir)
Nesta etapa inicial, delimitou-se o escopo do projeto, os principais clientes (população, setor privado e prefeitura) e as suas dores reais através da ferramenta **VOC (Voice of Customer)** e do mapeamento de processos **SIPOC**.
* **SIPOC Estruturado:** Mapeou-se os fornecedores de infraestrutura, os inputs públicos/privados, o processo de atração e permanência do turista e as saídas esperadas (geração de emprego, renda e IDH).
* **Definição do Problema:** Identificação visual e estatística da queda expressiva na representatividade do turismo na geração de empregos formais da cidade e a necessidade de reverter esse cenário frente a flutuações de receitas de royalties do petróleo.

### 2. 📏 MEASURE (Medir)
Estruturação da coleta de dados agregando bases de dados oficiais de múltiplas fontes confiáveis, cobrindo uma linha do tempo histórica (2010–2024).
* **Matriz de Fontes:**
    * *Demografia e Renda:* IBGE (Censos e Estimativas DOU).
    * *Economia local:* IBGE (Sistema de Contas Regionais - PIB per capita).
    * *Mercado de Trabalho:* Ministério do Trabalho e Emprego / Novo CAGED (Empregos formais totais e no setor de turismo).
    * *Segurança Pública:* ISP-RJ (Instituto de Segurança Pública).
    * *Demanda de Mercado:* Google Trends (Índice de Interesse Digital para hotéis e pousadas).
* *Nota Metodológica:* Os valores monetários foram tratados nominalmente para comparação direta regional dentro do mesmo ano, e anos ausentes de censos foram estimados via interpolação linear padrão.

### 3. 🔍 ANALYZE (Analisar)
Fase dedicada à transformação de dados em insights e teste de hipóteses por meio de correlações lineares estatísticas (Coeficiente de Pearson).
* **Descobertas Chave (Insights do Analyze):**
    * **Turismo em Queda:** O número de empregos formais no turismo por 1k habitantes em Rio das Ostras caiu drasticamente de **4,88** para **2,18** (período 2010-2021). Em contrapartida, o benchmark Cabo Frio conseguiu expandir o indicador de **6,56** para **7,90** no mesmo período.
    * **A Força do Digital:** Identificou-se uma **correlação de Pearson fortíssima (0,83)** entre o *Índice de Interesse Digital (Google Trends)* e o volume de *Empregos Formais no Turismo*. Menos presença digital da cidade correlaciona-se diretamente com o esvaziamento hoteleiro.
    * **Paradoxo do Emprego Geral vs. Renda:** O total de empregos formais apresentou uma correlação fraca com o PIB per capita. Isso provou que a renda municipal é altamente dependente de setores de alto valor agregado (como o Petróleo historicamente e o Turismo potencialmente), e não da quantidade absoluta de vagas subalternas.
    * **Dinâmica da Segurança Pública:** Furtos apresentaram uma correlação linear fortíssima com o emprego no turismo (**Pearson = 0,93**), sugerindo que a criminalidade contra o patrimônio acompanha o fluxo de visitantes. Roubos urbanos, por outro lado, não demonstraram correlação relevante (Pearson = 0,13), exigindo abordagens de segurança pública totalmente distintas no plano de ação.

### 4. 💡 IMPROVE (Melhorar)
A partir das causas raiz identificadas no Ishikawa e validadas estatisticamente no Analyze, foi desenvolvida uma **Matriz de Priorização de Ações baseada no esforço vs. impacto** e desdobrada em um plano de ação robusto focado no ciclo **PDSA** (Plan-Do-Study-Act).

| Categoria | Causa Raiz Endereçada | Ação Proposta | Indicador-Alvo | Prioridade |
| :--- | :--- | :--- | :--- | :---: |
| **Gestão e Planejamento** | Ausência de estratégia municipal | Criar Plano Municipal de Turismo com metas anuais de ocupação hoteleira e arrecadação de ISS. | Empregos no Turismo / 1k hab | **P1 (Alto Impacto / Médio Esforço)** |
| **Gestão e Planejamento** | Falta de incentivo ao setor | Programa de incentivo fiscal (redução de ISS por 24 meses) para novos negócios de hospedagem/lazer. | % Empregos Turismo | **P1 (Alto Impacto / Médio Esforço)** |
| **Monitoramento e Dados** | Falta de inteligência de mercado | Estratégia de marketing digital municipal focada em dados do Google Trends, parcerias com influenciadores e SEO. | Índice de Interesse Digital | **P1 (Alto Impacto / Baixo Esforço)** |
| **Infraestrutura Urbana** | Infraestrutura das orlas defasada | Revitalização física e de acessibilidade das principais praias e sinalização turística moderna. | Empregos no Turismo | **P2 (Alto Impacto / Alto Esforço)** |
| **Capital Humano** | Mão de obra local desqualificada | Criação de programas municipais gratuitos de capacitação profissional em hotelaria e gastronomia. | IDHM Educação | **P2 (Médio Impacto / Médio Esforço)** |

#### 🗺️ Roadmap de Implementação Proposto:
* **Curto Prazo (0-6 meses):** Start nas campanhas de marketing digital regional e início do desenho do Plano Municipal de Turismo.
* **Médio Prazo (6-18 meses):** Aprovação e vigência da lei de incentivo fiscal, reforço sazonal planejado de policiamento na orla (foco em coibir furtos) e implementação de painel público de indicadores (Control).
* **Longo Prazo (18+ meses):** Entrega das obras de revitalização de infraestrutura e consolidação do calendário cultural fixo anual.

### 5. 🎛️ CONTROL (Controlar)
Para garantir que as melhorias implementadas na fase *Improve* sejam sustentáveis a longo prazo, o plano prevê a governança e o monitoramento contínuo:
* **Revisão Anual do Plano:** Análise sistemática dos desvios de metas utilizando painéis ágeis de Business Intelligence (BI).
* **Gatilhos de Ajuste:** Caso o Índice de Interesse Digital ou o número de novos CNPJs hoteleiros fique 15% abaixo da meta trimestral, aciona-se o plano de contingência de marketing focado nos principais polos emissores de turistas (capital e MG).

---

## 📈 Principais Resultados e Conclusões
* O estudo provou matematicamente que a crise socioeconômica de Rio das Ostras não decorre apenas de fatores externos (crise do petróleo), mas sim da **perda de tração e falta de posicionamento estratégico de seu segundo motor econômico: o turismo**.
* A aplicação do **DMAIC** permitiu desmistificar problemas complexos de gestão pública, gerando um portfólio de ações cirúrgicas e priorizadas para maximizar o retorno sobre o investimento municipal.

---

## 📂 Estrutura do Repositório
```bash
├── data/
│   ├── DEFINE.csv                # Dados de escopo, SIPOC e VOC
│   ├── MEASURE_FONTES.csv         # Metadados, links de fontes e notas metodológicas
│   ├── ANALYZE.csv               # Matrizes de correlação de Pearson e testes de hipóteses
│   ├── IMPROVE.csv               # Matriz de priorização de ações e roadmap PDSA
│   └── [Demais planilhas de dados brutos: PIB, IDHM, Violência, Empregos, População]
├── README.md                     # Documentação principal do projeto
