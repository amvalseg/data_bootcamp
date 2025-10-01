# Data Bootcamp - Python, NumPy, Pandas & EDA

Bootcamp completo de análisis de datos con Python, desde los fundamentos del lenguaje hasta análisis exploratorio de datos (EDA) con visualizaciones.

## 📚 Contenido del Curso

### 1. **Iniciación a Python**

- Variables y tipos de datos (`int`, `float`, `str`, `bool`, `list`, `dict`)
- Operaciones con strings y métodos
- Estructuras de datos (listas, sets, tuplas, diccionarios)
- Control de flujo (`if`, `elif`, `else`, `for`, `while`)
- Funciones y lambdas
- Manejo de errores (try-except)
- Operaciones con archivos (CSV, JSON)

### 2. **NumPy & Pandas**

- Introducción a NumPy y arrays multidimensionales
- Fundamentos de Pandas (DataFrames y Series)
- Manipulación y transformación de datos
- Filtrado, agrupación y agregación
- Ejercicios prácticos con datasets reales (Uber, migraciones)

### 3. **Análisis Exploratorio de Datos (EDA)**

- Exploración visual de datos
- Gráficos y visualizaciones
- Análisis de patrones y tendencias
- Proyecto guiado con datos de migración

### 4. **VS Code Shortcuts & Productividad**

- Atajos esenciales de teclado
- Navegación y edición de código
- Uso del terminal integrado
- Operaciones con Jupyter notebooks
- Herramientas de debugging

## 🎯 Objetivos de Aprendizaje

- Dominar la sintaxis y lógica básica de Python
- Desarrollar habilidades de programación práctica
- Fomentar el pensamiento lógico y analítico
- Aprender mejores prácticas de codificación
- Dominar técnicas de manipulación de datos con Pandas y NumPy
- Realizar análisis exploratorio de datos (EDA) completo
- Crear visualizaciones efectivas para análisis de datos
- Construir aplicaciones con datos del mundo real

## 📋 Estructura del Repositorio

```
.
├── README.md
├── VSC_shortcuts.ipynb                    # Atajos de VS Code
├── iniciacion_python/                     # Módulo 1: Fundamentos de Python
│   ├── Iniciacion_python.ipynb           # Teoría y ejemplos
│   ├── Ejercicios_python.ipynb           # Ejercicios prácticos
│   ├── Ejercicios_python_soluciones.ipynb # Soluciones
│   └── img/
├── numpy_pandas/                          # Módulo 2: NumPy & Pandas
│   ├── ubernumpypandas.ipynb             # Tutorial completo NumPy/Pandas
│   ├── pandas_uber_exercises.ipynb        # Ejercicios con datos de Uber
│   ├── pandas_uber_exercises_solutions.ipynb
│   ├── pandas_migration_exercises.ipynb   # Ejercicios con datos de migración
│   ├── teoría/
│   │   └── Pandas/
│   │       └── Introducción_a_Pandas.ipynb
│   └── data/
│       ├── ncr_ride_bookings.csv          # Dataset de viajes Uber
│       └── DTM_Mixed Migration Flows to Europe_Yearly_2024_1.xlsx
└── EDA/                                   # Módulo 3: Análisis Exploratorio
    ├── proyecto_guiado.ipynb              # Proyecto guiado de EDA
    ├── eda_visual_migration.ipynb         # EDA visual con datos de migración
    └── data/
        ├── DTM_Mixed Migration Flows to Europe_Yearly_2023_1.xlsx
        └── DTM_Mixed Migration Flows to Europe_Yearly_2024_1.xlsx
```

## ✨ Comenzando

### Instalación

1. Clona este repositorio

   ```bash
   git clone <repository-url>
   cd data_bootcamp
   ```

2. Crea un entorno virtual (recomendado)

   ```bash
   python -m venv .venv
   # Windows
   .venv\Scripts\activate
   # Linux/Mac
   source .venv/bin/activate
   ```

3. Instala las dependencias
   ```bash
   pip install numpy pandas matplotlib jupyter openpyxl
   ```

### Ruta de Aprendizaje

**Módulo 1: Iniciación a Python**

1. Revisa [VSC_shortcuts.ipynb](VSC_shortcuts.ipynb) para atajos útiles de VS Code
2. Estudia la teoría en [iniciacion_python/Iniciacion_python.ipynb](iniciacion_python/Iniciacion_python.ipynb)
3. Practica con [iniciacion_python/Ejercicios_python.ipynb](iniciacion_python/Ejercicios_python.ipynb)
4. Verifica soluciones en [iniciacion_python/Ejercicios_python_soluciones.ipynb](iniciacion_python/Ejercicios_python_soluciones.ipynb)

**Módulo 2: NumPy & Pandas**

1. Comienza con [numpy_pandas/ubernumpypandas.ipynb](numpy_pandas/ubernumpypandas.ipynb)
2. Profundiza en [numpy_pandas/teoría/Pandas/Introducción_a_Pandas.ipynb](numpy_pandas/teoría/Pandas/Introducción_a_Pandas.ipynb)
3. Practica con ejercicios de Uber y migración
4. Revisa las soluciones proporcionadas

**Módulo 3: EDA**

1. Sigue el [EDA/proyecto_guiado.ipynb](EDA/proyecto_guiado.ipynb)
2. Explora [EDA/eda_visual_migration.ipynb](EDA/eda_visual_migration.ipynb)
3. Aplica lo aprendido a tus propios datasets

## 🎓 Prerequisitos

- Conocimientos básicos de programación (recomendado pero no obligatorio)
- Python 3.8 o superior instalado
- Jupyter Notebook o VS Code con extensión de Jupyter
- Git (opcional)

## 💡 Características Principales

- **Notebooks interactivos** con Jupyter para aprendizaje práctico
- **Ejemplos del mundo real** con datasets de Uber y flujos migratorios
- **Ejercicios progresivos** desde básico hasta avanzado
- **Soluciones completas** para todos los ejercicios
- **Proyectos guiados** de análisis exploratorio de datos
- **Visualizaciones** con matplotlib y otras bibliotecas
- **Documentación clara** con explicaciones paso a paso

## 🛠️ Paquetes Necesarios

```python
numpy>=1.20.0
pandas>=1.3.0
matplotlib>=3.4.0
jupyter>=1.0.0
openpyxl>=3.0.0  # Para leer archivos Excel
seaborn>=0.11.0  # Para visualizaciones avanzadas (opcional)
```

## 📊 Datasets Incluidos

- **ncr_ride_bookings.csv** (~25 MB): Dataset de reservas de viajes de Uber
- **DTM_Mixed Migration Flows to Europe** (2023-2024): Datos de flujos migratorios hacia Europa de la Organización Internacional para las Migraciones (OIM)

## 🚀 Proyectos y Casos de Uso

Este bootcamp te prepara para:

- Análisis de datos de transporte y movilidad
- Visualización de tendencias migratorias
- Procesamiento y limpieza de datos
- Creación de dashboards y reportes
- Análisis exploratorio de datasets complejos

## 📝 Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo LICENSE para más detalles.

## 👥 Contribuciones

¡Las contribuciones son bienvenidas! Si encuentras errores o tienes sugerencias:

1. Abre un issue describiendo el problema o mejora
2. Haz un fork del repositorio
3. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
4. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
5. Push a la rama (`git push origin feature/AmazingFeature`)
6. Abre un Pull Request

## 📫 Contacto

Para preguntas, sugerencias o feedback, por favor abre un issue en el repositorio.

---

**Happy Learning! 🎉📊🐍**
