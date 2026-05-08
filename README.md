# MD004_HA_DV - Master en Data Science

## 📚 Descripción

Repositorio de la asignatura **MD004 - Herramientas Avanzadas de Visualización de Datos** del Máster Universitario en Data Science (MUDS) La Salle - URL. Este repositorio contiene notebooks de Jupyter con las resoluciones de tareas y entregables de la asignatura.

## 📋 Nomenclatura de Archivos

Los archivos en este repositorio siguen una nomenclatura específica:

### Notebooks de Tareas
- **S{n}T{m}**: Sesión {n}, Tarea {m}
- **E{n}**: Entregable {n}

**Formato completo**: `S{n}T{m}_{NombreDataset}_{Autor}_{YYYYMMDD}.ipynb`

**Ejemplo**: `S2T3_CancerReg_ChristianR_20260303.ipynb`
- Sesión 2, Tarea 3
- Dataset: Cancer Registry
- Autor: Christian R
- Fecha: 03 de marzo de 2026

## 📁 Estructura del Repositorio

```
md004_ha_dv/
│
├── data/                                           # Datasets utilizados
│   ├── 20221124_DataSalary.csv                    # Datos de salarios
│   ├── 20230119_DatosBoston.csv                   # Datos de Boston
│   ├── 20230119_SerieMacroeconomica_2010.csv      # Serie macroeconómica 2010
│   ├── 20230202 Subject Ecommerce.csv             # Datos de e-commerce (asignatura)
│   ├── 20230202 Subject vs Spam.csv               # Datos de clasificación spam
│   ├── accomodation_nights_booked.csv             # Noches reservadas en alojamientos
│   ├── audio_book_data.csv                        # Datos de audiolibros
│   ├── babies.csv                                 # Datos de bebés
│   ├── cancer_reg.csv                             # Datos de registro de cáncer
│   ├── customer_churn_data.csv                    # Datos de churn telecom india
│   ├── Fichero Golf.csv                           # Datos de pelotas de golf (Par Inc.)
│   ├── indian_city_tiers.csv                      # Clasificación de ciudades indias
│   ├── nba_logreg.csv                             # Datos de jugadores NBA
│   ├── Poison_and_treat.txt                       # Datos de envenenamiento y tratamiento
│   ├── sentiment_dataset.csv                      # Reviews de apps en App Store (polaridad)
│   ├── TratamientoDatos_SerieTitanic.csv          # Dataset Titanic (preprocesado)
│   └── brazilian_ecommerce_dataset/               # Dataset Olist (9 tablas relacionadas)
│       ├── olist_customers_dataset.csv
│       ├── olist_geolocation_dataset.csv
│       ├── olist_order_items_dataset.csv
│       ├── olist_order_payments_dataset.csv
│       ├── olist_order_reviews_dataset.csv
│       ├── olist_orders_dataset.csv
│       ├── olist_products_dataset.csv
│       ├── olist_sellers_dataset.csv
│       ├── product_category_name_translation.csv
│       └── clean/
│           └── geo_distances.csv                  # Distancias Haversine cliente-vendedor (AC08)
│
├── notebooks/                                      # Notebooks de trabajo y tareas
│   ├── S2T3_CancerReg_ChristianR_20260303.ipynb
│   ├── S4T3_SentimentAnalysis_ChristianR_20260404.ipynb
│   ├── S5T3_ChurnAnalysis_ChristianR_20260411.ipynb
│   ├── S6T2_AudioBook_ChristianR_20260416.ipynb
│   ├── S6T3_AccomodationNights_ChristianR_20260427.ipynb
│   ├── AnalisisChurnCompras_5_3.ipynb
│   ├── test_hipotesis.ipynb
│   ├── 3_Matrix_de_Covarianza,_ANOVA_y_Análisis_de_Factores_Ejemplo_Babies.ipynb
│   ├── 3_Matrix_de_Covarianza,_ANOVA_y_Análisis_de_Factores_Ejemplo_Poison.ipynb
│   ├── 3_Matrix_de_Covarianza,_ANOVA_y_Análisis_de_Factores_Ejemplo_Serie_Macroeconómica.ipynb
│   ├── 4_Entropía_Bayes_y_sus_amigos__Ejemplo_NBA.ipynb
│   ├── 4_Entropía_Bayes_y_sus_amigos__Ejemplo_SPAM.ipynb
│   └── 6_Preparación_de_Datos_Ejemplo_Titanic.ipynb
│
├── deliverables/                                   # Entregables finales
│   ├── MD004ChristianRomanMarinAC03.ipynb         # Actividad Continua 03
│   ├── MD004ChristianRomanMarinAC03.html          # Actividad Continua 03 (HTML)
│   ├── MD004ChristianRomanMarinAC06.ipynb         # Actividad Continua 06
│   ├── MD004ChristianRomanMarinAC06.html          # Actividad Continua 06 (HTML)
│   ├── MD004ChristianRomanMarinAC08.ipynb         # Actividad Continua 08 (exploración)
│   └── MD004ChristianRomanMarinAC08.pbix          # Actividad Continua 08 (modelo Power BI)
│
├── figures/                                        # Gráficos y visualizaciones generadas
│
├── submissions/                                    # Archivos enviados a plataforma
│   ├── MD004ChristianRomanMarinAC03.pdf           # AC03 enviado
│   └── MD004ChristianRomanMarinAC08.pdf           # AC08 enviado
│
├── requirements.txt                                # Dependencias del proyecto
└── README.md                                       # Este archivo

```

## 📓 Notebooks

### Tareas y Ejercicios

#### 1. S6T3_AccomodationNights_ChristianR_20260427.ipynb
**Sesión 6 - Tarea 3: Análisis de Noches de Alojamiento**

Análisis sobre el dataset de noches reservadas en alojamientos.

**Dataset**: `accomodation_nights_booked.csv`

---

#### 2. S6T2_AudioBook_ChristianR_20260416.ipynb
**Sesión 6 - Tarea 2: Data Wrangling sobre Datos de Audiolibros**

Ejercicio de limpieza y transformación de datos sobre un dataset de audiolibros. Exploración de técnicas de preprocesamiento y extracción de información desde campos de texto no estructurado.

**Preguntas de investigación:**
1. ¿Cuál es la duración mediana de los audiolibros en minutos?
2. ¿Cuántas valoraciones tiene el audiolibro con más reseñas?
3. ¿Qué autor tiene más audiolibros publicados?
4. ¿Cuál es el narrador más popular?

**Técnicas aplicadas:**
- Parsing y transformación de strings de duración (horas/minutos a minutos)
- Extracción de conteo de valoraciones desde campos de texto
- Normalización de nombres de autores y narradores
- Estadísticas descriptivas post-limpieza
- Visualizaciones con matplotlib y seaborn

**Dataset**: `audio_book_data.csv`

---

#### 3. S5T3_ChurnAnalysis_ChristianR_20260411.ipynb
**Sesión 5 - Tarea 3: Análisis de Churn y Cohort Analysis**

Análisis exhaustivo sobre el comportamiento de clientes y su abandono (churn) mediante análisis de cohortes y análisis de supervivencia (Kaplan-Meier).

**Preguntas de investigación:**
1. ¿Cómo varían las tasas de retención de clientes según el canal de adquisición?
2. ¿Existen diferencias significativas en el comportamiento de cohort de clientes en diferentes períodos?
3. ¿Cuál es la curva de supervivencia de los clientes por línea de productos?
4. ¿Cómo se distribuyen los clientes por canal y línea de productos?
5. ¿Existen patrones en la primera compra de clientes y su posterior retención?

**Técnicas aplicadas:**
- Análisis exploratorio de datos (EDA) de comportamiento clientela
- Análisis de Cohortes: tabla pivot de cohortes por período de primera compra
- Curvas ROT (Repeat Order Time) y análisis de patrones temporales
- Análisis de Supervivencia (Kaplan-Meier Fitter)
- Segmentación por canal de adquisición y línea de productos
- Pruebas estadísticas log-rank para comparación de curvas de supervivencia
- Visualización de curvas de supervivencia Kaplan-Meier
- Análisis de cohort retention rates y customer lifetime patterns
- Identificación de primeras compras por cliente y seguimiento posterior

**Métricas clave:**
- Retention rates por cohorte temporal
- Churn rate por canal de adquisición
- Survival curves por product line
- Repeat purchase behavior
- Customer acquisition patterns

**Dataset**: Datos de transacciones de e-commerce con información de clientes, productos y canales

---

#### 4. S4T3_SentimentAnalysis_ChristianR_20260404.ipynb
**Sesión 4 - Tarea 3: Análisis de Sentimientos - Reviews de App Store**

Análisis de sentimientos sobre reviews de applicaciones en App Store utilizando Naive Bayes con CountVectorizer.

**Preguntas de investigación:**
1. ¿Tienen todas las apps la misma proporción de polaridad en sus reseñas?
2. ¿Qué palabras parecen ser las que generan una mayor polaridad?
3. ¿Cómo de bueno es el modelo generado con este conjunto de datos?
4. ¿Podemos hacer uso de Laplace smoothing para mejorar los resultados?
5. ¿Qué resultados obtenemos en el modelo?, ¿Predice correctamente en todas las apps?

**Técnicas aplicadas:**
- Análisis exploratorio de datos (EDA) por aplicación
- Preprocesamiento de texto (normalización, eliminación de URLs, stopwords)
- CountVectorizer para representación bag-of-words
- Modelo Naive Bayes Multinomial (`MultinomialNB`)
- Importancia de palabras mediante diferencia de log-probabilidades
- Word Cloud de palabras más relevantes para la polaridad
- Laplace Smoothing (`alpha` tuning) para comparación de modelos
- Evaluación con accuracy, matriz de confusión y classification report

**Dataset**: `sentiment_dataset.csv`

---

#### 5. S2T3_CancerReg_ChristianR_20260303.ipynb
**Sesión 2 - Tarea 3: Análisis de Registro de Cáncer**

Análisis estadístico exhaustivo sobre tasas de mortalidad por cáncer en diferentes condados de Estados Unidos.

**Preguntas de investigación:**
1. ¿Qué variables parecen tener un mayor impacto sobre la tasa de mortalidad?
2. ¿Qué variables son las más significativas en un modelo de regresión lineal?
3. ¿Cómo se distribuyen los residuos de la regresión?

**Técnicas aplicadas:**
- Análisis exploratorio de datos (EDA)
- Matriz de correlación de Pearson
- Detección de multicolinealidad mediante VIF (Variance Inflation Factor)
- Regresión Lineal Múltiple (OLS)
- Análisis de residuos
- Feature selection basada en p-values

**Variables clave identificadas:**
- `incidencerate`: Tasa de incidencia (factor dominante)
- `povertypercent`: Porcentaje de pobreza
- `pcths25_over`: Educación secundaria en adultos
- `avganncount`: Media de casos reportados
- `pctunemployed16_over`: Tasa de desempleo

**Dataset**: `cancer_reg.csv`

---

#### 6. test_hipotesis.ipynb
**Test de Hipótesis: Caso Par Inc.**

Estudio de caso sobre el fabricante de equipos de golf Par Inc., que busca introducir una pelota resistente a cortes manteniendo distancias de conducción comparables.

**Objetivo:**
Comparar estadísticamente las distancias de conducción entre:
- Pelotas de golf del modelo actual
- Pelotas con nuevo revestimiento resistente a cortes

**Metodología:**
- Test de hipótesis para comparación de medias
- Análisis con 40 pelotas de cada modelo
- Pruebas realizadas con máquina mecánica para eliminar sesgo
- Cálculo de p-valor
- Estadística descriptiva por modelo

**Dataset**: `Fichero Golf.csv`

---

### Análisis Multivariante y Preparación de Datos

#### 7. 6_Preparación_de_Datos_Ejemplo_Titanic.ipynb
**Sesión 6 - Preparación de Datos: Titanic**

Notebook de referencia (en R) sobre las etapas del pipeline de preparación de datos, usando el dataset del Titanic como caso práctico.

**Técnicas aplicadas:**
- Exploración y resumen de datos
- Creación de nuevas variables (feature engineering)
- Transformación de tipos de datos
- Filtrado de outliers
- Tratamiento de valores missing
- Normalización y estandarización
- Discretización y agrupación de variables

**Dataset**: `TratamientoDatos_SerieTitanic.csv`
**Lenguaje**: R (tidyverse, dplyr, ggplot2)

---

#### 8. AnalisisChurnCompras_5_3.ipynb
**Sesión 5 - Referencia: Análisis de Cohortes y Supervivencia (R)**

Notebook de referencia (en R) sobre análisis de cohortes y análisis de supervivencia para retención de usuarios en aplicaciones móviles.

**Técnicas aplicadas:**
- Construcción de tablas de cohortes diarias y mensuales
- Análisis de tasas de retención por cohorte
- Curvas de retención y transformación shift-left
- Análisis de supervivencia (survival analysis)
- Visualización de cohortes con heatmaps

**Dataset**: `gamelaunch` (paquete survminer de R)
**Lenguaje**: R (tidyverse, cohorts, survival, survminer)

---

#### 9. Matrix de Covarianza, ANOVA y Análisis de Factores - Ejemplo Babies
**Análisis multivariante de datos de bebés**

Estudio de matriz de covarianza, análisis de varianza (ANOVA) y análisis factorial sobre datos relacionados con recién nacidos.

**Técnicas aplicadas:**
- Matriz de covarianza y correlación
- ANOVA (Análisis de Varianza)
- Análisis de Factores
- Pruebas de significancia estadística

**Dataset**: `babies.csv`

---

#### 10. Matrix de Covarianza, ANOVA y Análisis de Factores - Ejemplo Poison
**Análisis de tratamientos contra envenenamiento**

Análisis estadístico multivariante sobre datos de envenenamiento y diferentes tratamientos aplicados.

**Técnicas aplicadas:**
- Matriz de covarianza
- ANOVA multifactorial
- Análisis de efectos principales e interacciones
- Comparaciones post-hoc

**Dataset**: `Poison_and_treat.txt`

---

#### 11. Matrix de Covarianza, ANOVA y Análisis de Factores - Ejemplo Serie Macroeconómica
**Análisis de series macroeconómicas**

Estudio de variación y correlación en variables macroeconómicas a lo largo del tiempo.

**Técnicas aplicadas:**
- Matriz de covarianza temporal
- ANOVA para series temporales
- Análisis de componentes principales
- Análisis factorial

**Dataset**: `20230119_SerieMacroeconomica_2010.csv`

---

### Sesión 4 - Entropía, Bayes y sus amigos

#### 12. 4_Entropía_Bayes_y_sus_amigos__Ejemplo_NBA.ipynb
**Análisis de jugadores NBA con regresión logística y Naive Bayes**

Aplicación de modelos probabilísticos sobre datos de la NBA.

**Técnicas aplicadas:**
- Regresión logística
- Naive Bayes
- Análisis de entropía e información

**Dataset**: `nba_logreg.csv`

---

#### 13. 4_Entropía_Bayes_y_sus_amigos__Ejemplo_SPAM.ipynb
**Clasificación de spam con Naive Bayes**

Modelo de clasificación de correos spam vs ham usando Naive Bayes.

**Técnicas aplicadas:**
- Naive Bayes para clasificación de texto
- Análisis de entropía e información
- Evaluación de clasificadores

**Dataset**: `20230202 Subject vs Spam.csv`

---

### Entregables

#### MD004ChristianRomanMarinAC06 ✅
**Actividad Continua 06 - COMPLETADO Y ENVIADO**

Segundo entregable de la asignatura enviado el 27 de abril de 2026. Análisis completo del ciclo de vida del cliente y predicción de churn en el sector de telecomunicaciones (India).

**Estado**: ✅ Calificación: **9/10**

> 💬 **Feedback del profesor**: Teoría muy bien desarrollada y pasos bien razonados. Se echa de menos en las conclusiones un análisis crítico de los pobres resultados del modelo (F1-score ≈ 0.5 equivale a tirar una moneda) y cómo interpretar el modelo desde esa perspectiva.

**Contenido:**
- Análisis exploratorio exhaustivo (EDA) sobre dataset de telecom con 104.142 clientes
- Análisis de calidad de datos: missing values, distribuciones, outliers
- Visualización de variables numéricas y categóricas
- Análisis de percentiles y asimetría de distribuciones
- Identificación de patrones en métricas de los primeros 7 días post-registro
- Análisis de la variable objetivo `is_churned` y sus relaciones con el resto de features

**Variables clave:**
- `is_churned`: variable objetivo (churn binario)
- `device_brand`, `city`, `age`: perfil demográfico
- `payment_initiated`, `payment_failed`, `payment_completed`: historial de pagos
- `visits_feature_1/2`, `permissions_count`, `referral`: engagement y permisos
- `reward_purchase_count_first_7days`: actividad inicial del cliente

**Dataset**: `customer_churn_data.csv` (104.142 filas × 18 columnas)

**Formatos disponibles:**
- 📓 Notebook Jupyter: `deliverables/MD004ChristianRomanMarinAC06.ipynb`
- 🌐 HTML exportado: `deliverables/MD004ChristianRomanMarinAC06.html`

**Fecha de envío**: 27 de abril de 2026

---

#### MD004ChristianRomanMarinAC03 ✅
**Actividad Continua 03 - COMPLETADO Y ENVIADO**

Primer entregable de la asignatura completado y enviado a plataforma académica.

**Estado**: ✅ Calificación: **10/10**

**Contenido:**
- Análisis estadístico multivariante
- Matriz de covarianza y análisis ANOVA
- Análisis de factores sobre múltiples datasets
- Visualizaciones avanzadas con matplotlib/seaborn
- Modelo de regresión lineal múltiple con interpretación de resultados

**Formatos disponibles:**
- 📓 Notebook Jupyter: `deliverables/MD004ChristianRomanMarinAC03.ipynb`
- 🌐 HTML exportado: `deliverables/MD004ChristianRomanMarinAC03.html`
- 📄 PDF enviado: `submissions/MD004ChristianRomanMarinAC03.pdf`

**Fecha de envío**: 22 de marzo de 2026

---

#### MD004ChristianRomanMarinAC08 🔜
**Actividad Continua 08 - Brazilian Ecommerce: Power BI + Data Storytelling**

Tercer entregable de la asignatura. Construcción de un modelo dimensional en Power BI utilizando el dataset de Olist (Brazilian Ecommerce), con un modelo DAR de 3 páginas y una narrativa de data storytelling.

**Contenido del notebook de exploración:**
- Auditoría de datos: tipos, cardinalidad y rango temporal de las 9 tablas del dataset
- EDA sobre productos: volumen, peso y densidad; detección de outliers
- Test de hipótesis para el storytelling:
  - **H₀**: La distancia entre cliente y vendedor no impacta el incumplimiento del SLA de entrega
  - **H₁**: La distancia sí tiene impacto en el incumplimiento del SLA
  - Cálculo de distancias de Haversine entre cliente y vendedor
  - Variable binaria `SLA_failed` (fecha estimada vs. real)
  - Validación estadística con Chi-cuadrado y Cramer's V (V=0.067): efecto real y sistemático pero no dominante
- Data Cleaning: generación de tabla `geo_distances.csv` con distancias y bins para importación directa a Power BI

**Formatos disponibles:**
- 📓 Notebook Jupyter: `deliverables/MD004ChristianRomanMarinAC08.ipynb`
- 📊 Modelo Power BI: `deliverables/MD004ChristianRomanMarinAC08.pbix`
- 📄 PDF enviado: `submissions/MD004ChristianRomanMarinAC08.pdf`

**Dataset**: Brazilian Ecommerce (Olist) — 9 tablas relacionadas (`data/brazilian_ecommerce_dataset/`)

**Fecha de envío**: 8 de mayo de 2026

---

## 🚀 Instalación y Uso

### Prerrequisitos
- Python 3.8 o superior
- pip (gestor de paquetes de Python)

### Paso 1: Clonar el repositorio
```bash
git clone https://github.com/Chrissroman/md004_ha_dv.git
cd md004_ha_dv
```

### Paso 2: Crear entorno virtual (recomendado)
```bash
python -m venv .venv
source .venv/bin/activate  # En Linux/Mac
# o
.venv\Scripts\activate     # En Windows
```

### Paso 3: Instalar dependencias
```bash
pip install -r requirements.txt
```

### Paso 4: Ejecutar Jupyter Notebook
```bash
jupyter notebook
```

Los notebooks se encuentran en la carpeta `notebooks/` y los entregables finales en `deliverables/`.

## 📦 Dependencias Principales

- **pandas** (3.0.1): Manipulación y análisis de datos
- **numpy** (2.4.2): Operaciones numéricas
- **matplotlib** (3.10.8): Visualizaciones básicas
- **seaborn** (0.13.2): Visualizaciones estadísticas avanzadas
- **statsmodels** (0.14.6): Modelos estadísticos y tests
- **scikit-learn** (1.8.0): Machine Learning y preprocessing

Ver `requirements.txt` para lista completa de dependencias.

## 📊 Datasets

### 1. cancer_reg.csv
Registro de cáncer con información por condado en Estados Unidos.

**Variables principales:**
- Indicadores de salud: tasa de mortalidad, incidencia
- Factores socioeconómicos: ingreso mediano, pobreza
- Demografía: edad, composición étnica
- Educación: niveles educativos por grupos de edad
- Cobertura sanitaria: pública, privada

### 2. Fichero Golf.csv
Datos de pruebas de distancia de pelotas de golf Par Inc.

**Contenido:**
- Distancias de conducción del modelo actual (40 observaciones)
- Distancias de conducción del nuevo modelo (40 observaciones)
- Mediciones realizadas con máquina mecánica

### 3. babies.csv
Dataset de información sobre recién nacidos.

**Uso:**
- Análisis de matriz de covarianza
- ANOVA y análisis de factores
- Estudios de correlación entre variables perinatales

### 4. Poison_and_treat.txt
Datos de envenenamiento y tratamientos aplicados.

**Contenido:**
- Diferentes tipos de veneno
- Tratamientos aplicados
- Resultados y efectividad

### 5. 20230119_SerieMacroeconomica_2010.csv
Serie temporal de variables macroeconómicas desde 2010.

**Uso:**
- Análisis de series temporales
- Matriz de covarianza temporal
- Análisis factorial de variables económicas

### 6. 20230119_DatosBoston.csv
Dataset relacionado con datos de Boston (housing, crimen, etc.).

**Uso:**
- Análisis multivariante
- Regresión y modelado predictivo

### 7. 20221124_DataSalary.csv
Dataset de salarios y compensaciones.

**Uso:**
- Análisis salarial
- Estudios de disparidad y segmentación

### 8. sentiment_dataset.csv
Reviews de aplicaciones de la App Store con su polaridad de sentimiento.

**Variables:**
- `package_name`: Identificador de la aplicación
- `review`: Texto de la reseña del usuario
- `polarity`: Sentimiento (`1` = muy positivo/negativo, `0` = neutro)

**Uso:**
- Análisis de sentimientos (S4T3)
- Clasificación de texto con Naive Bayes

### 9. nba_logreg.csv
Datos estadísticos de jugadores de la NBA.

**Uso:**
- Regresión logística
- Clasificación con Naive Bayes

### 10. 20230202 Subject vs Spam.csv
Dataset de clasificación de correos electrónicos spam/ham.

**Uso:**
- Clasificación de texto con Naive Bayes
- Análisis de entropía

### 11. 20230202 Subject Ecommerce.csv
Datos de e-commerce de la asignatura.

**Uso:**
- Análisis multivariante
- Ejercicios de la asignatura

### 12. customer_churn_data.csv
Datos de clientes de una empresa de telecomunicaciones india.

**Variables principales:**
- `is_churned`: variable objetivo (abandono del cliente)
- `device_brand`, `city`, `age`: perfil demográfico del cliente
- `payment_initiated`, `payment_failed`, `payment_completed`: métricas de pagos
- `visits_feature_1/2`: uso de funcionalidades de la plataforma
- `permissions_count`, `referral`: comportamiento y captación
- `reward_purchase_count_first_7days`: actividad primeros 7 días

**Uso:**
- Análisis de churn y predicción (AC06)
- EDA y análisis de calidad de datos

### 13. audio_book_data.csv
Datos de audiolibros con información de duración, autores, narradores y valoraciones.

**Uso:**
- Ejercicio de data wrangling (S6T2)
- Parsing y transformación de campos de texto

### 14. accomodation_nights_booked.csv
Datos de reservas de noches en alojamientos.

**Uso:**
- Análisis de noches de alojamiento (S6T3)

### 15. TratamientoDatos_SerieTitanic.csv
Dataset del Titanic con información de pasajeros para preprocesamiento de datos.

**Variables principales:**
- `PassengerId`, `Survived` (target), `Pclass`, `Name`, `Age`
- `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`

**Uso:**
- Notebook de referencia de preparación de datos (Sesión 6)

### 16. indian_city_tiers.csv
Clasificación de ciudades indias por nivel/tier.

**Uso:**
- Dato de apoyo para análisis geográfico en contexto indio

### 17. brazilian_ecommerce_dataset/
Dataset de e-commerce brasileño de Olist con 9 tablas relacionadas.

**Tablas:**
- `olist_customers_dataset.csv`: Clientes
- `olist_geolocation_dataset.csv`: Geolocalizaciones por código postal
- `olist_order_items_dataset.csv`: Ítems por pedido
- `olist_order_payments_dataset.csv`: Pagos por pedido
- `olist_order_reviews_dataset.csv`: Reseñas de pedidos
- `olist_orders_dataset.csv`: Pedidos
- `olist_products_dataset.csv`: Productos
- `olist_sellers_dataset.csv`: Vendedores
- `product_category_name_translation.csv`: Traducción de categorías (PT → EN)
- `clean/geo_distances.csv`: Distancias Haversine cliente-vendedor (generada en AC08)

**Uso:**
- Modelo dimensional en Power BI (AC08)
- Data storytelling sobre SLA de entrega y distancia geográfica

## 👤 Autor

**Christian R**
- Estudiante del Master Universitario en Data Science (MUDS) La Salle - URL
- Asignatura: MD004 - Herramientas Avanzadas de Visualización de Datos

## 🚦 Estado del Proyecto

| Entregable | Estado | Fecha Envío | Evaluación |
|------------|--------|-------------|------------|
| AC03 - Actividad Continua 03 | ✅ Enviado | 22/03/2026 | ✅ 10/10 |
| AC06 - Actividad Continua 06 | ✅ Enviado | 27/04/2026 | ✅ 9/10 |
| AC08 - Actividad Continua 08 | ✅ Enviado | 08/05/2026 | ⏳ Pendiente |
| Evaluación Final | 🔜 Próximo | - | - |

## 📅 Historial de Actualizaciones

- **03/03/2026**: S2T3 - Análisis de Cancer Registry completado
- **03/03/2026**: Test de hipótesis Par Inc. implementado
- **04/03/2026**: README.md inicial creado
- **21/03/2026**: Primer entregable AC03 completado y añadido a `deliverables/`
- **21/03/2026**: Notebooks de matriz de covarianza, ANOVA y análisis de factores añadidos
- **21/03/2026**: Reestructuración del repositorio - carpetas `notebooks/`, `deliverables/` y `submissions/` creadas
- **21/03/2026**: README.md actualizado con nueva estructura y datasets adicionales
- **22/03/2026**: 🎯 AC03 exportado a PDF y enviado a plataforma académica
- **22/03/2026**: 🏆 AC03 calificado con **10/10**
- **04/04/2026**: S4T3 - Análisis de Sentimientos (App Store reviews) completado con Naive Bayes y Laplace Smoothing
- **04/04/2026**: Dataset `sentiment_dataset.csv` añadido a `/data/`
- **12/04/2026**: S5T3 - Análisis de Churn con Kaplan-Meier y Cohort Analysis completado
- **16/04/2026**: S6T2 - Data Wrangling sobre datos de audiolibros completado
- **16/04/2026**: Dataset `audio_book_data.csv` añadido a `/data/`
- **27/04/2026**: 🎯 AC06 - Entregable de Churn Telecom completado y enviado a plataforma académica
- **27/04/2026**: Dataset `customer_churn_data.csv` y archivos de soporte añadidos a `/data/`
- **27/04/2026**: S6T3 - Análisis de Noches de Alojamiento completado
- **27/04/2026**: README.md actualizado con AC06, nuevos notebooks y datasets
- **28/04/2026**: 🏆 AC06 calificado con **9/10** — feedback recibido del profesor
- **28/04/2026**: README.md actualizado con nota AC06, feedback del profesor y estado del proyecto
- **08/05/2026**: AC08 - Modelo dimensional Power BI (Brazilian Ecommerce) completado y enviado
- **08/05/2026**: Notebook de exploración y preparación de datos AC08 completado (EDA, hipótesis, geo_distances)
- **08/05/2026**: Dataset `brazilian_ecommerce_dataset/` documentado y tabla `geo_distances.csv` generada
- **08/05/2026**: README.md actualizado con AC08, Power BI y dataset Brazilian Ecommerce

## 📝 Notas

- Los notebooks están completamente documentados con explicaciones en español
- Se incluyen interpretaciones estadísticas y conclusiones
- Los análisis siguen metodología académica rigurosa
- Código reproducible y modular
- **Estructura organizada**: notebooks en `/notebooks/`, datos en `/data/`, entregables en `/deliverables/`, figuras en `/figures/`
- La carpeta `submissions/` contiene archivos enviados oficialmente a plataforma académica
- ✅ AC03 completado, enviado y calificado con **10/10**
- ✅ AC06 completado, enviado y calificado con **9/10** (28/04/2026)
- 💬 Feedback AC06: profundizar en el análisis crítico de métricas del modelo cuando el F1-score es bajo
- ✅ AC08 completado y enviado (08/05/2026) — calificación pendiente

---

**Repositorio**: [github.com/Chrissroman/md004_ha_dv](https://github.com/Chrissroman/md004_ha_dv)

**Licencia**: Uso académico
