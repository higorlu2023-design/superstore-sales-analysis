# Hipóteses - Análise Exploratória de Dados (EDA)

## Hipótese 1 - Coluna Sales

### Observações
- Média superior ao terceiro quartil (75%).
- Desvio padrão elevado.
- Valor máximo muito distante da maioria dos registros.

### Hipótese
Existem valores extremos (outliers) influenciando significativamente a média das vendas.

### Próximos passos
- Construir um boxplot.
- Calcular o IQR.
- Verificar se os maiores valores são erros ou vendas legítimas.

---

## Hipótese 2 - Coluna Profit

### Observações
- Existem registros com lucro negativo.

### Hipótese
Descontos elevados podem estar relacionados aos prejuízos.
    
### Próximos passos
- Analisar a relação entre `discount` e `profit`.
- Identificar os produtos com maior prejuízo.

# Perguntas de Negócio | Business Questions

## 🇧🇷 Português

1. **Quais categorias e subcategorias geram maior volume de vendas e lucro?**

2. **Quais produtos apresentam os maiores lucros e prejuízos?**

3. **Qual é a relação entre o nível de desconto e o lucro?**

4. **Quais regiões e estados apresentam melhor desempenho em vendas e lucro?**

5. **Como as vendas e o lucro evoluem ao longo do tempo?**

---

## 🇺🇸 English

1. **Which categories and sub-categories generate the highest sales and profit?**

2. **Which products generate the highest profits and losses?**

3. **What is the relationship between discount levels and profit?**

4. **Which regions and states have the best sales and profit performance?**

5. **How do sales and profit evolve over time?**
