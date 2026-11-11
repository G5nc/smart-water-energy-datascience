# Smart Water & Energy Data Science

Notebook de análise de dados, previsão de curto prazo e clustering para a Horta Inteligente.

## Integrante
- Gustavo Nobre Coppola (RM561423)

## Análise Realizada
- **Leitura e Compreensão:** 72 registros simulados de 3 dias de operação.
- **Análise Temporal:** Gráficos de linha mostrando a evolução do nível da água e do consumo de energia.
- **Previsão (MAE):** Uso de tendência linear (80% treino / 20% teste) para prever o consumo. O MAE foi de 0.0378 kWh.
- **Feature Engineering:** Criação da feature de "eficiência" (consumo / vazão).
- **Clustering (K-Means):** Agrupamento dos dados em 3 perfis operacionais (K=3) para identificar padrões de consumo.
- **Integração:** O notebook gera o arquivo `previsao_estacao.json`, que é consumido pelo backend Java (`smart-water-energy-api`).

## Como Executar
1. Clone o repositório.
2. Abra o notebook `SmartWater_Energy_DataScience.ipynb` no Jupyter Notebook ou Google Colab.
3. Execute as células em ordem.
