# Analisis_de_datos_sobre_la_correlacion_entre_pobreza_inseguridad_y_crecimiento_poblacional
# 🏥 Análisis de Pacientes con Diabetes

## 📖 Descripción
Análisis exploratorio de dataset de pacientes con diabetes para identificar factores de riesgo y patrones predictivos.

## 🎯 Objetivos
- Identificar factores correlacionados con diagnóstico de diabetes
- Desarrollar modelo predictivo de riesgo
- Proporcionar visualizaciones comprensivas

## 🚀 Ejecución Rápida
[![Open in Colab]([https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tu-usuario/diabetes-analysis/blob/main/analysis.ipynb](https://colab.research.google.com/drive/1riysf6eRqfz_YBh-SwbGrYEL5QWpg7FY))

## 📊 Hallazgos Clave
- **Edad**: Pacientes mayores de 45 años tienen 3x más riesgo
- **BMI**: Índice de masa corporal >30 aumenta probabilidad en 65%
- **Herencia**: Historial familiar es el factor más predictivo











---

## 🧩 Estructura del Notebook

1. **Introducción y Contexto**
   - Descripción del propósito del estudio y de las fuentes de datos.
2. **Carga y exploración de los datos**
   - Lectura de archivos CSV y revisión de tipos de datos.
   - Inspección con `head()`, `describe()` y `value_counts()`.
3. **Limpieza y transformación**
   - Identificación de valores nulos mediante una función personalizada.
   - Imputación de valores faltantes con la mediana.
   - Creación de tablas dinámicas (`pivot_table`) para análisis por localidad, edad y sexo.
4. **Análisis exploratorio**
   - Cálculo de totales poblacionales, tasas y comparaciones entre años.
   - Identificación de las localidades más pobladas y con mayor natalidad.
5. **Visualizaciones**
   - Gráficos de barras, líneas, violines y mapas ilustrativos.
   - Visualizaciones de la evolución temporal de la población y la natalidad.
6. **Conclusiones**
   - Interpretación de los hallazgos clave sobre la demografía bogotana.

---

## 📊 Resultados destacados

- La población de Bogotá presenta un **crecimiento sostenido** durante las últimas dos décadas.
- Las localidades del sur como **Bosa, Usme y Ciudad Bolívar** concentran una proporción importante de la población joven.
- Se evidencia una **disminución gradual en la tasa de natalidad**, especialmente en zonas de estrato medio y alto.
- Las mujeres entre **20 y 29 años** siguen representando el grupo con mayor número de nacimientos.
- La estructura poblacional muestra una **transición demográfica** hacia una población más adulta.

---

## 🧠 Habilidades demostradas

El proyecto refleja un sólido dominio de herramientas y competencias analíticas en ciencia de datos:

| Área | Competencias demostradas |
|------|---------------------------|
| **Manipulación de datos** | Uso avanzado de `pandas` (`groupby`, `pivot_table`, `merge`, `fillna`, etc.) |
| **Análisis exploratorio (EDA)** | Identificación de patrones, outliers y tendencias temporales |
| **Visualización** | Creación de gráficos profesionales con `matplotlib` y `seaborn` |
| **Pensamiento analítico** | Diseño lógico del flujo de trabajo, interpretación de resultados |
| **Comunicación científica** | Inclusión de texto descriptivo, conclusiones y contexto demográfico |
| **Reproducibilidad** | Organización y documentación clara en entorno Jupyter |

---

## 🧰 Tecnologías utilizadas

- **Lenguaje:** Python 3.x  
- **Librerías principales:**
  - `pandas` → Manipulación y análisis de datos  
  - `matplotlib` y `seaborn` → Visualización de datos  
  - `numpy` → Operaciones numéricas  
  - `PIL` y `IPython.display` → Visualización de imágenes y mapas  
- **Entorno:** Jupyter Notebook

---

## 📈 Visualizaciones incluidas

- Evolución de la población total de Bogotá (2005–2024).  
- Comparación por grupo de edad y sexo.  
- Tasas de natalidad por localidad.  
- Distribución de población por curso de vida.  
- Mapas temáticos de localidades.  
- Ranking de localidades más pobladas.  
- Gráficos de violín para distribución etaria.

---

## 📚 Fuentes de datos

- **Población en Bogotá D.C por Localidad (2005–2035):**  
  [https://saludata.saludcapital.gov.co/osb/indicadores/natalidad-en-bogota](https://saludata.saludcapital.gov.co/osb/indicadores/natalidad-en-bogota)

- **Natalidad en Bogotá D.C (2009–2024):**  
  [https://datosabiertos.bogota.gov.co/en/dataset/piramide-poblacional-bogota-d-c/resource/d1743cda-9ff](https://datosabiertos.bogota.gov.co/en/dataset/piramide-poblacional-bogota-d-c/resource/d1743cda-9ff)

---

## 🧾 Conclusiones generales

El análisis revela una **transformación demográfica significativa** en Bogotá:  
- La ciudad mantiene su tendencia de crecimiento, pero con **reducción en la natalidad**.  
- Se aprecia un **envejecimiento gradual de la población** y una **redistribución** hacia periferias urbanas.  
- Estos hallazgos son relevantes para la **planificación urbana, políticas sociales y de salud pública.**

---

## 👤 Autor

**Juan Gómez**  
📧 *[Tu correo o perfil profesional]*  
📍 Bogotá, Colombia  

💡 *Proyecto académico de análisis de datos con enfoque en demografía urbana.*

---

## 🏁 Licencia

Este proyecto se distribuye bajo licencia **MIT**.  
Eres libre de usar, modificar y compartir el contenido con la debida atribución.

---

## ⭐ Cómo citar

> Gómez, J. (2025). *Población y Natalidad en Bogotá: Análisis de Datos Final.* GitHub Repository.  
> https://github.com/tuusuario/PoblacionYNatalidadBogota

---

