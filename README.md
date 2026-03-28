# Power BI Dashboard Afluencia del Metro

<img width="1129" height="638" alt="Analisis metro" src="https://github.com/user-attachments/assets/a732b022-8e8b-418a-be39-171f8de75c64" />


*Vista principal del dashboard de afluencia del Metro CDMX*

## Descripción del Proyecto

Dashboard interactivo desarrollado en **Power BI** que analiza la afluencia de pasajeros en el Sistema de Transporte Colectivo Metro de la Ciudad de México, con datos históricos desde **2010 hasta 2026**.

## Conclusiones

El análisis de la afluencia del Sistema de Transporte Colectivo (STC) Metro de la Ciudad de México durante el período **2010-2026** ha permitido identificar patrones clave, cuantificar el impacto de eventos extraordinarios y proyectar la recuperación del sistema. A continuación, se presentan los hallazgos más relevantes:

---

### Hallazgos Principales

#### 1. Dimensión del sistema
- **1,151,085 registros** analizados, abarcando **166 estaciones** distribuidas en **12 líneas**
- **22,638 millones de pasajeros** transportados durante los 16 años de estudio
- **Promedio diario histórico de 3.8 millones de pasajeros**, con máximos que superan los 4.5 millones en días hábiles

#### 2. Impacto de la pandemia COVID-19
- La afluencia **cayó un 65% en 2020** respecto a 2019, alcanzando mínimos históricos
- El punto más bajo se registró en abril-mayo 2020, con menos de 500,000 pasajeros diarios
- **2021 fue el año con menor afluencia** de toda la serie histórica, con solo 794 millones de pasajeros anuales

#### 3. Recuperación post-pandemia
- La recuperación ha sido **gradual pero constante**, con una tasa de crecimiento del **15-20% anual**
- **2025 cerró con 1,255 millones de pasajeros**, un **78% de recuperación** vs 2019
- La proyección lineal estima que los **niveles pre-pandemia se alcanzarían hacia finales de 2027 o principios de 2028**

#### 4. Estaciones y líneas de mayor demanda
- **Pantitlán** lidera con **1,404 millones de pasajeros**, consolidándose como el principal nodo de transferencia
- Las **5 estaciones más transitadas** concentran aproximadamente el **20% del total de la afluencia**
- **Línea 2** (Cuatro Caminos - Tasqueña) es la más utilizada con **3,974 millones de pasajeros**, seguida por Línea 3 y Línea 1

#### 5. Patrones estacionales
- **Agosto y septiembre** (regreso a clases) registran los mayores picos de afluencia
- **Diciembre y enero** muestran una disminución considerable por periodos vacacionales
- **Martes y miércoles** son los días de mayor demanda, mientras que los domingos concentran la menor actividad

El proyecto incluye:
- Limpieza y procesamiento de datos con Python (Pandas)
- Análisis de datos
- Visualizaciones interactivas en Power BI
- Métricas clave de afluencia por estación, línea y periodo

## Visualizaciones Incluidas

-  **Tendencia histórica**: Evolución de la afluencia por año y mes
-  **Top estaciones**: Ranking de las estaciones con mayor afluencia
-  **Distribución por línea**: Participación de cada línea en el total
-  **Análisis estacional**: Comportamiento por meses y días de la semana
-  **Filtros interactivos**: Por año, línea y estación

##  Tecnologías Utilizadas

- **Python**: Limpieza y procesamiento de datos
- **Pandas**: Manipulación y análisis de datos
- **Power BI**: Visualización y dashboard interactivo
- **Git/GitHub**: Control de versiones

##  Notas Importantes

- Los datos fueron obtenidos de https://datos.cdmx.gob.mx/dataset/afluencia-diaria-del-metro-cdmx
- La limpieza incluyó corrección de codificación de caracteres (acentos)
- El dashboard permite filtrar por rango de fechas y líneas específicas
