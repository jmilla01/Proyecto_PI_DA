# 
<p align=center><img src=https://neurona-ba.com/wp-content/uploads/2021/07/HenryLogo.jpg><p>

# <h1 align=center>  Proyecto Individual NRO 2  </h1>

# <h1 align=center>**`Data Analytics`**</h1>

<p align=center><img src=https://www.clarin.com/img/2023/06/14/WJlAYJhAg_1256x620__1.jpg><p> 


# JOAQUIN MILLAN LANHOZO - AGOSTO 2023 - DTPT02

# SOY HENRY

El trabajo aquí expuesto fue realizado durante la cursada en la institución Soy Henry, formo parte de la cohorte DATAPT02 y este es el segundo proyecto integrador enfocado en Data Analytics

<Vr> 


## Tabla de contenidos
- [Archivos en el Repositorio](#archivos-en-el-repositorio)
- [Contexto](#contexto-del-proyecto)
- [Criptomonedas elegidas](#criptomonedas-elegidas)
- [Descripción de las criptomonedas](#descripcion-de-las-criptomonedas)
- [KPI's](#kpi)
- [Conclusión](#conclusión)
- [Stack tecnologico](#stack-tecnologico)
- [Bibliografía](#bibliografia)



# ARCHIVOS EN EL REPOSITORIO

<hr> 

+ Archivo "Conocimiento de la API y fuentes de datos" --> En este archivo esta la visualización y testeo de la API con sus funciones e información contenida en la web, una exploración a nivel informativo para poder familiarizarme y ver la fuente requerida que es la conexión a la API de CoinGecko y a su vez, consulto la API de Yahoo Finance y un dataset de Kaggle.

+ Archivo "PI_DA_Crypto_dataset.ipynb" --> Consulta a las fuentes de datos y armado del dataset que luego será consumido para el EDA y Dashboard.

+ Archivo "dataset_final.csv" --> Este es el archivo creado en Python armado con las fuentes de datos anteriormente mencionadas. En donde, junto la información de las fuentes y tomo la información que considero útil para el proyecto.

+ Archivo "EDA.ipynb" --> Análisis exploratorio de los datos, de las criptomonedas elegidas.

+ Archivo "requirements.txt" --> Este archivo tiene los requerimientos que utilizan las notebooks.

[Tabla de Contenidos](#tabla-de-contenidos)

# Contexto del proyecto

El proyecto realizado como primer paso tuvo la obligación de la conexión y acceso a la API de CoinGecko para extraer datos sobre las criptomonedas. 

Debido al corto periodo de realización de trabajo, el análisis había que centrarlo en 10 criptomonedas a libre elección.

En cuanto al objetivo del trabajo, había que realizar un análisis exhaustivo para poder presentar con estos datos, una historia para entender mejor el mercado de criptomonedas y presentar hallazgos y recomendaciones en un informe detallado. El mismo además de tratamiento de datos, análisis exploratorio de datos, la utilización de KPI's y un Dashboard interactivo  para poder visualizar e interactuar diferentes perspectivas de la temática.

[Tabla de Contenidos](#tabla-de-contenidos)
<Vr> 

# CRIPTOMONEDAS ELEGIDAS

Las criptomonedas son monedas digitales que utilizan métodos de criptografía para asegurar las transacciones. Esto significa que es un sistema descentralizado en el que mediante la tecnología blockchain, en donde cada agente de la red garantiza la seguridad y el equilibrio de las transacciones, es como un gran libro de contabilidad inmodificable y compartido que van escribiendo una gran cantidad de ordenadores de forma simultánea.

Las 10 criptomonedas elegidas son las 10 que actualmente tienen más market capitalization (la mayor cantidad de capitalización en el mercado) según: https://coinmarketcap.com/ 

- BTC - BITCOIN
- ETH - ETHEREUM
- USDT - TETHER USDT
- BNB - BNB
- XRP - RIPPLE
- USDC - USD COIN
- DOGE - DOGECOIN
- ADA - CARDANO
- SOL - SOLANA
- TRX - TRON

[Tabla de Contenidos](#tabla-de-contenidos)
<Vr> 

# DESCRIPCION DE LAS CRIPTOMONEDAS

### BITCOIN - BTC

Bitcoin (BTC) es la criptomoneda más antigua de todas y nació en el año 2009. Es la moneda más popular y con mayor capitalización de mercado, fue la precursora de las criptomonedas, de la descentralización en activos financieros digitales utilizando la tecnología blockchain. Su oferta es limitada y cada 4 años hay halvings (más información en EDA)

### ETHEREUM - ETH

Ethereum (ETH) es una plataforma y criptomoneda descentralizada creada por el Ruso Vitalik Buterin en 2015.Ethereum se desarrolló como una plataforma que permite a los desarrolladores construir y ejecutar aplicaciones descentralizadas (DApps) y contratos inteligentes en su blockchain. (Más información en el EDA)

### TETHER - USDT

Tether es una criptomoneda estable que está diseñada para mantener un valor estable en relación con una moneda fiduciaria, generalmente el dólar estadounidense (USD). A diferencia de muchas otras criptomonedas que pueden ser volátiles en términos de precios, Tether se crea con la intención de proporcionar estabilidad y fungibilidad similares a las monedas tradicionales (más información en el EDA)

### BINANCE COIN - BNB

Binance Coin, es la moneda que pertenece y fue creada por la actual sitio de Exchange más grande y con más movimientos de criptomonedas. (Más información en el EDA)

### RIPPLE - XRP

XRP es parte de una plataforma y red de pago que busca facilitar transferencias de dinero rápidas y eficientes a nivel global. A diferencia de muchas otras criptomonedas, XRP no se basa en tecnología blockchain descentralizada, sino que utiliza un enfoque diferente llamado Red de Validación Ripple (RippleNet). (Más información en el EDA)

### USD COIN - USDC 

 El objetivo principal de USDC es proporcionar una moneda digital que mantenga una paridad cercana al dólar estadounidense y que sea útil para transacciones y contratos inteligentes en el espacio de las criptomonedas. (Más información en el EDA)

### DOGECOIN - DOGE

Dogecoin es una criptomoneda que nació en 2013 como una versión paródica de Bitcoin. Aunque comenzó como una broma, Dogecoin se ha convertido en una criptomoneda popular y querida en la comunidad cripto. (Más información en el EDA)

### CARDANO - ADA

Cardano (ADA) es una plataforma de blockchain y una criptomoneda que se centra en la investigación y la ingeniería de alto nivel para crear una red escalable y segura. (Más información en el EDA)

### SOLANA - SOL

Solana es una plataforma blockchain de alto rendimiento diseñada para proporcionar escalabilidad y velocidad en la ejecución de aplicaciones descentralizadas (DApps) y contratos inteligentes. (Más información en el EDA)

### TRON - TRX

TRON (TRX) es una plataforma blockchain descentralizada que tiene como objetivo crear un ecosistema para la descentralización de contenido y aplicaciones en la web. Fue fundada por Justin Sun en 2017 con el objetivo de revolucionar la forma en que se comparte y consume contenido en línea. TRON se centra en la industria del entretenimiento y la creación de contenido digital. 

[Tabla de Contenidos](#tabla-de-contenidos)
<Vr> 


<Vr> 

# KPI

Los KPI's son indicadores claves de performance, indicadores de desempeño, respecto de un objetivo propuesto por una organización, para medir dicho desempeño se utilizan medidas numéricas denominadas métricas, en relación con los objetivos preestablecidos. Los KPI son utilizados para medir el progreso y el éxito en áreas clave como ventas, productividad, rentabilidad, eficiencia y satisfacción del cliente. En el dashboard los podremos ver

* <u>Retorno de la inversión (ROI)</u> -->  El objetivo para los próximos cuatro años es lograr un Retorno de Inversión (ROI) de al menos el 15% en nuestra cartera de criptomonedas, asegurando un crecimiento rentable de nuestros activos digitales. Este objetivo se medirá tomando en cuenta la relación entre las ganancias netas generadas por nuestras inversiones y el capital invertido inicialmente.

El ROI es utilizado como un indicador clave en la industria financiera, que sirve para obtener el retorno de una inversión realizada por una empresa o acción. Para calcular el ROI es necesario saber cuáles fueron las ganancias y que monto se invirtió. Es un indicador que utilizare, el cual me parece clave para poder medir la performance de las inversiones realizadas.


<h1 align=center><img src="data:image/png;base64,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" width="300" alt="Alt Text"></h1>


* <u>Indicador de Fuerza relativa (RSI)</u>: Al cabo de dos años, lograr un 60% de operaciones exitosas al utilizar el RSI como guía para tomar decisiones de compra y venta en criptomonedas

El RSI es un oscilador que se encuentra en un rango entre 0 y 100 y se utiliza para identificar condiciones de sobrecompra y sobreventa en un activo. Cuando el RSI está por debajo de 30, decimos que está en sobreventa, lo esperado es que el precio se mueva hacia arriba (holdear y posicionarse en largo).

Cuando el RSI está por encima de 70, sobrecompra, pasa justo lo contrario, así que lo esperado es que el precio caiga, por lo que tendríamos la mirada puesta en posiciones cortos.

* <u>Rendimiento por Período</u>: Lograr un rendimiento positivo en la inversión a lo largo dos años que supere al menos un 10% en relación con la inversión inicial y el precio inicial de la criptomoneda.

Mide el porcentaje de cambio en el precio de la criptomoneda durante un período de tiempo específico.

Rendimiento por periodo = ((Precio Final - Precio Inicial) / Precio Inicial) * 100

* <u>Precios Máximos</u>: Utilizar el precio máximo histórico como referencia para evaluar el rendimiento actual y potencial de la criptomoneda en relación con su precio más alto registrado.

Este KPI establece una referencia del precio máximo alcanzado por una criptomoneda específica, con el propósito de evaluar el rendimiento y las oportunidades de ganancia en función de este precio histórico.

* <u>Diversificación del Portfolio</u>: Número de Activos Diversificados = Al finalizar los próximos cinco años, se busca que un porcentaje significativo de usuarios cuente con al menos tres activos diferentes en sus carteras de inversión, lo que reflejará una estrategia efectiva de diversificación y contribuirá a la reducción del riesgo de inversión. Esta diversificación de portfolio coincide con el perfil de inversor cliente al que está destinada la cartera de activos de inversión.
  
Número de Activos Diversificados = Total de Usuarios con al menos 3 Activos Diferentes / Total de Usuarios

[Tabla de Contenidos](#tabla-de-contenidos)

# Conclusión

Tras analizar el mercado de las criptomonedas, principalmente el de estas 10 monedas, noto un mercado que se instaló rápidamente y debido a su descentralización, con su amplio acceso y facilidad por parte de billones de usuarios, lo que permite un fácil acceso y esto hace que sea una comunidad que crece exponencialmente, con las funcionalidades y el mercado asociado a estas monedas. La tecnología en la que se basa, Blockchain permite que esto mismo se pueda dar y da lugar a todos estas millones de transacciones y a los usuarios que interactúan con ellas.

Se puede ver el primer gran crecimiento que tuvieron las criptomonedas en 2017, cuando empezaron a ser más populares y se dieron a conocer aún más de la mano de la precursora, el Bitcoin. Por otro lado, se nota el incremento que todas las monedas tuvieron en el segundo gran crecimiento exponencial de las criptomonedas en 2021. Y como luego, a finales del 2021 empiezan a caer los precios de todas las monedas pero a un precio ubicado entre la mitad del pico y de lo que eran antes de esa corriente alcista.

El mercado de las criptomonedas contiene una amplia variedad de monedas, cada una con sus propias características y niveles de volatilidad. La volatilidad asociada a este mercado ha sido un aspecto llamativo, y su influencia se ha expuesto a lo largo del análisis. Además, este mercado opera con volúmenes financieros muy altos, lo que refleja el significativo interés y participación de inversores y usuarios en todo el mundo.

Es importante destacar que la volatilidad puede generar oportunidades excepcionales de generación de riqueza en un período relativamente corto, así como también presentar desafíos sustanciales. La experiencia del mercado de criptomonedas se asemeja a una montaña rusa financiera, donde las ganancias y las pérdidas pueden ser extremadamente pronunciadas. Estos caminos destacan la importancia de la educación financiera, la comprensión profunda del mercado y la adopción de una estrategia de inversión bien fundamentada.

Hay que destacar la constante evolución del desarrollo de las criptomonedas, como su evolución fue adaptando distintas tecnologías y como estas monedas con sus tecnologías y funcionalidades impulsan avances tecnológicos como Cardano, o como monedas como tron impulsan el desarrollo de la industria del entretenimiento. Y como monedas como el USDC y USDT, son una fuente segura de ahorros con un respaldo y paridad cuasi perfecta 1:1 vs dólar. Como hemos visto, hay varios casos en solo estas 10 monedas de lo grande, compleja y abarcativa que son las criptomonedas.

[Tabla de Contenidos](#tabla-de-contenidos)
<Vr> 

# STACK TECNOLOGICO

+  Notebook desarrollada en python a traves de Visual Studio Code.
+  Libreria numpy -- [Numpy](https://numpy.org/) Numerical Pyhton útil para realizar cálculos lógicos y matemáticos sobre cuadros y matrices.
+  Libreria pandas -- [Pandas](https://pandas.pydata.org/) Pandas es una librería de Python especializada en el manejo y análisis de estructuras de datos
+  Libreria matplotlib -- [Matplotlib](https://matplotlib.org/) Matplotlib libreria para la visualización de datos.
+  Libreria seaborn -- [Seaborn](https://seaborn.pydata.org/) Seaborn libreria para la visualización de datos.
+  Libreria plotly [Plotly](https://plotly.com/python/) Plotly libreria para la visualizacion de datos.
+  Libreria datetime -- [Datetime](https://docs.python.org/es/3/library/datetime.html) Datetime libreria utilizada para la transformación a formato fecha´
+  Libreria request -- [Request](https://pypi.org/project/requests/) Se utiliza para hacer solicitudes HTTP a través de la red, en este proyecto para acceder a las APIS.
+ API CoinGecko -- [Coingecko](https://www.coingecko.com/es/api/documentation) API con datos de criptomonedas
+ API Yahoo Finance -- [YFinance](https://pypi.org/project/yfinance/) API con datos de criptomonedas

[Tabla de Contenidos](#tabla-de-contenidos)
<Vr> 

# BIBLIOGRAFIA

Material de la cursada en Soy henry

https://www.nationalgeographic.com.es/mundo-ng/que-son-criptomonedas-y-como-funcionan_16981#google_vignette

https://www.euroinnova.com.ar/blog/latamhistoria-de-las-criptomonedas#:~:text=En%201995%2C%20Chaum%20desarroll%C3%B3%20unel%20origen%20de%20las%20criptomonedas

https://www.ibm.com/es-es/topics/blockchain

https://www.bitpanda.com/academy/es/lecciones/que-es-la-capitalizacion-del-mercado-market-cap-y-por-que-importa/

 
https://www.centralcharts.com/es/gm/1-aprender/1-criptomoneda/42-trading

https://www.euroinnova.com.ar/blog/latamhistoria-de-las-criptomonedas#:~:text=En%201995%2C%20Chaum%20desarroll%C3%B3%20unel%20origen%20de%20las%20criptomonedas

https://ethereum.org/es/what-is-ethereum/:~:text=Ethereum%20es%20una%20red%20quecontrolada%20por%20una%20autoridad%20central

https://learn.bybit.com/es/altcoins/que-es-bnb-binance-coin/

[Tabla de Contenidos](#tabla-de-contenidos)




