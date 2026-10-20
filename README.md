# ConnectaTel Customer Analytics – Sprint 7

Este repositorio contiene el análisis realizado durante el Sprint 7 del caso **ConnectaTel Customer Analytics**.

El dataset `connectatel_customers` incluye información de clientes, planes contratados, consumo de llamadas y mensajes, así como registros de cancelación del servicio. Los datos presentan valores faltantes, valores centinela, inconsistencias y posibles outliers diseñados para simular escenarios reales de negocio en la industria de telecomunicaciones.

## 📂 Contenido del repositorio

- `notebooks/connectatel_analysis.ipynb`  
  → Notebook principal con limpieza de datos, análisis exploratorio (EDA), detección de outliers, segmentación de clientes e insights de negocio.


## Cómo reproducir el análisis

1. Abre `notebooks/connectatel_analysis.ipynb`.
2. Ejecuta las celdas en orden.
3. El notebook carga automáticamente el dataset desde la carpeta `/data/` o desde el origen configurado en el proyecto.

## Objetivo del análisis

- Identificar problemas de calidad de datos.
- Limpiar y transformar los datos mediante un proceso reproducible.
- Analizar patrones de uso de llamadas y mensajes.
- Detectar y evaluar valores atípicos mediante el método IQR.
- Segmentar clientes según edad y nivel de uso.
- Generar insights accionables para apoyar la toma de decisiones comerciales y de retención.

## Principales hallazgos

- Se identificaron valores faltantes y registros con valores centinela que requirieron tratamiento previo al análisis.
- Los valores extremos observados en variables de consumo corresponden principalmente a comportamientos reales de clientes intensivos y no a errores de captura.
- La mayor concentración de usuarios pertenece al segmento de **uso medio**, representando aproximadamente el 73.6% de la base analizada.
- La segmentación por nivel de uso resultó más informativa que la segmentación por edad para comprender el comportamiento de los clientes.
- Los resultados sugieren oportunidades para estrategias de fidelización, retención y optimización de planes comerciales.

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Colab

## Autor

**Sofía Corzo**  
Analista de Datos | Data Analytics Portfolio

---

Este proyecto fue desarrollado con fines académicos y forma parte de mi portafolio de análisis de datos, demostrando habilidades en limpieza de datos, análisis exploratorio, detección de outliers, segmentación de clientes y comunicación de hallazgos para negocio
.
