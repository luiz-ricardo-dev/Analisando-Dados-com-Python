# Python Insights - Análise de Cancelamento de Clientes (Churn)

Este projeto consiste numa análise de dados de uma base com mais de 800 mil clientes. O objetivo principal é identificar os motivos de cancelamento (churn) e propor soluções estratégicas para melhorar a retenção de clientes.

## 📋 Cenário do Projeto
A empresa identificou um alto índice de inatividade na sua base de clientes. Como analista de dados, o objetivo foi processar essa base, identificar os padrões que levam ao cancelamento e calcular o impacto potencial de ações corretivas.

## 🛠️ Tecnologias Utilizadas
* **Python**: Linguagem base.
* **Pandas**: Manipulação e limpeza de dados.
* **Plotly**: Visualização de dados e criação de gráficos interativos.
* **Jupyter Notebook**: Ambiente de desenvolvimento.

## 📊 Etapas da Análise

1.  **Tratamento de Dados**: Limpeza de valores nulos e remoção de colunas irrelevantes (como IDs).
2.  **Análise Inicial**: Verificação da taxa de cancelamento atual, que se encontrava em **56%**.
3.  **Identificação de Causas (Insights)**:
    * **Contratos Mensais**: Identificou-se que todos os clientes com contrato mensal cancelam.
    * **Call Center**: Clientes que ligam mais de 4 vezes para o suporte têm uma tendência drástica de cancelamento.
    * **Atrasos no Pagamento**: Clientes com mais de 20 dias de atraso representam uma perda quase certa.

## 🚀 Soluções Propostas
* Incentivar a migração de contratos mensais para trimestrais ou anuais.
* Criar um processo de urgência para resolver problemas de clientes que ligam mais de 3 vezes para o suporte.
* Melhorar os processos de cobrança para evitar atrasos superiores a 20 dias.

## 📈 Resultados Alcançados
Após simular a correção dos problemas identificados (removendo os perfis críticos da análise), a taxa de cancelamento caiu de **56% para 18%**, o que representa uma retenção de milhares de clientes e um impacto financeiro positivo significativo.

---
**Autor:** Luiz R Campos