![header](https://github.com/Cora1218/Data_Analysis_Bright/blob/main/logo4.png) 

<div align="center">
  
## Bright Data Analysis 
</div>

## Problema 1: Tasas de conversión
<div align="justify">
Gran parte del análisis de ventas de Bright mide la tasa de conversión.  Por ejemplo, de todos los clientes potenciales cargados, ¿qué porcentaje de ellos se convierte en cliente aprobado?  Esa tasa de conversión concreta puede desglosarse en 2 partes: 1) clientes potenciales que reciben una visita de ventas y 2) clientes potenciales con una visita de ventas que se aprueban (ya que, de todos modos, cada cliente potencial necesita al menos una visita de ventas para ser aprobado).  
Si abreviamos "lead subido" como "Lead", Visita de ventas como "SV" y "cliente aprobado" como "APP". Podemos llegar a estas cifras falsas  El 5% de los clientes potenciales se aprueban, porque el 10% de ellos reciben visitas de ventas, y la mitad de nuestras visitas de ventas se convierten en clientes aprobados.
</div>

## Indice
<!-- TABLE OF CONTENTS -->
<details>
  <summary>Tabla de contenido</summary>
  <ol>
    <li><a href="#Introducción">Introducción</a></li>
    <li><a href="#Objetivo">Objetivo</a></li>
    <li><a href="#Propósito">Propósito</a></li>
    <li><a href="#Metodología">Metodología</a></li>
    <li><a href="#Archivos">Archivos en Google Drive</a></li>
    <li><a href="#Tecnologías">Tecnologías Utilizadas</a></li>
    <li><a href="#Conclusiones">Conclusiones relevantes</a></li>
    <li><a href="#PowerBI">PowerBI</a></li>
    <li><a href="#Desarrollador">Desarrollador</a></li>
  </ol>
</details>

## Introducción
<div align="justify">
En este proyecto, he explorado con profundidad la tasa de conversión, un pilar fundamental en el análisis de ventas. En Bright, nos enfrentamos al dilema: ¿qué proporción de nuestros clientes potenciales, una vez introducidos en el proceso, culminan siendo aprobados? Esta tasa de conversión específica se descompone en dos elementos esenciales: 1) los clientes potenciales que reciben una visita de ventas y, 2) aquellos que, tras una visita de ventas, alcanzan la aprobación necesaria.

Al emprender este proyecto, mi objetivo principal fue profundizar en la esencia misma de esta tasa de conversión. A través de análisis detallados y minuciosos, he buscado los factores que influyen en este proceso vital para cualquier estrategia de ventas exitosa. A medida que avancemos, les invito a adentrarse en este viaje de descubrimiento y comprensión de cómo optimizar y mejorar nuestra tasa de conversión para alcanzar el éxito deseado.
</div>

## Objetivo
Diseñar un dashboard interactivo que proporcione una visualización clara y detallada de la tasa de conversión en Bright. 

## Propósito
<div align="justify">
El dashboard tiene como propósito permitir a los equipos de ventas y marketing tener acceso a información crucial de manera rápida y efectiva. Esto les permitirá tomar decisiones informadas, ajustar estrategias y optimizar los esfuerzos para maximizar la tasa de conversión y, en última instancia, el éxito comercial de Bright.
</div>

## Metodología
El proyecto fue desarrollado siguiendo los pasos a continuación:
1. Análisis y Contexto del proyecto.
2. ETL (Extracción, Transformación y Carga de Datos) [ETL Link](https://github.com/Cora1218/Data_Analysis_Bright/blob/main/bright.ipynb).
   - Carga de datos del archivo Bright.sqlite a dataframe.
   - Transformación de datos paso a paso y detección de anomalías.
   - Exportación de datos a archivos con formato csv.
   - Diagrama de entidad y relación.
   - Análisis de gráficos apropiados para el dashboard.
   - Generación de conclusiones.
3. Desarrollo de dashboard con PowerBI.
4. Proyecto en GitHub.

## Archivos
Puedes encontrar enlaces a los archivos de este proyecto (dashboard y tablas de los datos) en la carpeta: (https://drive.google.com/drive/folders/1IGkP-VnYduWkRe-B9sNfJr5OXJKnjtCZ).

## Tecnologías
- Python
- VSC
- Pandas
- Numpy
- MatplotLib
- Power Bi
- GitHub 

## Conclusiones
<div align="justify">
A través de gráficos intuitivos y métricas clave, se tiene una visión en tiempo real de cómo los clientes potenciales se convierten en clientes aprobados, desglosando el proceso en sus elementos fundamentales: las visitas de ventas y las aprobaciones.
1.  Lead Cargados (97,69%):
El 97,69% de los clientes potenciales cargados indica un alto nivel de interacción y participación de la audiencia con el proceso de generación de leads. Este es un indicador positivo y sugiere una eficaz captación de clientes potenciales.
    Leads Aprobados (2,31%):
Aunque el porcentaje de leads aprobados es relativamente bajo (2,31%), esto no es necesariamente una señal negativa. Es importante tener en cuenta que no todos los leads cargados pueden cumplir con los criterios necesarios para la aprobación. Este bajo porcentaje podría ser indicativo de una selección rigurosa y adecuada de clientes potenciales para garantizar la calidad del cliente final.
2.  Leads Cargados (87,13%):
El 87,13% de leads cargados representa una participación sólida en el proceso de generación de leads. Esto indica una buena respuesta y una efectiva captación de posibles clientes interesados en los servicios o productos ofrecidos por Bright.
    Leads con Visita de Ventas Exitosa (12,87%):
Con un 12,87% de leads que culminan en una visita de ventas exitosa, se evidencia un flujo efectivo de prospectos hacia el siguiente paso del proceso. Esto señala una adecuada transición de la fase de adquisición a la fase de ventas.
3.   Leads con una Visita de Ventas Exitosa (86,21%):
Un impresionante 86,21% de leads que culminan en una visita de ventas exitosa es un indicador positivo. Esto sugiere una alta eficacia en la etapa de ventas y una capacidad destacada para convertir leads en oportunidades tangibles.
    Leads Aprobados (13,79%):
Aunque el porcentaje de leads aprobados es menor (13,79%), sigue siendo una cifra significativa. Esto indica un proceso de selección riguroso pero efectivo para asegurarse de que solo los leads más prometedores sean aprobados.
</div>
Así mismo, el dashboard proporciona una visión detallada de la evolución de leads y conversiones en Bright a lo largo de los últimos años. 

<div align="left">
- Este gráfico combina una representación de barras y líneas para mostrar la tendencia de "Leads con una visita de ventas exitosa" y "Leads aprobados" a lo largo del tiempo, con el eje x representando los años y el eje y mostrando el número de leads.
</div>
<div align="center"><img src="https://github.com/Cora1218/Data_Analysis_Bright/blob/main/bright.png" width=500><sub>Gráfico de Barras y Líneas: Leads con Visita Exitosa y Leads Aprobados</sub></div>

<div align="left">
   Esta representación visual ofrece una perspectiva clara y concisa de la efectividad de las visitas de ventas y el proceso de aprobación en la conversión de leads en clientes a lo largo de los años.
</div>   

## PowerBI
Links de acceso para descarga del dashboard:

- [https://drive.google.com/drive/folders/1IGkP-VnYduWkRe-B9sNfJr5OXJKnjtCZ](https://drive.google.com/file/d/1g9aweonMI-f7gBr2gmJJrLyyJu0tEUd0/view?usp=drive_link)

Links de acceso para visualizar el dashboard:

- https://app.powerbi.com/links/iB3mYt_ZkB?ctid=a9e17f9e-90be-41d0-84eb-6a48ebe9fec0&pbi_source=linkShare

## Desarrollador
<div align="center">
 
| [<img src="https://github.com/Cora1218/Data_Analysis_Bright/blob/main/yo.png" width=115><br><sub>Maria Martínez</sub>](https://github.com/Cora1218) |
| :---: | 

Dejo mi Linkedin para ponerte en contacto conmigo: </br>

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mar%C3%ADa-guadalupe-mart%C3%ADnez-1a489173/)

</div>

