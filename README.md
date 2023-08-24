<h1 align="center"> Cryptocurrency-Market </h1>

![CRIPTOMONEDAS](https://cdn.computerhoy.com/sites/navi.axelspringer.es/public/media/image/2021/11/criptomonedas-vs-acciones-diferencias-incovenientes-cual-mejor-opcion-dinero-2522591.jpg?tf=1200x)

  
# **INTRODUCCION**

Una criptomoneda es un activo digital que emplea un cifrado criptográfico para garantizar su titularidad y asegurar la integridad de las transacciones. Las criptomonedas se inventaron en 2009 con la creación de Bitcoin y han crecido en popularidad y cantidad desde entonces. 
En este proyecto encontraremos 10 criptomonedas, que son las 10 más populares actualmente y haremos un pequeño análisis de cada una.

## *CONTEXTO DEL ANALISIS*

Vamos a realizar un pequeño análisis donde tomaremos las 10 criptomonedas más populares hoy por hoy segun la [API CoinGecko](https://www.coingecko.com/es/api/documentation), donde tenemos:

- Binance
- Bitcoin
- Cardano
- Dogecoin
- Ethereum
- Ripple
- Solana
- Staked-Ether
- Tether
- USD Coin

`A tener en cuenta`: 
Dentro de este repositorio encontraremos un archivo 'csv' por cada moneda.

En el `EDA` encontraremos una tabla por cada moneda con los siguientes valores:

- snapped_at = Fecha y hora
- price = Precio en dolares (USD)
- market_cap = Capitalización de mercado
- total_volume = Volumen de comercio diario

### **EDA (Exploratory Data Analysis)**

Dentro del `EDA` podremos ver como hacemos una pequeña limpieza de datos, buscando valores nulos y/o duplicados y reemplazarlos según se considere, buscaremos Outliers o valores atípicos por cada DataFrame y nos adentraremos un poco en el por qué de estos valores, haremos una comparativa entre cada campo de los DataFrame y finalmente podremos ver los precios actuales de las monedas seleccionadas.
