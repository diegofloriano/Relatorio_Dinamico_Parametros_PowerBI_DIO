# Projeto de Data Analytics - Dashboard Financeiro com Power BI

[!](./imagens/HomePage.jpg)

## 📌 Sobre o Projeto
Este repositório contém um projeto de portfólio focado na criação de um relatório financeiro interativo e estratégico. O desenvolvimento foi guiado pelos requisitos de desafios de projeto, com atenção especial à experiência do usuário (UX), hierarquia visual e storytelling de dados[cite: 1].

## 🎯 Requisitos do Desafio
O dashboard foi construído respeitando as diretrizes técnicas e analíticas do projeto:
* Estruturação em múltiplas páginas com navegação intuitiva[cite: 1].
* Criação de medidas DAX para cálculos financeiros complexos (Total de Vendas, Lucro, Unidades, TOP N)[cite: 1].
* Implementação de visuais de agrupamento, compartimentação (Binning) e análise de outliers[cite: 1].
* Desenvolvimento de uma página de simulação estratégica utilizando **Field Parameters**[cite: 1].

## 📊 Estrutura do Relatório

O projeto está dividido nas seguintes páginas:

### 1. Home Page
Tela de entrada com identidade visual moderna, contendo o título "Report Financeiro" e botão interativo para iniciar a exploração da análise[cite: 1].

### 2. Sales Report (Principal)
Painel gerencial de alto nível com KPIs resumidos. Utiliza indicadores (Bookmarks) para alternar dinamicamente entre visuais de Barras e Pizza, e entre Treemap e Mapa no mesmo espaço de tela[cite: 1].
[!](./imagens/Principal.PNG)

### 3. Detalhes (Report de Lucro Detalhado)
Página voltada para o aprofundamento analítico, apresentando o detalhamento em matriz por trimestre e ano, além de um histograma focado na distribuição de unidades vendidas[cite: 1].
[!](./imagens/Detalhes.PNG)

### 4. Report de Performance (Data Analytics)
Focado em correlações, exibe a relação entre volume de unidades e faturamento mensal, além de destacar os rankings de TOP 5 meses e TOP 3 países[cite: 1].
[!](./imagens/DataAnalytics.PNG)

### 5. Categorias & Cluster
Utiliza inteligência de dados para agrupamentos automáticos (Clustering) e visuais de fluxo (Sankey Chart) para demonstrar a distribuição de vendas entre continentes e anos[cite: 1].
[!](./imagens/CategoriasClusters.PNG)

### 6. Report de Ranking (TOPN & Outliers)
Identificação visual de tendências e exceções através de um gráfico de dispersão dinâmico com **Eixo de Reprodução (Play Axis)** para análise temporal[cite: 1].
[!](./imagens/TOPNOutliers.PNG)

### 7. Painel de Simulação Estratégica (Módulo Final)
Esta página foi desenvolvida seguindo estritamente as regras de **Storytelling**. Através de parâmetros de campos, o usuário pode customizar sua própria visão, escolhendo a dimensão (Produto, País ou Segmento) e a métrica (Vendas, Lucro ou Unidades)[cite: 1].
* **Interatividade**: Filtros em estilo "tijolo" para facilitar a navegação rápida.
* **Narrativa de Dados**: Container dedicado com insights para guiar o tomador de decisão na identificação de distorções entre volume e rentabilidade real[cite: 1].
[!](./imagens/SimulacaoEstrategica.PNG)

## 🛠️ Tecnologias Utilizadas
* **Microsoft Power BI**: Desenvolvimento de dashboards e ETL.
* **DAX (Data Analysis Expressions)**: Criação de medidas e indicadores dinâmicos.
* **Power Query**: Limpeza e transformação dos dados.
* **UX/UI Design**: Princípios de design aplicados ao BI para melhor legibilidade e fluxo de informação.

---
**Desenvolvido por Diego Floriano Costa**
*Profissional focado em transformar dados brutos em inteligência de negócio.*
