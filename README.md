# DeepLearning
Deep learning (LSTM) - Cryprocurrency

Link: https://colab.research.google.com/drive/1Ssgk7kj2dk3ia4qshGyLToD09Qtg26nt?usp=sharing

**Dataset:**

Este conjunto de datos recopila información histórica de más de 50 criptomonedas, detallando sus datos OHLC (Open High Low Close) desde mayo de 2013 hasta octubre de 2022, con una frecuencia diaria. Los precios están expresados en dólares. El formato del archivo es CSV.

Los datos fueron recopilados de kaggle que a su vez extrajo y depuró el dataset del sitio web de Coin Market Cap mediante el uso de scripts automatizados.

________

**El datatset propone hacer las siguientes investigaciones:**

- Análisis de series temporales para distintas criptomonedas, basado en la fecha.
- Predicción de los precios de diferentes criptomonedas en el futuro.
_________


**Descripción de Columnas**

- **open**: Precio de apertura en la fecha específica (hora UTC).
- **high**: Precio más alto alcanzado en la fecha específica (hora UTC).
- **low**: Precio más bajo alcanzado en la fecha específica (hora UTC).
- **close**: Precio de cierre en la fecha específica (hora UTC).
- **volume**: Cantidad de activos comprados o vendidos, expresada en la moneda base.
- **marketCap**: El valor total de todas las monedas minadas, calculado multiplicando la cantidad de monedas en circulación por el precio de mercado actual de una sola moneda.
- **timestamp**: Marca de tiempo UTC del día considerado.
- **crypto_name**: Nombre de la criptomoneda.
- **date**: Marca de tiempo convertida al formato de fecha.
