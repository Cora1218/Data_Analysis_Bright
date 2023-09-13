![header](https://github.com/Cora1218/Data_Analysis_Bright/blob/main/logo4.png) 

# Bright Data Analysis 
Conversion Rates

## Indice
<!-- TABLE OF CONTENTS -->
<details>
  <summary>Tabla de contenido</summary>
  <ol>
    <li><a href="#Introducción">Introducción</a></li>
    <li><a href="#Objetivo">Objetivo</a></li>
    <li><a href="#Alcance">Alcance</a></li>
    <li><a href="#Tecnologías">Tecnologías Utilizadas</a></li>
    <li><a href="#ETL-EDA">ETL-EDA</a></li>
    <li><a href="#Conclusiones relevantes">Conclusiones relevantes</a></li>
    <li><a href="#KPIs">KPIs</a></li>
    <li><a href="#PowerBI">PowerBI</a></li>
    <li><a href="#Desarrollador">Desarrollador</a></li>
  </ol>
</details>

## Introducción
En este proyecto, he explorado con profundidad la tasa de conversión, un pilar fundamental en el análisis de ventas. En Bright, nos enfrentamos al dilema: ¿qué proporción de nuestros clientes potenciales, una vez introducidos en el proceso, culminan siendo aprobados? Esta tasa de conversión específica se descompone en dos elementos esenciales: 1) los clientes potenciales que reciben una visita de ventas y, 2) aquellos que, tras una visita de ventas, alcanzan la aprobación necesaria.

Al emprender este proyecto, mi objetivo principal fue profundizar en la esencia misma de esta tasa de conversión. A través de análisis detallados y minuciosos, he buscado los factores que influyen en este proceso vital para cualquier estrategia de ventas exitosa. A medida que avancemos, les invito a adentrarse en este viaje de descubrimiento y comprensión de cómo optimizar y mejorar nuestra tasa de conversión para alcanzar el éxito deseado.

## Objetivo
Diseñar un dashboard interactivo que proporcione una visualización clara y detallada de la tasa de conversión en Bright. 

## Alcance
El proyecto fue desarrollado siguiendo los pasos a continuación:
1. ETL (Extracción, Transformación y Carga de Datos)
2. Desarrollo de dashboard con PowerBI

**Archivos en Google Drive:**
Puedes encontrar enlaces a los archivos de este proyecto (dashboard y tablas de los datos) en la carpeta: (https://drive.google.com/drive/folders/1IGkP-VnYduWkRe-B9sNfJr5OXJKnjtCZ).

## Tecnologías
- Python
- VSC
- Pandas
- Numpy
- MatplotLib
- Power Bi
- GitHub

## ETL-EDA
1. Carga de datos del archivo Bright.sqlite a dataframe.
2. Transformación de datos paso a paso y detección de anomalías.
3. Exportación de datos a archivos con formato csv.
4. Diagrama de entidad y relación.
5. Análisis de gráficos apropiados para el dashboard.
6. Generación de conclusiones.

El desarrollo de este proceso se puede ver aquí: [ETL Link](https://github.com/Cora1218/Data_Analysis_Bright/blob/main/bright.ipynb)

## Conclusiones relevantes
1. La mayor concentración de accidentes aéreos se encuentra entre los años 1940 y 2000, con el máximo en 1946 donde hubo un total de 87 accidentes. Esto se puede deber al hecho de que alrededor de 1950 la aviación comercial empezó a tener un auge en popularidad, años en los que también coincide la producción de las primeras generación de jets, las cuales tenían una alta tasa de accidentalidad e inadecuadas práticas de mantenimiento. 
2. La mayor cantidad de accidentes se ha dado en la ruta de Moscú, Rusia, lo cual concuerda con los datos de los operadores, dentro de los cuales, la aerolínea rusa Aeroflot tiene el mayor número de accidentes y mayor número de fatalidades. Esto apoya a los registros históricos, que constatan que Aeroflot ha tenido cinco veces más accidentes que cualquier otra aerolínea. 
3. Los accidentes aéreos militares superaron a los civiles en los tiempos de las guerras mundiales, lo cual tiene sentido ya que las fuerzas aéreas, como la Luftwaffe, tuvieron una incidencia significativa en estos conflictos. 
4. El modelo Douglas DC-3 que más ha tenido accidentes historicamente. Este modelo tuvo un alto impacto en la industria aérea durante las decadas de 1930, 1940 y la segunda guerra mundial (se vendió mucho). Estos aviones fueron acogidos tanto por industría aérea civíl, como por la militar. Se adaptaron varias versiones dependiendo el uso. Esto concuerda con las gráficas analizadas anteriormente, donde se pudo evidenciar una alta incidencia de accidentes después de 1940.
5. No suele haber muchas muertes en tierra a causa de accidentes aéreos, en comparación a las muertes de las personas a bordo. Sin embargo, se evidenció un pico máximo de fatalidades en tierra en el 2001, superando con creces a las muertes de personas a bordo, el cual corresponde al ataque terrorista al World Trade Center (9/11) en la ciudad de Nueva York, lo cual le da total sentido a este outlier. 
6. El año con mayor número de fatalidades parece ser 1972, lo cual tiene sentido porque en 1972 ya estaba operando la nueva generación de jets, que hasta el día de hoy siguen en uso y en producción, como el Boeing 737. Estos aviones son mucho más grandes que los de la primera generación y admiten muchos más pasajeros, por ende, en el caso de accidentes, lo más probable es que haya una mayor tasa de mortalidad, aunque no necesariamente haya una mayor tasa de accidentalidad.

## KPIs
1. `KPI 1`: Tasa de mortalidad 
- Métrica: Número de muertes a bordo/Número total de personal a bordo 
- Objetivo: Reducción del 5% anualmente
2. `KPI 2`: Tasa de fatalidades por accidentes
- Métrica: Número de muertes a bordo/Número total de accidentes
- Objetivo: Reducción de un 10% anualmente
3. `KPI 3`: Tasa de accidentes fatales
- Métrica: Número de accidentes donde no hubo sobrevivientes a bordo/Número total de accidentes
- Objetivo: Tasa de accidentes fatales por debajo del 50% anualmente
4. `KPI 4`: Tasa de accidentes sin fatalidades
- Métrica: Número de accidentes sin fatalidades a bordo/Número total de accidentes
- Objetivo: Aumento de un 10% en un periodo de 3 años

## PowerBI
Links de acceso para descarga del dashboard:

- Link MEGA: https://mega.nz/file/PZVgkKiL#cmJWWgZrk0rN2Vu08YaDEJjrRTHPN6auinmSsZaaBww

- Link Google Drive: https://drive.google.com/file/d/1YzWFc2t1ZZUCxJbnLFMK2_dkq3-X9tEq/view?usp=sharing

## Desarrollador
<div align="center">

 
| [<img src="https://avatars.githubusercontent.com/u/104804355?s=400&u=7c7592e2239f0ef414c4a3c5a61920ab19c9d980&v=4" width=115><br><sub>Karla Fajardo</sub>](https://github.com/ksfajardo) |
| :---: | 

Aquí esta mi Linkedin si te quieres poner en contacto conmigo: </br>

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karla-fajardo-3b3020175/)

</div>

<div align="center">
  
<img src="https://github.com/ksfajardo/PI02_DA/blob/main/hearttaylor.gif" width="200" height="250">

</div>
