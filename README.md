# challenge-telecomx-paola-manrique
Hola Mi nombre es Cindy Paola Manrique y a continuacion muestro los resultados del presente analisis en el presente informe:

# Análisis Exploratorio de Datos (EDA) - Churn

Este proyecto realiza un Análisis Exploratorio de Datos (EDA) para analizar el abandono de clientes (Churn) y su relación con los cargos mensuales.

## Objetivo
El objetivo de este Análisis Exploratorio de Datos (EDA) es comprender el comportamiento de los clientes y analizar los factores asociados al abandono (Churn), con el fin de identificar patrones, problemas potenciales y oportunidades de mejora que permitan reducir la tasa de abandono.

## Descripción del Dataset

El dataset contiene información de clientes, incluyendo variables categóricas y numéricas relacionadas con su permanencia en la empresa.
Variables relevantes analizadas:
Churn: indica si el cliente abandonó la compañía (YES / NO).
account.Charges.Monthly: cargos mensuales del cliente.
El dataset incluye tanto clientes activos como clientes que han abandonado el servicio.

- Revisión y Preparación de los Datos
  
  - Tipos de datos
Churn: variable categórica (YES / NO).
account.Charges.Monthly: variable numérica continua.
Se verificó que los cargos mensuales estuvieran en formato numérico y se corrigieron posibles valores no válidos.

 -Valores faltantes
Se realizó una revisión de valores nulos para asegurar la calidad del análisis.
Los valores faltantes en variables numéricas fueron tratados adecuadamente para evitar distorsiones en los gráficos.

## Análisis Exploratorio

- Análisis Univariado
  
🔹 Distribución de Churn
El gráfico de distribución muestra que:
La mayoría de los clientes NO abandona la compañía.
Existe un porcentaje significativo de clientes que SÍ abandonan, lo cual representa una oportunidad de mejora para el negocio.

Insight:
Aunque la mayoría de los clientes se mantiene, el volumen de abandono es lo suficientemente relevante como para justificar acciones estratégicas de retención.

- Análisis Bivariado
  
🔹 Relación entre Churn y Cargos Mensuales
Al analizar los cargos mensuales según el estado de churn, se observa que:
Los clientes que abandonan (YES) presentan cargos mensuales más altos en promedio.
Existe mayor dispersión en los cargos de los clientes que abandonan, lo que sugiere variabilidad en la percepción del valor del servicio.

Insight:
Los cargos mensuales elevados parecen estar asociados a una mayor probabilidad de abandono.

## Insights Relevantes

A partir del EDA se identificaron los siguientes insights clave:

El churn no es aleatorio: existe una relación clara entre el abandono y el nivel de cargos mensuales.
Clientes con cargos altos son más propensos a abandonar, lo que puede indicar insatisfacción con el precio o el servicio recibido.
La variabilidad en los cargos de clientes que abandonan sugiere que no todos los clientes perciben el mismo valor por el mismo costo.

## Herramientas
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Recomendaciones

Basado en los insights obtenidos, se recomiendan las siguientes acciones:
- Revisar la estructura de precios para clientes con cargos mensuales elevados.
- Implementar estrategias de retención específicas para clientes con mayor probabilidad de churn.
- Ofrecer descuentos, planes personalizados o beneficios adicionales a clientes de alto riesgo.
- Profundizar el análisis con más variables (tipo de contrato, servicios adicionales, antigüedad).

## Conclusión

El Análisis Exploratorio de Datos permitió comprender mejor el comportamiento de los clientes y detectar factores clave asociados al abandono.
Este EDA proporciona una base sólida para la toma de decisiones estratégicas y para el desarrollo de modelos predictivos de churn en futuras etapas del análisis.
