# MD004_HA_DV - Master en Data Science

## 📚 Descripción

Repositorio de la asignatura **MD004 - Herramientas Avanzadas de Visualización de Datos** del Máster Universitario en Data Science (MUDS). Este repositorio contiene notebooks de Jupyter con las resoluciones de tareas y entregables de la asignatura.

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
├── data/                           # Datasets utilizados
│   ├── cancer_reg.csv             # Datos de registro de cáncer
│   ├── 20221124_DataSalary.csv    # Datos de salarios
│   └── Fichero Golf.csv           # Datos de pelotas de golf (Par Inc.)
│
├── S2T3_CancerReg_ChristianR_20260303.ipynb    # Sesión 2, Tarea 3
├── test_hipotesis.ipynb                        # Test de hipótesis (Par Inc.)
├── requirements.txt                            # Dependencias del proyecto
└── README.md                                   # Este archivo

```

## 📓 Notebooks

### 1. S2T3_CancerReg_ChristianR_20260303.ipynb
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

### 2. test_hipotesis.ipynb
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

### 3. 20221124_DataSalary.csv
Dataset de salarios (a utilizar en futuras tareas).

## 👤 Autor

**Christian R**
- Estudiante del Master Universitario en Data Science (MUDS)
- Asignatura: MD004 - Herramientas Avanzadas de Visualización de Datos

## 📅 Historial de Actualizaciones

- **03/03/2026**: S2T3 - Análisis de Cancer Registry completado
- **03/03/2026**: Test de hipótesis Par Inc. implementado
- **04/03/2026**: README.md creado

## 📝 Notas

- Los notebooks están completamente documentados con explicaciones en español
- Se incluyen interpretaciones estadísticas y conclusiones
- Los análisis siguen metodología académica rigurosa
- Código reproducible y modular

---

**Repositorio**: [github.com/Chrissroman/md004_ha_dv](https://github.com/Chrissroman/md004_ha_dv)

**Licencia**: Uso académico
