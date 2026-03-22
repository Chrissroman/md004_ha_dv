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
├── data/                                       # Datasets utilizados
│   ├── 20221124_DataSalary.csv                # Datos de salarios
│   ├── 20230119_DatosBoston.csv               # Datos de Boston
│   ├── 20230119_SerieMacroeconomica_2010.csv  # Serie macroeconómica 2010
│   ├── babies.csv                             # Datos de bebés
│   ├── cancer_reg.csv                         # Datos de registro de cáncer
│   ├── Fichero Golf.csv                       # Datos de pelotas de golf (Par Inc.)
│   └── Poison_and_treat.txt                   # Datos de envenenamiento y tratamiento
│
├── notebooks/                                  # Notebooks de trabajo y tareas
│   ├── S2T3_CancerReg_ChristianR_20260303.ipynb
│   ├── test_hipotesis.ipynb
│   ├── 3_Matrix_de_Covarianza,_ANOVA_y_Análisis_de_Factores_Ejemplo_Babies.ipynb
│   ├── 3_Matrix_de_Covarianza,_ANOVA_y_Análisis_de_Factores_Ejemplo_Poison.ipynb
│   └── 3_Matrix_de_Covarianza,_ANOVA_y_Análisis_de_Factores_Ejemplo_Serie_Macroeconómica.ipynb
│
├── deliverables/                               # Entregables finales
│   ├── MD004ChristianRomanMarinAC03.ipynb     # Actividad Continua 03
│   └── MD004ChristianRomanMarinAC03.html      # Actividad Continua 03 (HTML)
│
├── submissions/                                # Archivos enviados a plataforma
│   └── MD004ChristianRomanMarinAC03.pdf       # AC03 enviado (en evaluación)
│
├── requirements.txt                            # Dependencias del proyecto
└── README.md                                   # Este archivo

```

## 📓 Notebooks

### Tareas y Ejercicios

#### 1. S2T3_CancerReg_ChristianR_20260303.ipynb
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

#### 2. test_hipotesis.ipynb
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

### Análisis Multivariante

#### 3. Matrix de Covarianza, ANOVA y Análisis de Factores - Ejemplo Babies
**Análisis multivariante de datos de bebés**

Estudio de matriz de covarianza, análisis de varianza (ANOVA) y análisis factorial sobre datos relacionados con recién nacidos.

**Técnicas aplicadas:**
- Matriz de covarianza y correlación
- ANOVA (Análisis de Varianza)
- Análisis de Factores
- Pruebas de significancia estadística

**Dataset**: `babies.csv`

---

#### 4. Matrix de Covarianza, ANOVA y Análisis de Factores - Ejemplo Poison
**Análisis de tratamientos contra envenenamiento**

Análisis estadístico multivariante sobre datos de envenenamiento y diferentes tratamientos aplicados.

**Técnicas aplicadas:**
- Matriz de covarianza
- ANOVA multifactorial
- Análisis de efectos principales e interacciones
- Comparaciones post-hoc

**Dataset**: `Poison_and_treat.txt`

---

#### 5. Matrix de Covarianza, ANOVA y Análisis de Factores - Ejemplo Serie Macroeconómica
**Análisis de series macroeconómicas**

Estudio de variación y correlación en variables macroeconómicas a lo largo del tiempo.

**Técnicas aplicadas:**
- Matriz de covarianza temporal
- ANOVA para series temporales
- Análisis de componentes principales
- Análisis factorial

**Dataset**: `20230119_SerieMacroeconomica_2010.csv`

---

### Entregables

#### MD004ChristianRomanMarinAC03 ✅
**Actividad Continua 03 - COMPLETADO Y ENVIADO**

Primer entregable de la asignatura completado y enviado a plataforma académica.

**Estado**: 📋 En evaluación

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

## 👤 Autor

**Christian R**
- Estudiante del Master Universitario en Data Science (MUDS) La Salle - URL
- Asignatura: MD004 - Herramientas Avanzadas de Visualización de Datos

## � Estado del Proyecto

| Entregable | Estado | Fecha Envío | Evaluación |
|------------|--------|-------------|------------|
| AC03 - Actividad Continua 03 | ✅ Enviado | 22/03/2026 | ⏳ Pendiente |
| Evaluación Final | 🔜 Próximo | - | - |

## 📅 Historial de Actualizaciones

- **03/03/2026**: S2T3 - Análisis de Cancer Registry completado
- **03/03/2026**: Test de hipótesis Par Inc. implementado
- **04/03/2026**: README.md inicial creado
- **21/03/2026**: Notebooks de matriz de covarianza, ANOVA y análisis de factores añadidos
- **21/03/2026**: Reestructuración del repositorio - carpetas `notebooks/`, `deliverables/` y `submissions/` creadas
- **21/03/2026**: Primer entregable AC03 completado y añadido a `deliverables/`
- **21/03/2026**: README.md actualizado con nueva estructura y datasets adicionales
- **22/03/2026**: 🎯 AC03 exportado a PDF y enviado a plataforma académica - A la espera de evaluación

## 📝 Notas

- Los notebooks están completamente documentados con explicaciones en español
- Se incluyen interpretaciones estadísticas y conclusiones
- Los análisis siguen metodología académica rigurosa
- Código reproducible y modular
- **Estructura organizada**: notebooks en `/notebooks/`, datos en `/data/`, entregables en `/deliverables/`
- La carpeta `submissions/` contiene archivos enviados oficialmente a plataforma académica
- ✅ Primer entregable (AC03) completado y enviado - en proceso de evaluación

---

**Repositorio**: [github.com/Chrissroman/md004_ha_dv](https://github.com/Chrissroman/md004_ha_dv)

**Licencia**: Uso académico
