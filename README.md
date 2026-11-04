# 🚚 Projeto Logística - Power BI
# 📊 Visão Geral

Este projeto apresenta um dashboard interativo de logística, desenvolvido no Microsoft Power BI, com o objetivo de acompanhar e analisar as operações de transporte rodoviário.

Segue link: 

https://gist.github.com/user-attachments/assets/f534a707-8b95-4872-b87c-63a2c20e3a12"

Com ele, é possível visualizar informações importantes sobre a operação, como:

🚛 Desempenho e utilização da frota;

👨‍✈️ Performance dos motoristas;

🛣️ Rotas e entregas realizadas;

💰 Receitas, custos e rentabilidade;

⛽ Consumo e gastos com combustível;

🔧 Manutenções dos veículos;

⚠️ Segurança e ocorrências operacionais.

A proposta é transformar dados em informações visuais que facilitem o acompanhamento dos resultados e a tomada de decisões.

## 🗂️ Estrutura do Projeto

O projeto está organizado da seguinte forma:

```text
logistica/
├── 📊 logistica.pbix            # Dashboard do Power BI
├── 📁 logistica.SemanticModel/  # Modelo de dados
├── 📁 logistica.Report/         # Estrutura do relatório
├── 📁 dataset/                  # Arquivos com os dados (CSV)
└── 📄 .gitignore
```

## 📁 Fontes de Dados

Os dados utilizados no projeto estão armazenados na pasta dataset/, em arquivos CSV.

Arquivo	Descrição
🚗 drivers.csv	Cadastro e histórico dos motoristas

🚛 trucks.csv	Cadastro dos caminhões da frota

🚚 trailers.csv	Cadastro de reboques e carretas

🏢 customers.csv	Informações sobre clientes e contratos

🏭 facilities.csv	Terminais, armazéns e locais de operação

🛣️ routes.csv	Rotas, distâncias, origens e destinos

📦 loads.csv	Informações sobre as cargas transportadas

🚦 trips.csv	Viagens realizadas e seus resultados

📍 delivery_events.csv	Eventos de coleta e entrega

⛽ fuel_purchases.csv	Registros de abastecimento e gastos com combustível

🔧 maintenance_records.csv	Histórico e custos de manutenção

⚠️ safety_incidents.csv	Acidentes, infrações e ocorrências

📈 driver_monthly_metrics.csv	Indicadores mensais dos motoristas

🚛 truck_utilization_metrics.csv	Indicadores mensais de utilização dos caminhões

📖 DATABASE_SCHEMA.txt	Documentação das tabelas e relacionamentos

💡 Para conhecer melhor a organização dos dados e como as tabelas se relacionam, consulte o arquivo DATABASE_SCHEMA.txt.

## 📑 Páginas do Dashboard

O relatório foi dividido em cinco páginas, cada uma com um objetivo específico:

O que você encontra

📊 Overview (Visão Geral)	Resumo dos principais indicadores e resultados da operação

👨‍✈️ Driver Performance (Desempenho dos Motoristas)	Comparação e acompanhamento do desempenho dos motoristas

🚛 Fleet & Utilization (Frota e Utilização)	Informações sobre a frota, utilização e eficiência dos veículos

💰 Routes & Profitability (Rotas e Rentabilidade)	Análise de receitas, custos e resultados financeiros por rota

📦 Operations (Operações)	Acompanhamento das viagens, coletas e entregas

## 🎯 Principais Indicadores (KPIs)

O dashboard apresenta indicadores que ajudam a entender o desempenho da operação logística.

💵 Receita e Rentabilidade: receita total e lucro por viagem ou rota.

⏱️ Pontualidade das Entregas: percentual de entregas realizadas dentro do prazo.

⛽ Consumo de Combustível: consumo médio e gastos com abastecimento.

🚛 Utilização da Frota: quilometragem percorrida e nível de utilização dos caminhões.

🔧 Manutenção: custos com reparos e tempo em que os veículos ficam parados.

🛡️ Segurança: quantidade de incidentes, acidentes e infrações.

👨‍✈️ Desempenho dos Motoristas: eficiência, produtividade e pontualidade individual.

## 🛠️ Tecnologias Utilizadas

As principais ferramentas e tecnologias utilizadas no desenvolvimento foram:

📊 Microsoft Power BI: criação dos dashboards e visualização dos dados.

🔄 Power Query: preparação, limpeza e transformação dos dados.

🧮 DAX: criação de cálculos e indicadores personalizados.

🗃️ TMDL: organização e definição do modelo de dados.

📄 CSV: arquivos utilizados como fonte de dados.

## ▶️ Como Abrir o Projeto

📥 Baixe ou clone este repositório.

💻 Abra o Microsoft Power BI Desktop.

📂 Localize e abra o arquivo logistica.pbix.

🔄 Caso necessário, atualize as fontes de dados para carregar os arquivos CSV.

## 💻 Requisitos

Para visualizar e utilizar o projeto, é necessário:

Microsoft Power BI Desktop instalado.

📁 Acesso aos arquivos CSV disponíveis na pasta dataset/.

🔗 Manter a estrutura de pastas do projeto para facilitar a localização das fontes de dados.

## 🧩 Modelo de Dados

O projeto possui um modelo de dados organizado para facilitar o cruzamento das informações.

As tabelas estão divididas entre:

📌 Tabelas de cadastro: motoristas, caminhões, carretas, clientes, rotas e instalações.

📊 Tabelas de movimentação: cargas, viagens, entregas, abastecimentos, manutenções e ocorrências.

📅 Tabelas de indicadores: métricas mensais dos motoristas, utilização dos caminhões e calendário.

Essa organização permite analisar diferentes aspectos da operação logística de maneira integrada.

## 📜 Licença e Fonte dos Dados

Este projeto foi desenvolvido para fins de estudo, análise de dados e demonstração de conhecimentos em Business Intelligence (BI).

Os dados utilizados são fictícios e foram obtidos no site do Kaggle:

[🔗 Logistics Operations Database - Kaggle](https://www.kaggle.com/datasets/yogape/logistics-operations-database?select=delivery_events.csv)

⭐ Se este projeto foi útil ou interessante, fique à vontade para explorar o repositório!
