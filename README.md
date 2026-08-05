# Proyecto: Análisis Exploratorio de Clientes de ConnectaTel

## Objetivo del proyecto

El objetivo de este proyecto es realizar un Análisis Exploratorio de Datos (EDA) sobre la información de los clientes de ConnectaTel para comprender sus patrones de uso del servicio, identificar posibles problemas en los datos, detectar valores atípicos (outliers) y segmentar a los clientes según su edad y nivel de uso. Finalmente, se generan recomendaciones que apoyen la toma de decisiones del negocio.

## Datasets utilizados

El proyecto utiliza los siguientes conjuntos de datos:

- **users.csv:** Información demográfica de los clientes (edad, plan, ciudad, entre otros).
- **calls.csv:** Registro de llamadas realizadas por los usuarios.
- **messages.csv:** Registro de mensajes enviados.
- **internet.csv:** Consumo de datos móviles por usuario.
Durante el análisis, estos archivos se integran en un único DataFrame llamado **user_profile**, el cual contiene tanto la información del cliente como las métricas agregadas de uso.
## Etapas del análisis

El proyecto se desarrolló siguiendo las siguientes etapas:

1. Importación de librerías.
2. Carga de los datasets.
3. Exploración inicial de los datos.
4. Limpieza de datos.
   - Identificación de valores faltantes.
   - Verificación de tipos de datos.
   - Tratamiento de inconsistencias.
5. Análisis Exploratorio de Datos (EDA).
   - Estadísticas descriptivas.
   - Histogramas.
   - Boxplots.
   - Identificación de outliers mediante el método IQR.
6. Segmentación de clientes.
   - Segmentación por nivel de uso.
   - Segmentación por grupo de edad.
7. Visualización de resultados.
8. Elaboración de insights y recomendaciones para el negocio.

## Herramientas utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Cómo ejecutar el notebook

### Opción 1: Google Colab

1. Abrir Google Colab.
2. Seleccionar **Archivo → Subir notebook**.
3. Cargar el archivo `.ipynb`.
4. Subir los datasets necesarios.
5. Ejecutar las celdas en orden desde la primera hasta la última.

## Guía de reproducción

Para reproducir el análisis:

1. Descargue los datasets del proyecto.
2. Colóquelos en la carpeta de trabajo o actualice las rutas de lectura.
3. Abra el notebook en Google Colab o Jupyter Notebook.
4. Ejecute todas las celdas en orden.
5. Revise las visualizaciones, estadísticas, segmentaciones e insights obtenidos.

## Resultados principales

- Se identificaron y revisaron valores faltantes y valores atípicos.
- Se analizaron los patrones de uso mediante histogramas y boxplots.
- Los clientes fueron segmentados por edad y nivel de uso.
- Se identificó que el segmento de **Uso medio** representa la mayor parte de la base de clientes.
- Se propusieron recomendaciones para optimizar la oferta de planes de ConnectaTel.

  ## Autor

**Juan Arango**
