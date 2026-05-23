# Projeto 10PXP — Pipeline de BI para Rede de Postos de Combustíveis

Projeto desenvolvido do início ao fim por mim, de forma independente, para uma rede de 10 postos de combustíveis.
Abrange desde a extração dos dados no sistema interno até a visualização executiva no Power BI.

---

## Como o projeto funciona

---

## Stack utilizada

- **Banco de dados:** PostgreSQL 18
- **ETL / Carga:** Python (pandas, SQLAlchemy)
- **Tratamento:** Microsoft Excel
- **Visualização:** Power BI

---

## Dashboard — Páginas

### Geral
Visão executiva da operação. KPIs de receita total, litros vendidos e variação semanal e mensal. Inclui evolução mensal de receita, mix de combustíveis por receita, receita por posto e receita por base regional.

### Preço Médio
Análise de preço médio por litro com toggle entre visão mensal e semanal. Compara o preço praticado para clientes identificados versus clientes sem cadastro, além de calcular o spread(diferença) entre os dois grupos.

### Análise Sem Cliente
Página dedicada às vendas sem identificação de cliente. KPIs de percentual de transações, volume e receita sem cliente, com comparativo de ticket médio. Detalha o comportamento por combustível, por posto, por mês e por dia da semana — além da evolução semanal do volume de diesel vendido sem cliente.

### Análise de Cliente
Visão individual por cliente com busca interativa. Exibe consumo semanal por cliente (multi-linha), preço médio praticado por semana, mix de combustíveis por litro e participação de volume por posto.

### Resultados
Ranking dos Top 15 clientes por receita, litros vendidos por base regional e variação percentual de volume por posto entre o mês passado e o mês retrasado.

### Análise de Risco
Monitoramento de churn e risco operacional. Gráfico de dispersão posiciona cada cliente pelo volume da quinzena anterior versus a variação percentual de consumo — identificando visualmente clientes em queda. Complementado por consumo semanal multi-cliente e preço médio semanal.

---

## Sobre os dados

Os dados neste repositório são **sintéticos** — os valores numéricos foram anonimizados com fatores de escala aleatórios por posto e os nomes de clientes e postos foram substituídos por aliases genéricos. O dataset original contém informações confidenciais da empresa e não é de acesso público.

---

## Autor

Lucas Zanella — Analista de BI & estudante de Ciência de Dados
[LinkedIn](www.linkedin.com/in/lucas-zanella-509a89398) · [GitHub](https://github.com/lucaszanella00)
