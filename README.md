# 📈 Simulador de Investimentos em Fundos Imobiliários (FIIs)

Este projeto foi desenvolvido como parte do desafio da DIO, com o objetivo de aplicar conceitos de finanças pessoais, Excel e investimentos para criar um simulador realista de aportes mensais com rendimento composto.

## 🎯 Objetivo

Permitir ao usuário simular investimentos mensais em FIIs (Fundos Imobiliários), analisando a evolução do patrimônio ao longo do tempo e o impacto dos dividendos mensais.

---

## 📊 Parâmetros da Simulação

| Parâmetro             | Valor            |
|-----------------------|------------------|
| Valor Inicial (R$)    | R$ 10.000,00     |
| Aporte Mensal         | R$ 500,00        |
| Taxa de Rendimento    | 0,80% ao mês     |
| Período Total         | 60 meses (5 anos)|

---

## 📈 Exemplos de Resultados

| Mês | Aporte Total | Acumulado (R$) | Dividendos (R$) |
|-----|--------------|----------------|------------------|
| 1   | R$ 10.000,00 | R$ 10.000,00    | R$ 80,00         |
| 12  | R$ 15.500,00 | R$ 16.641,42    | R$ 133,13        |
| 24  | R$ 21.500,00 | R$ 24.582,37    | R$ 196,66        |
| 36  | R$ 27.500,00 | R$ 33.320,10    | R$ 266,56        |
| 48  | R$ 33.500,00 | R$ 42.934,57    | R$ 343,48        |
| 60  | R$ 39.500,00 | R$ 53.513,73    | R$ 428,11        |

---

## 📌 Funcionalidades

- Entrada de parâmetros personalizáveis
- Cálculo automático de juros compostos
- Simulação de aportes mensais
- Estimativa de dividendos mensais (baseados na taxa de rendimento)
- Visualização mês a mês dos resultados
- Gráfico opcional de crescimento do patrimônio (na planilha)

---

## 🛠️ Tecnologias Utilizadas

- Microsoft Excel
- Fórmulas financeiras (`VF`, `SOMA`, `SE`, `TAXA`, entre outras)
- Tabela dinâmica
- Gráficos ilustrativos
- Formatação condicional

---

## 📷 Imagem de Prévia

![Visualização da Planilha](images/preview-simulador.png)

---

## 🚀 Como Usar

1. Faça o download da planilha `.xlsx` incluída neste repositório.
2. Abra com o Microsoft Excel (ou Google Sheets com limitações).
3. Altere os valores de entrada no topo da planilha.
4. Observe a atualização automática das colunas de "Acumulado" e "Dividendos".

---

## 📘 Aprendizados

- Como aplicar juros compostos em planilhas
- Automatizar simulações financeiras
- Apresentar dados de forma clara e visual
- Criar modelos realistas de longo prazo com Excel
