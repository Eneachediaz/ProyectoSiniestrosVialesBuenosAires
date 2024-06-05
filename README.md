# Análisis de Homicidios Viales en la Ciudad Autónoma de Buenos Aires (CABA), Argentina

## Introducción

Este proyecto simula el rol de un Analista de Datos dentro de un equipo de consultoría. El Observatorio de Movilidad y Seguridad Vial (OMSV), adscrito a la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires, nos ha encomendado la tarea de realizar un análisis exhaustivo de datos.

El propósito de este análisis es proporcionar a las autoridades información clave para implementar estrategias que reduzcan el número de muertes ocasionadas por accidentes viales en CABA. Para ello, se nos ha provisto de un conjunto de datos sobre fallecimientos en accidentes viales entre 2016 y 2021.

Los entregables del proyecto incluyen un informe detallado sobre las actividades realizadas, las metodologías empleadas y las conclusiones principales, además de un dashboard interactivo que mejore la visualización y análisis de los datos.

## Contexto

Los accidentes de tránsito son incidentes que involucran vehículos y pueden ser causados por múltiples factores, resultando en daños materiales y/o físicos a los implicados. En la densamente poblada Ciudad Autónoma de Buenos Aires, con un tráfico considerable, estos eventos son una preocupación constante debido a su impacto en la seguridad pública, la infraestructura vial y los servicios de emergencia.

Con una población de 3,120,612 habitantes en un área de 200 km² según el censo de 2022, y más de 12 millones de vehículos circulando por sus autopistas en julio de 2023, la prevención de accidentes y la implementación de políticas de seguridad vial eficaces son cruciales.

## Objetivo y Estructura del Análisis

El objetivo de este análisis es identificar el tipo de accidente más común mediante un análisis demográfico, temporal y espacial, con el fin de desarrollar estrategias efectivas de prevención y seguridad vial. Así, el análisis se va a estructurar en tres secciones:

1. **Análisis demográfico:** ¿Quién se accidenta más?
2. **Análisis temporal:** ¿Cuándo suceden más accidentes?
3. **Análisis espacial:** ¿Dónde ocurren más accidentes?

Estas preguntas guían el enfoque del proyecto, proporcionando una visión clara para la toma de decisiones y la implementación de medidas de seguridad vial.

## Datos

El análisis se basó en la Base de Datos de Víctimas Fatales en Siniestros Viales, disponible en formato Excel con dos secciones: HECHOS y VÍCTIMAS, interconectadas por un ID único. Se proporcionan detalles sobre las definiciones y variables utilizadas en este documento.

## Análisis demográfico: ¿Quién se accidenta más?

Se analizó el perfil de las víctimas para identificar los grupos más vulnerables:

- **Distribución por Sexo:** La mayoría de las víctimas son hombres (78.2%), seguidas por mujeres (23.8%), con una pequeña fracción no especificada (0.9%).
- **Distribución por Edad:** La edad media de las víctimas es de 41.27 años, con una mediana de 35 años. El grupo de edad con mayor número de víctimas es el de 30 a 34 años.
- **Tipo de Transporte:** Las motos y los peatones son los más afectados, debido a su falta de protección en comparación con otros tipos de vehículos. Los motociclistas representan una proporción significativa de las víctimas.
- **Rol de la Víctima:** La categoría con mayor número de accidentes mortales es la de conductores (59.6%), seguida de peatones (48.5%). Esto sugiere que los conductores, especialmente los motociclistas, y los peatones son los más vulnerables en los accidentes viales.

## Análisis temporal: ¿Cuándo suceden más accidentes?

Se analizó la frecuencia de accidentes a lo largo del tiempo para identificar patrones estacionales y variaciones anuales:

- **Frecuencia Mensual:** Se observó una variabilidad considerable en el número de accidentes a lo largo del año, con picos en diciembre y enero y valores más bajos en abril, mayo y junio. Diciembre es el mes con mayor número de accidentes (78), mientras que abril es el mes con menos accidentes (50).
- **Frecuencia Anual:** Aunque se identifica una tendencia general a la baja en el número de accidentes, con una notable disminución durante el período de cuarentena por COVID-19 (2020), los datos de 2021 muestran un aumento respecto a 2020. Sin embargo, se necesita más información para determinar el comportamiento post-pandemia.
- **Frecuencia Diaria:** No se identificó un patrón claro en la distribución de accidentes por día de la semana, lo que sugiere que el día de la semana no es un factor determinante en la accidentalidad.
- **Frecuencia Horaria:** La distribución horaria de los accidentes muestra una tendencia en forma de "U", con un pico en las horas centrales del día (entre las 3:00 p.m. y las 9:00 p.m.), y menos accidentes en las horas de la madrugada y la noche. Las horas de mayor riesgo coinciden con los momentos de mayor actividad y tráfico.

## Análisis espacial: ¿Dónde ocurren más accidentes?

Se realizó un análisis geográfico para identificar las zonas con mayor riesgo de accidentes:

- **Frecuencia por Ubicación:** Los accidentes se concentran principalmente en avenidas. AV. General Paz es la avenida con mayor cantidad de accidentes mortales (57), casi triplicando la siguiente en la lista, AV. Rivadavia.
- **Cruces Peligrosos:** Los lugares más frecuentes para los accidentes son los cruces entre calles, destacándose el cruce de AV. 27 DE FEBRERO y AV. ESCALADA como el punto con más accidentes.
- **Distribución por Comunas:** La comuna con mayor número de accidentes mortales es la comuna 1 (90 accidentes), mientras que la comuna 0 registra el menor número de accidentes mortales (1 accidente). La disparidad en la cantidad de accidentes entre las diferentes comunas sugiere la influencia de factores como la densidad de población, la infraestructura vial y los comportamientos de conducción.

## Tecnologías Utilizadas

- **Python:** Para la manipulación y análisis de datos, utilizando bibliotecas como Pandas, NumPy, Matplotlib y Seaborn.
- **Power BI:** Para la creación de dashboards interactivos que permiten una visualización clara y detallada de los datos.

## KPI

En función del análisis previo, se establecieron tres objetivos para reducir la cantidad de víctimas fatales en siniestros viales, cada uno asociado a un indicador clave de rendimiento (KPI).

1. **Reducir en un 10% la tasa de homicidios en siniestros viales en los últimos seis meses en CABA, en comparación con el semestre anterior:** Este KPI se basa en la tasa de homicidios en siniestros viales, que mide el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes durante un período específico.

2. **Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año en CABA, respecto al año anterior:** Este indicador se basa en la cantidad de accidentes mortales de motociclistas, que mide el cambio porcentual en el número de accidentes mortales en los que estuvieron involucrados motociclistas entre dos años consecutivos.

3. **Reducir en un 5% la tasa de accidentes mortales en hombres de 25 a 35 años de edad en CABA respecto al año anterior:** Este KPI se enfoca en la tasa de accidentes mortales en hombres de 25 a 35 años, midiendo el cambio porcentual en el número de accidentes mortales en este grupo etario entre dos años consecutivos.

## Conclusiones

El análisis de los datos de accidentes viales con víctimas fatales en CABA revela patrones importantes y proporciona información valiosa para la toma de decisiones en la mejora de la seguridad vial. Algunas de las conclusiones clave incluyen:

1. **Temporabilidad:** No hay un patrón estacional claro, pero los picos de accidentes en diciembre y enero y la disminución en abril sugieren la necesidad de campañas de seguridad vial específicas durante estos meses. La reducción durante la cuarentena indica que las restricciones de movilidad tienen un impacto significativo en la reducción de accidentes.

2. **Perfil de Víctimas:** Los hombres jóvenes, especialmente aquellos entre 25 y 35 años, son los más vulnerables. Las estrategias deben enfocarse en la educación y concienciación de este grupo.

3. **Ubicaciones Críticas:** Las avenidas y cruces son los puntos más críticos. Es esencial implementar medidas de control de tráfico y mejorar la infraestructura en estos lugares para reducir los accidentes.

4. **Información Demográfica Completa:** Es clave tener presente que la información demográfica disponible solo nos permitió hacer un análisis centrado en las víctimas (aunque puede ser más útil la categoría de paciente). Para una versión posterior de este estudio, sería ideal contar con información demográfica no solamente de la víctima sino del acusado también. De esta forma se pueden identificar los perfiles de riesgo de manera más adecuada.
