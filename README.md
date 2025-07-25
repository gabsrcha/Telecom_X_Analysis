# TelecomX Analysis

Bem-vindo ao projeto **TelecomX Analysis**! Este repositório apresenta uma análise detalhada de dados de clientes de uma empresa de telecomunicações, explorando padrões de uso, características dos clientes, serviços contratados e o fenômeno do churn (cancelamento).

## 🚀 Sobre o Projeto

O objetivo principal deste projeto é entender melhor os fatores que influenciam o cancelamento de clientes (churn) e gerar insights para reduzir a evasão, utilizando Python, pandas, matplotlib e seaborn. Os dados foram organizados e tratados a partir de um arquivo JSON, normalizando diferentes aspectos dos clientes, como informações pessoais, serviços de telefone, internet e detalhes de conta.

## 📂 Organização dos Dados

Os dados originais estão em um arquivo JSON estruturado, contendo as seguintes colunas principais:

- **customerID:** Identificador único do cliente
- **Churn:** Informa se o cliente cancelou ou não
- **customer:** Dados pessoais (gênero, dependentes, etc)
- **phone:** Serviços telefônicos contratados
- **internet:** Serviços de internet contratados
- **account:** Informações de contrato e faturamento

Após a extração, as colunas aninhadas são normalizadas em DataFrames separados para facilitar a análise.

## 📊 Principais Análises

- Distribuição de clientes por gênero, faixa etária e tempo de contrato
- Relação entre churn e tipos de contrato, serviços utilizados e perfil do cliente
- Visualizações personalizadas usando matplotlib e seaborn
- Estratégias para redução do churn

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- pandas
- matplotlib
- seaborn
- Google Colab

## 📒 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/gabsrcha/Telecom_X_Analysis.git
   ```

2. Abra o notebook [`TelecomX_BR.ipynb`](TelecomX_BR.ipynb) no Google Colab (ou localmente).

3. Faça o upload do arquivo de dados (`TelecomX_Data.json`) no seu Google Drive, conforme indicado no notebook.

4. Siga as células passo a passo para carregar, tratar e analisar os dados.

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se livre para abrir issues, sugerir melhorias ou enviar pull requests.

## 📧 Contato

Dúvidas ou sugestões? Entre em contato pelo [GitHub](https://github.com/gabsrcha) ou abra uma issue neste repositório.

---

Feito com 💙 por [gabsrcha](https://github.com/gabsrcha)
