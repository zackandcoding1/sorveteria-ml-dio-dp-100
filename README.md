# Simulação de Sorveteria com Azure ML
Simulação de vendas de uma sorveteria considerando a temperatura para gerar uma regressão linear com Azure ML

O projeto foi feito baseado no desafio proposto, considerando o cenário de uma sorveteria localizada no Rio de Janeiro realizando uma simulação de 100 dias de vendas considerando que as mudanças de temperatura na cidade podem impactar no aumento ou diminução de vendas de sorvetes. O objetivo principal é treinar um modelo de Machine Learning para prever a quantidade ideal do produto em cada dia a partir do clima.

![image](https://github.com/user-attachments/assets/e3a000b7-a055-4b86-9d95-dd1b9cc27294)

A tabela apresentada foi utilizada no Azure Machine Learning, por meio de um processo de Machine Learning Automatizado (AutoML). Durante a simulação, foram utilizadas as variáveis "Temperatura" e "Vendas" para treinar um modelo preditivo de regressão.

Após o treinamento, o modelo foi avaliado utilizando o Designer do Azure ML, e as previsões de vendas foram geradas na coluna Scored Labels, que representa a quantidade de vendas previstas pelo modelo para cada temperatura observada.

Comparando os valores reais de vendas com as previsões, percebe-se que a diferença (erro) foi mínima, indicando um bom desempenho do modelo. Os gráficos de barras ao lado dos valores ajudam a visualizar rapidamente a distribuição e a proximidade entre vendas reais e previstas.

Após a conclusão do treinamento, o modelo escolhido apresentou um excelente resultado, atingindo uma variância explicada (R²) de 0.9495. Esse valor indica que aproximadamente 94,95% da variação nas vendas de sorvete pode ser explicada pelo modelo a partir da temperatura do dia. Em termos práticos, isso significa que o modelo tem uma capacidade muito boa de prever a quantidade de sorvetes vendidos com base na temperatura, tornando-se uma ferramenta bastante confiável para apoiar o planejamento de produção da sorveteria.

![image](https://github.com/user-attachments/assets/e5e2d70f-6e62-4911-a74d-7d71df390708)

![image](https://github.com/user-attachments/assets/83594610-ad14-443c-9f67-ff8553c1d326)
