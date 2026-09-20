# dashboard-logistica-otif-excel

# 🚚 Dashboard de Logística e Ocupação de Frota

## 📌 Visão Geral
Este projeto consiste na construção de um **Dashboard de Controle Logístico e Capacidade de Frota** desenvolvido no Microsoft Excel. O objetivo do painel é monitorar indicadores-chave de desempenho (KPIs) operacionais, acompanhar o nível de serviço de entregas e otimizar o uso da capacidade da frota (peso e volume).

![Dashboard Final](img/dashboard_preview.png)

---

## 📊 Indicadores e Métricas (KPIs)
- **Índice OTIF (On-Time In-Full):** Percentual de entregas realizadas no prazo e conforme o pedido (Atualmente em **80%**).
- **Custo Total de Frete:** Monitoramento financeiro acumulado das operações de transporte.
- **Distância Total Percorrida:** Quilometragem total acumulada pelas rotas.
- **Total de Entregas:** Volume total de solicitações atendidas.
- **Capacidade e Ocupação da Frota:** Análise comparativa percentual de ocupação por **Peso** vs. **Volume** por veículo (`Truck-01`, `VUC-01`, `VUC-02`).

---

## 🛠️ Tecnologias e Recursos Utilizados
- **Microsoft Excel**:
  - Tratamento e organização de dados em tabelas dinâmicas/relacionais.
  - Fórmulas de agregação e cálculo de KPIs (`SOMA`, `DIVISÃO`, referências dinâmicas).
  - Formatação condicional e personalização visual (cards com cantos arredondados, remoção de linhas de grade).
  - Gráficos de Rosca e Barras Agrupadas customizados.

---

## 📂 Estrutura da Planilha
A pasta de trabalho está dividida em três abas principais:
1. **`Frota_e_Capacidade`**: Registro detalhado dos veículos, cargas atribuídas, volume e percentuais de ocupação.
2. **`Dashboard_Resumo`**: Tabela de apoio e consolidação matemática das métricas dos cards e gráficos.
3. **`Dashboard`**: Painel visual executivo final para tomada de decisão.

---

## 🚀 Como Visualizar o Projeto
1. Faça o download do arquivo `Dashboard_Logistica.xlsx` presente neste repositório.
2. Abra no Microsoft Excel (versão 2016 ou superior).
