# ClearBank - Análise Financeira com Python

Este projeto realiza a análise de transações financeiras armazenadas em um arquivo CSV. O sistema valida os dados, identifica registros inválidos, calcula métricas financeiras mensais, detecta transações suspeitas e gera um relatório com os resultados da análise.

## ▶️ Como Executar

1. Abra o notebook no Google Colab ou Jupyter Notebook.
2. Certifique-se de que o arquivo `transacoes.csv` esteja disponível no mesmo diretório do notebook.
3. Execute todas as células em ordem, do início ao fim.
4. Ao final da execução, o relatório será exibido e o arquivo JSON será gerado automaticamente.

## 📊 Saídas Geradas

O notebook gera:

* Um relatório formatado no terminal com:
  * Quantidade de transações válidas e inválidas;
  * Período analisado;
  * Resumo financeiro mensal;
  * Lista de transações suspeitas.
* Um arquivo `relatorio.json` contendo todas as métricas calculadas durante a análise.
