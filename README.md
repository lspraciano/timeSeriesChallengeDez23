# Sobre o Desafio

Este desafio tem como contexto treinamento e validação de modelos
de machine learning para predição em séries temporais. Como eu não
tenho vivência com este tipo de problema resolvi compartilhar este
desafio e a evolução da minha resolução com vocês.

## 📦 Status do Desafio

- Em Resolução

## 📚 Tarefas

### 🔖 Análise exploratória

AE-1 - Carregue os dados em um DataFrame pandas.

AE-2 - Analise e responda qual foi o crescimento das vendas
(VendasSupermercados) dos últimos 12 meses (Set/2022 - Agosto
2023 vs Set/2021 - Agosto 2022)?

AE-3 - Analise e responda se existe sazonalidade e tendência
nesses dados? Como você descreveria e mostraria graficamente?

AE-4 - Analise e responda se existe relação entre o CDI e
as vendas? Como você a descreveria e mostraria graficamente?

### 🔖 Modelagem

M-1 - Usando uma biblioteca de sua escolha, treine dois modelos
de machine learning, um ARIMA e outro multivariado, para prever
as vendas de supermercados.

M-2 - Como você usou esses dados (vendas, cdi e datas) para
criar variáveis?

M-3 - Faça a modelagem numa estratégia de validação
com 2 backtests. Calcule o MAPE (Mean absolute percentage error)
para cada um desses backtests e reporte a média dos MAPEs.
Explique como definiu o tamanho do backtest (por exemplo:3,6,12 ou 24 meses).

M-4- Faça a previsão dos próximos 12 meses e crie um gráfico de linhas
(eixo X = date, eixo Y VendasSupermercados/Previsões) mostrando 1)
os últimos 4 anos de histórico de vendas, 2) as projeções dos
2 backtests, 3) o ano projetado.