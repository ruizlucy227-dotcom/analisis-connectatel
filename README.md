# Análisis de una Empresa de Telecomunicaciones (ConnectaTel)

## Descripción del proyecto

Este proyecto tiene como objetivo analizar los datos de clientes de una empresa de telecomunicaciones para comprender sus patrones de uso, identificar problemas de calidad en los datos y generar perfiles de usuarios que permitan obtener información útil para la toma de decisiones de negocio.

A través de técnicas de limpieza, exploración y análisis de datos, se busca identificar características relevantes de los clientes, segmentarlos según su comportamiento y proponer recomendaciones basadas en la evidencia obtenida.

---

## Datasets utilizados

### users_latam.csv
Contiene información demográfica y de registro de los clientes:

- `user_id`: identificador único del usuario.
- `age`: edad del cliente.
- `city`: ciudad de residencia.
- `plan`: plan contratado.
- `reg_date`: fecha de registro.

### usage.csv
Contiene el historial de uso de los servicios de telecomunicaciones:

- `user_id`: identificador del usuario.
- `date`: fecha de la actividad.
- `type`: tipo de actividad (llamada o mensaje).
- `duration`: duración de llamadas.
- `length`: longitud del mensaje.

### plans.csv
Contiene información sobre los planes disponibles para los clientes.

---

## Etapas del análisis

### 1. Exploración inicial de los datos
- Carga de archivos CSV.
- Revisión de dimensiones y estructura.
- Análisis de tipos de datos.

### 2. Limpieza de datos
- Identificación de valores nulos.
- Detección de valores inválidos o centinela.
- Conversión y validación de fechas.
- Corrección de inconsistencias.

### 3. Análisis exploratorio
- Estadísticas descriptivas.
- Distribuciones de variables numéricas.
- Comparación entre grupos de usuarios.
- Identificación de valores atípicos.

### 4. Ingeniería de características
- Agregación de métricas de uso por cliente.
- Creación de segmentos de usuarios.
- Clasificación por grupos de edad y nivel de actividad.

### 5. Visualización de datos
- Histogramas.
- Diagramas de caja (boxplots).
- Gráficos de distribución y segmentación.

### 6. Conclusiones y recomendaciones
- Hallazgos principales.
- Implicaciones para el negocio.
- Recomendaciones basadas en los resultados obtenidos.

---

## Cómo ejecutar el notebook

### Opción 1: Google Colab

1. Descarga el archivo `.ipynb` del repositorio.
2. Accede a Google Colab:
   https://colab.research.google.com
3. Selecciona **Archivo → Subir notebook**.
4. Carga el notebook del proyecto.
5. Sube los archivos CSV necesarios.
6. Ejecuta las celdas en orden.

### Opción 2: Jupyter Notebook

Instala las dependencias necesarias:

```bash
pip install pandas numpy matplotlib seaborn
```

Inicia Jupyter Notebook:

```bash
jupyter notebook
```

Abre el archivo `.ipynb` y ejecuta las celdas secuencialmente.

---

## Guía rápida de reproducción

1. Clonar el repositorio:

```bash
git clone https://github.com/tu_usuario/analisis-connectatel.git
```

2. Acceder al directorio del proyecto:

```bash
cd analisis-connectatel
```

3. Colocar los archivos:
   - `users_latam.csv`
   - `usage.csv`
   - `plans.csv`

4. Abrir el notebook en Google Colab o Jupyter Notebook.

5. Ejecutar todas las celdas en orden para reproducir el análisis completo.

---

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## Autor

Proyecto desarrollado como parte del programa de Análisis de Datos de TripleTen.
