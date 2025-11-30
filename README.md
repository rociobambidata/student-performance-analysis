# Student Performance Analysis
Exploración de los factores que influyen en el rendimiento académico de los estudiantes

---

## Descripción
Este proyecto analiza cómo distintos factores personales, académicos y familiares influyen en el rendimiento escolar de los estudiantes.

Utiliza el dataset **Student Performance Factors (Kaggle)** para identificar patrones, evaluar hipótesis y comprender qué variables tienen mayor impacto sobre el puntaje final del examen (*Exam_Score*).

El objetivo es ofrecer información útil para docentes, instituciones educativas y cualquier persona interesada en entender qué elementos favorecen —o dificultan— el éxito académico.

---

## Fuente de datos
Dataset proveniente de Kaggle: **Student Performance Factors**.  
El archivo CSV está incluido en este repositorio dentro de la carpeta **/data**, lo que permite reproducir el análisis sin necesidad de descargas adicionales.

---

## Objetivos del análisis
- Analizar el impacto de hábitos académicos como **horas de estudio** y **asistencia**.  
- Evaluar el rol del **entorno familiar**, incluyendo nivel educativo de los padres e ingresos.  
- Explorar factores personales: horas de sueño, actividad física, motivación, género, dificultades de aprendizaje.  
- Validar hipótesis sobre qué elementos predicen mejor el rendimiento.  
- Presentar visualizaciones claras que permitan interpretar los resultados.

---

## Tecnologías utilizadas
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Google Colab  

---

## Contenido del repositorio
- **/data** → Base de datos utilizada (CSV)  
- **/notebook** → Notebook completo del análisis (.ipynb)  
- **/requirements.txt** → Librerías necesarias para reproducir el proyecto  

---

## Principales hallazgos
- **Horas de estudio y asistencia** son los factores más determinantes en el rendimiento académico. La asistencia presenta la correlación más alta con el *Exam_Score* (0.58).  
- **Los puntajes previos** influyen considerablemente: quienes tuvieron buen desempeño histórico tienden a mantenerlo.  
- **La motivación** muestra una diferencia leve entre grupos, pero no es un predictor fuerte por sí sola.  
- **El nivel educativo de los padres** sí marca una tendencia: a mayor nivel educativo, mayor puntaje promedio.  
- **El acceso a internet** no mostró un impacto significativo.  
- **No existen diferencias importantes entre géneros** en el puntaje del examen.  
- **El tipo de escuela (pública/privada)** tampoco evidenció influencia.  
- **Horas de sueño y actividad física** presentan una relación débil con el rendimiento.

En conjunto, el rendimiento académico se explica principalmente por **hábitos de estudio y participación escolar**, mientras que factores demográficos muestran una influencia menor.

---

## Cómo reproducir el análisis
1. Clonar o descargar este repositorio.  
2. Instalar dependencias:  
   ```bash
   pip install -r requirements.txt
3. Ejecutar el notebook:
/notebook/Student_Performance_Analysis.ipynb
