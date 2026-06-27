**Análisis de Clientes de ConnectaTel**

**Descripción del proyecto**

Este proyecto presenta un análisis exploratorio de datos (EDA) sobre la base de clientes de ConnectaTel, una empresa de telecomunicaciones en Latinoamérica.

El objetivo es comprender el comportamiento de los clientes durante el año 2024, identificar patrones de consumo, detectar problemas de calidad en los datos, segmentar a los usuarios según su edad y nivel de uso, y generar recomendaciones de negocio que ayuden a mejorar la oferta de planes y las estrategias de retención.

**Objetivos**
Explorar y comprender la estructura de los datos.
Detectar y corregir problemas de calidad (valores nulos, sentinels y fechas inválidas).
Analizar el comportamiento de uso de llamadas y mensajes.
Identificar valores atípicos (outliers).
Segmentar clientes por edad y nivel de uso.
Generar insights ejecutivos y recomendaciones para la toma de decisiones.

**Datasets utilizados**

El proyecto utiliza tres archivos CSV:

**Dataset**	**Descripción**
plans.csv	Información de los planes disponibles (precio, minutos, mensajes, GB incluidos y costos adicionales).
users_latam.csv	Información de los clientes (edad, ciudad, fecha de registro, plan contratado y fecha de cancelación).
usage.csv	Registro histórico del uso de los servicios (llamadas y mensajes).

 **Etapas del análisis**
 
1. **Carga y exploración de datos**
Importación de librerías.
Carga de los datasets.
Revisión de estructura, dimensiones y tipos de datos.
2. **Evaluación de la calidad de los datos**
Identificación de valores nulos.
Detección de sentinels y valores inválidos.
Conversión y validación de fechas.
3. **Limpieza de datos**
- Reemplazo de valores atípicos.
- Corrección de fechas fuera de rango.
- Tratamiento de valores faltantes.
4. **Construcción del perfil de usuario**
- Cálculo del número de llamadas.
- Cálculo del número de mensajes.
- Total de minutos hablados por usuario.
5. **Análisis exploratorio (EDA)**
- Estadísticas descriptivas.
- Histogramas.
- Boxplots.
- Identificación de outliers.
6. **Segmentación de clientes**
- Clasificación por grupo de edad.
- Clasificación por nivel de uso.
- Análisis cruzado entre ambas variables.
7. **Insights y recomendaciones**
- Identificación de segmentos de mayor valor.
- Análisis de patrones de consumo.
- Recomendaciones para optimizar la oferta de planes y fortalecer la retención de clientes.

**Principales hallazgos**

Los adultos de uso medio y alto representan el segmento más valioso para ConnectaTel debido a su tamaño y nivel de consumo.
La mayoría de los clientes pertenece al segmento de uso medio, lo que representa la principal fuente de ingresos.
Se identificó un pequeño grupo de usuarios con consumos muy superiores al promedio, especialmente en minutos de llamada, lo que sugiere oportunidades para planes premium y programas de fidelización.
Los jóvenes y los adultos mayores de bajo uso representan segmentos con potencial de crecimiento mediante ofertas adaptadas a sus necesidades.

**Tecnologías utilizadas**

* Python 3
* Pandas
* Matplotlib
* Seaborn
* Google Colab Notebook

**¿Cómo ejecutar el proyecto?**

## Ejecución en Google Colab (Recomendado)

Dado que el análisis se desarrolló utilizando **Google Colab Notebook**, esta es la manera más rápida de ejecutarlo sin necesidad de configurar un entorno local:

1. **Abrir el Notebook en Colab:**
   * Ve a [Google Colab](https://colab.research.google.com/github/blancaorozco/analysis-ever-pick/blob/main/S7_Version_Estudiante_Project_ConnectaTel.ipynb).
   

2. **Cargar los Datasets:**
   * Descarga los archivos CSV (`plans.csv`, `users_latam.csv`, `usage.csv`) desde este repositorio a tu computadora.
   * En el panel lateral izquierdo de Google Colab, haz clic en el icono de la **Carpeta** (Archivos).
   * Arrastra y suelta los tres archivos CSV directamente en el almacenamiento temporal de Colab, o usa el botón de subir archivo.

3. **Ejecutar las Celdas:**
   * Dirígete al menú superior y selecciona **Entorno de ejecución** > **Ejecutar todas**.
   * También puedes ir ejecutando celda por celda usando `Shift + Enter`.
**Reproducción del análisis**

Para reproducir los resultados:

