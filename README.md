# Proyecto2 - Análisis de datos con Python

Este proyecto tiene como objetivo analizar el dataset de préstamos de Kiva, realizando una limpieza de datos, análisis estadístico y visualización para extraer conclusiones relevantes

## El flujo de trabajo realizado en el notebook sigue estos pasos:

1-Carga de datos: Importación del dataset y exploración inicial de la estructura

2-Exploración y Limpieza:

    .Verificación y búsqueda de duplicados.
   
    .Gestión de valores nulos (imputación o eliminación).

    .Eliminación de columnas irrelevantes para el análisis.

    .Conversión y corrección de tipos de datos.

3-Detección de Outliers: Identificación de valores atípicos en loan_amount y evaluación de su impacto.

4-Visualización: Creación de gráficos para representar la distribución


## Para el criterio que hemos elegido para la limpieza de datos es :

1-Hemos quitado nulos, duplicados y espacios en blanco

2-Hemos quitado la columna Tags y Funded_amount

3-Hemos cambiado el formato de fecha , el de pais y moneda pero nos lo marca en dtype como object

4-Hemos añadido el simbolo del $
