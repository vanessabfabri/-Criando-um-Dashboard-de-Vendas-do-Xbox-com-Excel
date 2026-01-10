# 📊 Dashboard Executivo de Vendas – Xbox Game Pass (Python + Excel)

## 📌 Proposta do Exercício
Este projeto tem como objetivo desenvolver um **Dashboard Executivo de Vendas do Xbox Game Pass**, utilizando **Python no Google Colab** para realizar todo o processo de **ETL (Extração, Transformação e Carga)**, análise de dados e **geração automatizada de um dashboard premium em Excel**.

O exercício simula um cenário corporativo real, no qual uma base de dados bruta é processada automaticamente e transformada em um relatório executivo visual, pronto para tomada de decisão.

---

## 🎯 Objetivos
- Importar uma base de dados em Excel para o Google Colab  
- Automatizar a identificação do arquivo de entrada  
- Realizar limpeza e tratamento de dados (ETL)  
- Calcular indicadores-chave de desempenho (KPIs)  
- Consolidar análises por plano e tipo de assinatura  
- Gerar automaticamente um **arquivo Excel final com dashboard executivo**, layout profissional e gráficos  

---

## 🗂️ Base de Dados
A base de dados é fornecida em formato **Excel (.xlsx)** e contém informações relacionadas às assinaturas do Xbox Game Pass, incluindo, entre outras:

- Data de início da assinatura (`Start Date`)
- Identificador do assinante (`Subscriber ID`)
- Tipo de plano (`Plan`)
- Tipo de ciclo de cobrança (`Subscription Type`)
- Valor total da assinatura (`Total Value`)

> Os dados são utilizados exclusivamente para fins educacionais.

---

## 🔄 Processo ETL (Extração, Transformação e Carga)
O projeto executa automaticamente as seguintes etapas:

### 🔹 Extração
- Localização automática do arquivo Excel na pasta do Google Colab, evitando erros de digitação.
- Leitura da aba **Bases** do arquivo original.

### 🔹 Transformação
- Conversão de campos de data para formato datetime.
- Limpeza de valores monetários, removendo símbolos e tratando valores inválidos.
- Padronização dos dados para cálculo de métricas.

### 🔹 Carga
- Exportação da base tratada para uma aba chamada **Dados_Processados** no arquivo final.
- Criação de uma aba exclusiva de **Dashboard**.

---

## 📈 Indicadores Criados (KPIs)
O dashboard apresenta os seguintes indicadores principais:

- 💰 **Receita Total**
- 👥 **Total de Assinantes Únicos**
- 🎟️ **Ticket Médio por Assinante**

---

## 📊 Análises e Visualizações
O dashboard inclui:

- 📊 **Gráfico de colunas**: Faturamento por categoria de plano  
- 🥧 **Gráfico de pizza**: Participação por ciclo de cobrança  
- 🧾 Tabelas auxiliares ocultas para suporte aos gráficos  
- Layout executivo com:
  - Cartões de KPIs
  - Cores institucionais
  - Tipografia e formatação profissional
  - Data de atualização automática

---

## 🛠️ Tecnologias Utilizadas
- **Python 3**
- **Google Colab**
- **Pandas** – Manipulação e análise de dados  
- **XlsxWriter** – Criação e formatação avançada de arquivos Excel  
- **Excel (.xlsx)** – Entrega final do dashboard  

---

## ▶️ Como Executar o Projeto
1. Acesse o Google Colab  
2. Faça o upload do arquivo Excel original (`.xlsx`) na pasta raiz  
3. Execute o notebook  
4. O sistema irá:
   - Detectar automaticamente o arquivo
   - Processar os dados
   - Gerar o arquivo final `Dashboard_Xbox_Premium_Final.xlsx`  
5. Faça o download do dashboard gerado

---

## 📌 Resultados
Ao final da execução, é gerado automaticamente um **dashboard executivo em Excel**, pronto para apresentação gerencial, com indicadores claros, gráficos consolidados e visual profissional.

---
Projeto desenvolvido para fins educacionais, acadêmicos e de portfólio em Data Analytics e Business Intelligence.
