# Challenge AluraSore
# 📊 Alura Store – Análise de Desempenho das Lojas

Este projeto tem como objetivo apoiar a tomada de decisão do Senhor João sobre qual de suas lojas deve ser vendida, com base em uma análise de dados sobre vendas, avaliações, categorias de produtos, produtos mais/menos vendidos e frete médio.

## 🎯 Propósito da Análise

A partir de um conjunto de dados extraído de diferentes lojas, foram realizadas análises exploratórias e visuais para responder à seguinte pergunta:

> **Qual loja com menor eficiência e deve ser vendida ?**

Os dados foram processados em um notebook interativo no Google Colab, com o suporte de bibliotecas como *pandas* e *matplotlib*.

## 📁 Estrutura do Projeto

O projeto está centrado no notebook AluraStoreBr.ipynb, onde toda a análise foi conduzida. Os dados utilizados não estão armazenados localmente, mas são carregados diretamente a partir de URLs públicas no repositório do GitHub da Alura. Isso elimina a necessidade de download manual dos arquivos .csv.

As visualizações geradas — como gráficos, mapas e tabelas — podem ser visualizadas diretamente no notebook. Por fim, este arquivo README.md contém toda a documentação e instruções para replicar a análise.

## 📈 Exemplos de Gráficos e Insights Obtidos

- **Gráfico de Barras** com o faturamento total por loja .
- **Gráfico de Pizza** com a representatividade do faturamento total por loja → indicou a **loja 4 com a menor receita**.
- **Gráfico de Linhas** com a evolução do faturamento medio por loja. indicou que a **loja1 com melhor desempenho**
- **Gráfico de Dispersão de Avaliações** → revelou diferenças relevantes na satisfação dos clientes entre as lojas.
- **Gráfico de Barras** destacando as categoria mais vendidas
- **Gráfico de Barras Frete medio por loja** → indicou que a **loja1 com maior Frete**

Esses gráficos serviram como base para a recomendação final apresentada no relatório.

## ▶️ Como Executar o Notebook

1. Acesse o [Google Colab](https://colab.research.google.com/).
2. Faça upload do arquivo `AluraStoreBr.ipynb` (ou abra via GitHub se preferir).
3. Instale as bibliotecas necessárias com o seguinte comando: !pip install pandas matplotlib
4. Execute o notebook célula por célula, seguindo a ordem das análises.
5. Consulte os gráficos gerados e leia a recomendação final ao final do notebook.
