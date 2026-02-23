# A/B Testing – Landing Page Conversion Analysis

## 📌 Descripción del proyecto
Este proyecto analiza un experimento A/B aplicado a una landing page de e-commerce con el objetivo de identificar qué versión (A o B) genera una mayor tasa de conversión y un mejor desempeño en términos de gasto promedio por usuario convertido.

El análisis combina exploración de datos, pruebas estadísticas inferenciales y una interpretación orientada a la toma de decisiones de negocio basadas en evidencia.

---

## 🎯 Objetivos
- Comparar la tasa de conversión entre las páginas A y B.
- Evaluar diferencias en el gasto promedio de los usuarios convertidos.
- Analizar la relación entre la fuente de tráfico y la conversión.
- Verificar si existen diferencias de comportamiento según el tipo de usuario (Nuevo vs. Recurrente).
- Traducir los resultados estadísticos en recomendaciones accionables para el negocio.
---

## 📂 Dataset
El análisis se realizó sobre un dataset provisto por la plataforma del bootcamp.  
Por lineamientos del ejercicio, el archivo CSV no se incluye en este repositorio.

Columnas principales:
- user_id: identificador único del usuario
- landing: versión de la página (A / B)
- converted: indicador de conversión (0 = no convierte, 1 = convierte)
- date: fecha de interacción

## 🧪 Metodología
- Análisis exploratorio de datos (EDA) para validar balance de usuarios.
- Cálculo de tasas de conversión por versión.
- Aplicación de Z-test para comparar proporciones.
- Validación adicional mediante prueba Chi-cuadrado.
- Interpretación de resultados desde una perspectiva de negocio.

---

## 📊 Principales hallazgos
- La **Página B** presenta una tasa de conversión significativamente superior a la Página A.
- La diferencia es estadísticamente significativa (p < 0.001).
- La Página B genera aproximadamente **33 conversiones adicionales por cada 1.000 usuarios**.
- No se detectan diferencias relevantes en conversión según tipo de usuario.
- Las tasas de conversión por canal de tráfico son similares, con diferencias de efecto despreciables.

---

## 💡 Recomendaciones de negocio
- Implementar la **Página B** como versión definitiva de la landing.
- Priorizar la optimización del tráfico orgánico por su alto impacto en volumen.
- Evitar segmentar estrategias de conversión por tipo de usuario, ya que no presenta diferencias significativas.
- Continuar realizando experimentos A/B antes de aplicar cambios estructurales en el funnel.

---

## 🛠️ Tecnologías utilizadas
- Python
- Pandas
- NumPy
- SciPy
- Statsmodels
- Matplotlib / Seaborn

---

## 📎 **Notebook ejecutable en Google Colab:**  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/DayaRodriguezM/ab-testing-landing-page-conversion/blob/main/Proyecto_Landing_Experiment.ipynb)
---

## 👩‍💻 Autora
**Dayana Rodriguez**  
Analista de Datos  
