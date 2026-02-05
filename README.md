# 🎓 UNAC Data Analytics: Análisis Académico y de Matriculados

Este proyecto nace de la curiosidad por analizar el rendimiento académico y las tendencias de matriculación en la **Universidad Nacional del Callao (UNAC)**. Aprovechando que la institución publica semestralmente los promedios ponderados para el orden de mérito en las matrículas, este análisis consolida y procesa esa información para ofrecer una visión 360° de la comunidad universitaria.

<img width="1366" height="768" alt="1" src="https://github.com/juanchocce/UNAC-Project/blob/main/unac%203.png" />

## 📌 Contexto del Proyecto

En la UNAC, el acceso a los horarios de matrícula se define por el promedio ponderado: a mayor nota, más temprana es la cita de matrícula. Utilizando esta fuente de datos junto con el padrón anual de alumnos (extraído de registros públicos en PDF), se construyó una base de datos robusta para identificar patrones de éxito académico y deserción.

## 🚀 Capacidades de Análisis

El dashboard permite responder preguntas clave como:
* **Ranking de Excelencia:** Identificación automática de alumnos en el Medio Superior, Tercio, Quinto, Décimo Superior y Primer Puesto por código de ingreso (promoción) o facultad. 🏆
* **Impacto Histórico:** Análisis de cómo eventos externos (como el COVID-19) afectaron la cantidad de alumnos matriculados y el rendimiento promedio. 📉
* **Comparativa de Facultades:** Visualización de qué carreras o facultades mantienen los promedios ponderados más altos o bajos. 🏫
* **Evolución Temporal:** Seguimiento del promedio histórico por semestre de manera global e individual.

## 🛠️ Stack Tecnológico

* **Extracción de Datos:** Procesamiento de archivos PDF y listas de notas públicas para su estructuración.
* **SQL Server:** Motor de base de datos utilizado para el cruce de información entre el padrón de alumnos y las actas de notas. 🗄️
* **Power BI:** Creación de modelos de datos y visualizaciones interactivas. 📊

## 📈 Visualizaciones Clave

El proyecto se divide en tres áreas principales:

1.  **Vista de Matriculados:** Análisis de volumen poblacional por ciclo, facultad y carrera.
2.  **Vista de Notas:** Análisis de promedios, porcentajes de aprobación/desaprobación y tendencias de rendimiento.
3.  **Vista de Alumnos:** Detalle individual con rankings específicos y búsqueda por DNI o código.

## 📂 Estructura del Repositorio

* `/Data_Processing`: Documentación sobre la limpieza y estructuración de los datos originales.
* `/SQL_Queries`: Scripts para la lógica de negocio y cálculo de promedios ponderados.
* `/Dashboard`: Archivo `.pbix` con el modelado y visualizaciones.

## 👤 Autor

**Juan Chocce** - *Ingeniero de Sistemas*
* GitHub: [@juanchocce](https://github.com/juanchocce)
* Proyecto: [UNAC-Project](https://github.com/juanchocce/UNAC-Data-Analytics)
* Linkedin: [Juan Chocce](https://www.linkedin.com/in/juanchocce/)

---
*Nota: Este proyecto utiliza exclusivamente datos de acceso público proporcionados por la universidad con fines académicos y estadísticos.*
