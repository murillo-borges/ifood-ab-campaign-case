# Análise de Teste A/B: Otimização de Campanha de Cupons no iFood

## Visão Geral do Projeto

Este repositório contém a análise completa de um caso de teste A/B realizado em uma campanha de cupons do iFood.
O objetivo principal é avaliar a eficácia da campanha não apenas em métricas de engajamento, mas também em sua viabilidade financeira, culminando em uma proposta estratégica para otimizações futuras.

A análise completa, incluindo o diagnóstico, as recomendações e o plano de ação, está consolidada no relatório executivo em PDF.

---

## Objetivos da Análise

* **Avaliar o Impacto da Campanha:** Mensurar o efeito da oferta de cupons em KPIs de produto (frequência, retenção) e financeiros (receita, ROI).
* **Segmentar a Base de Usuários:** Ir além da média geral, criando segmentos de usuários por comportamento (Frequência e Valor) para entender as nuances dos resultados.
* **Analisar a Viabilidade Financeira:** Calcular o custo, o retorno sobre o investimento (ROI) e o resultado líquido da iniciativa.
* **Propor Otimizações Estratégicas:** Desenhar um novo plano de testes A/B com base nos insights gerados, visando maximizar o crescimento rentável.

---

## Estrutura dos Arquivos

* `Ifood_case.ipynb`: Notebook Jupyter contendo todo o código PySpark utilizado para a análise, desde a agregação dos dados até a segmentação e os cálculos financeiros.
* `Resumo Executivo | Data Analysis - iFood.pdf`: Relatório final em PDF com a análise consolidada, insights, gráficos e recomendações estratégicas, destinado a uma audiência de liderança de negócio.

---

## Tecnologias Utilizadas

* **Linguagem:** Python/PySpark
* **Processamento de Dados:** Apache Spark (via PySpark)

---

## Instruções de Execução do Notebook

Para replicar esta análise, siga os passos abaixo.

### Instalação

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/murillo-borges/ifood-ab-campaign-case.git](https://github.com/murillo-borges/ifood-ab-campaign-case.git)
    cd ifood-ab-campaign-case
    ```

2.  **(Recomendado) Crie e ative um ambiente virtual:**
    ```bash
    # Para macOS/Linux
    python3 -m venv venv
    source venv/bin/activate

    # Para Windows
    python -m venv venv
    venv\Scripts\activate
    ```

3.  **Instale as dependências:**
    Este projeto utiliza um arquivo `requirements.txt` para facilitar a instalação de todas as bibliotecas necessárias.
    ```bash
    pip install -r requirements.txt
    ```

### Execução

Abra o notebook `Ifood_case.ipynb` em um ambiente que suporte Jupyter, como:
* Jupyter Notebook ou Jupyter Lab (localmente)
* Google Colab (faça o upload do notebook)
* Databricks (importe o notebook para a plataforma)

Execute as células em ordem para reproduzir a análise completa e gerar o relatório em PDF.

---

## Relatório Executivo

Para uma visão direta e consolidada dos resultados e das recomendações estratégicas, acesse o relatório executivo abaixo.

**[➡️ Ver Relatório: Resumo Executivo | Data Analysis - iFood.pdf](./Resumo%20Executivo%20%7C%20Data%20Analysis%20-%20iFood.pdf)**
