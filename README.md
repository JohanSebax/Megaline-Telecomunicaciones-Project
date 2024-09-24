# Descripción del proyecto

Trabajas como analista para el operador de telecomunicaciones Megaline. La empresa ofrece a sus clientes dos tarifas de prepago, Surf y Ultimate. El departamento comercial quiere saber cuál de los planes genera más ingresos para poder ajustar el presupuesto de publicidad.

Vas a realizar un análisis preliminar de las tarifas basado en una selección de clientes relativamente pequeña. Tendrás los datos de 500 clientes de Megaline: quiénes son los clientes, de dónde son, qué tarifa usan, así como la cantidad de llamadas que hicieron y los mensajes de texto que enviaron en 2018. Tu trabajo es analizar el comportamiento de los clientes y determinar qué tarifa de prepago genera más ingresos. Más adelante, encontrarás en las instrucciones del proyecto cuáles son exactamente los aspectos del comportamiento de los clientes que debes analizar. Determinar qué plan, en promedio, aporta más ingresos es una cuestión que se abordará mediante pruebas estadísticas.

# Descripción de las tarifas

**Nota:** Megaline redondea los segundos a minutos y los megabytes a gigabytes. Para llamadas, cada llamada individual se redondea: incluso si la llamada duró solo un segundo, se contará como un minuto. Para tráfico web, las sesiones web individuales no se redondean. En vez de esto, el total del mes se redondea hacia arriba. Si alguien usa 1025 megabytes este mes, se le cobrarán 2 gigabytes.

A continuación puedes ver una descripción de las tarifas:

**Surf**

1. Pago mensual: 20$.
2. 500 minutos al mes, 50 SMS y 15 GB de datos.
3. Si se exceden los límites del paquete:

- 1 minuto: 3 centavos.
- 1 SMS: 3 centavos.
- 1 GB de datos: 10$.

**Ultimate**

1. Pago mensual: 70$.
2. 3000 minutos al mes, 1000 SMS y 30 GB de datos.
3. Si se exceden los límites del paquete:

- 1 minuto: 1 centavo.
- 1 SMS: 1 centavo.
- 1 GB de datos: 7$.

# Diccinario de datos

En este proyecto, trabajarás con cinco tablas diferentes.

1. La tabla **users** (datos sobre los usuarios).
2. La tabla **calls** (datos sobre las llamadas).
3. La tabla **messages** (datos sobre los SMS).
4. La tabla **internet** (datos sobre las sesiones web).
5. La tabla **plans** (datos sobre las tarifas).

## 🛠 Skills
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)

![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)

![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

**Seaborn**

## Lessons Learned

Aprendi a implementar analisis estadistico en datos y filtrado & agrupación de datos. Pude realizar pruebas de hipotesis estadisticas usando pruebas y modelos estadisticos. 

# Conclusiones

- El plan y las tarifas de Surf es la que más genera ingresos en comparación al plan Ultimate.

- El plan Surf representa más cantidad de minutos y trafico de internet por usuario lo que genera una cantidad considerable de ingreso por cada mes.

- Parece que los usuarios tienden a gastar la misma cantidad de minutos sin importar el plan pero hay mas cantidad de minutos por usuario en el plan Surf en comparacion al plan Ultimate, lo que indica que los usuarios prefieren usar el plan mas economico en la tarifas de minutos ya que terminan pagando menos por los mismos minutos, igualmente esto hace que se genere una cantidad considerable de ingresos especialmente en el consumo de internet.

- Debemos hacer un ajuste de inversion mayor en el plan de Ultimate para tener ingresos altos en ambos planes en caso de que sea posible y asi poder ajustar el presupuesto de publicidad. Tambien puede ser que es mas conveniente hacer publicidad al plan Surf ya que este plan es el que mas ingresos proporciona por usuarios.
