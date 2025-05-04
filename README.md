# 📊 Análise de Vendas de Lojas - Challenge Alura Data Science

Este projeto faz parte de um desafio proposto pela Alura, com o objetivo de analisar o desempenho de quatro lojas fictícias utilizando técnicas de análise de dados com Python 

## 🧠 Objetivo

Avaliar o desempenho de quatro lojas com base em métricas como:
- Faturamento total
- Volume de vendas por categoria
- Satisfação dos clientes
- Produtos mais e menos vendidos
- Custo médio de frete
- Distribuição geográfica das vendas

Com base nessas análises, foi possível recomendar qual loja possui o menor desempenho e, portanto, é candidata à venda.

## 🛠️ Tecnologias Utilizadas

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook 

## 📂 Estrutura dos Dados

Cada loja possui um conjunto de dados com as seguintes colunas:
- `Produto`
- `Categoria do Produto`
- `Preço`
- `Frete`
- `Data da Compra`
- `Vendedor`
- `Local da compra`
- `Avaliação da compra`
- `Tipo de pagamento`
- `Quantidade de parcelas`
- `lat` / `lon` (localização geográfica)

## 📈 Principais Análises

### 1. Faturamento Total por Loja
A Loja 1 foi a mais lucrativa, enquanto a Loja 4 teve o menor faturamento.

### 2. Vendas por Categoria
Todas as lojas apresentaram uma boa variedade de vendas, com destaque para a Loja 4, que demonstrou uma distribuição mais equilibrada.

### 3. Avaliação Média dos Clientes
A Loja 3 teve a melhor avaliação média (4.05), e a Loja 1, a pior (3.97).

### 4. Produtos Mais e Menos Vendidos
Cada loja apresentou seus produtos mais populares e os com menor saída, permitindo uma análise de estoque e preferência dos clientes.

### 5. Custo Médio de Frete
A Loja 4 teve o menor custo logístico, enquanto a Loja 1 apresentou o frete mais alto.

### 6. Distribuição Geográfica
Um gráfico de dispersão mostra a concentração de vendas em diferentes regiões do Brasil.

## ✅ Conclusão

Apesar de liderar em faturamento, a **Loja 1** se destacou negativamente em avaliações e logística, tornando-se a **candidata ideal para ser vendida**. Já a **Loja 4** mostrou maior estabilidade e melhor desempenho geral, sendo mais indicada para continuidade.

## 📌 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
