[English Bellow]
# Dataset
O dataset utilizado para o desafio pode ser encontrado no seguinte link: 
https://www.kaggle.com/tevecsystems/retail-sales-forecasting

# Prévia
Esta análise tem como objetivo, realizar uma previsão de vendas de uma loja. Para isso, foram utilizados os métodos preditivos ARIMA e Prophet, de forma a identificar qual deles alcançava o menor erro, ao comparar dados de validação com dados preditivos. Dentro do link disponibilizado, encontra-se um breve texto encorajando a realizar a previsão de vendas das 2 a 3 semanas seguintes aos últimos dados fornecidos, tendo sido utilizadas 3 semanas como base.

# Parâmetros Utilizados
Para comparar ambos os métodos, foram utilizadas as últimas 3 semanas de dados fornecidos, de forma a serem os dados de validação. Calculou-se a previsão dos valores que seriam correspondentes a essas 3 semanas, e por fim, foram comparados os dados de validação com os dados de previsão, através da raíz quadrada do erro médio quadrado.

# Resultado
O método que alcançou a menor raíz quadrada do erro médio quadrado foi o ARIMA. Dessa forma, apenas os dados futuros referentes a ele foram considerados. Na primeira semana de previsão, as vendas obteriam valor de 1556 (podendo variar entre 904 e 1407), na segunda semana de 1067 (podendo variar entre 814 e 1318), e na terceira semana de 1282 (podendo variar entre 1029 e 1533).

-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-

# Dataset
The dataset used for the challenge can be found at the following link:
https://www.kaggle.com/tevecsystems/retail-sales-forecasting

# Preview
This analysis aims to make a sales forecast for a store. For this, the ARIMA and Prophet predictive methods were used, in order to identify which one reached the smallest error, when comparing validation data with predictive data. Within the link provided, there is a brief text encouraging you to make a sales forecast for 2 to 3 weeks following the last data provided, using 3 weeks as a base.

# Used Parameters
To compare both methods, the last 3 weeks of data provided were used to be the validation data. The predicted values that would correspond to these 3 weeks were calculated, and finally, the validation data were compared with the prediction data, through the square root of the mean squared error.

# Result
The method that reached the smallest square root of the mean squared error was ARIMA. In this way, only future data referring to it were considered. In the first week of the forecast, sales would obtain a value of 1556 (which could vary between 904 and 1407), in the second week of 1067 (which could vary between 814 and 1318), and in the third week of 1282 (which could vary between 1029 and 1533).
