# A/B Testing – Landing Page Conversion Analysis

## 📌 Descripción del proyecto
Este proyecto analiza un experimento A/B realizado sobre una landing page de e-commerce, con el objetivo de determinar qué versión (A o B) genera una mejor tasa de conversión y mayor gasto promedio por usuario.

El análisis combina exploración de datos, pruebas estadísticas y una interpretación orientada a la toma de decisiones de negocio.

---

## 🎯 Objetivos
- Comparar la tasa de conversión entre las páginas A y B.
- Evaluar diferencias en el gasto promedio de usuarios convertidos.
- Analizar el impacto de la fuente de tráfico en la conversión.
- Verificar si existen diferencias según el tipo de usuario (Nuevo vs Recurrente).
- Traducir los resultados en recomendaciones accionables.

---

## 🧪 Metodología
- Análisis exploratorio de datos (EDA).
- Pruebas estadísticas:
  - Z-test para proporciones
  - Chi-cuadrado de independencia
  - Intervalos de confianza al 95%
  - Cramér’s V para tamaño del efecto
- Segmentación por:
  - Versión de landing page
  - Fuente de tráfico
  - Tipo de usuario

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

## 📂 Dataset
El dataset contiene información de usuarios expuestos al experimento A/B, incluyendo:
- versión de landing page
- fuente de tráfico
- tipo de usuario
- estado de conversión
- gasto asociado a usuarios convertidos

---

## 👩‍💻 Autora
**Dayana Rodriguez**  
Analista de Datos  
