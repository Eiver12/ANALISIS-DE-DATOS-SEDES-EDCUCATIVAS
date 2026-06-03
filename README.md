# Sistema de Análisis y Priorización de Sedes Educativas

## Descripción

Herramienta desarrollada en Python para analizar la información recopilada mediante encuestas de caracterización de infraestructura educativa. El sistema procesa los datos, asigna puntajes a diferentes criterios de evaluación y genera un ranking que permite identificar y priorizar las **33 sedes educativas con mayores necesidades de intervención**.

Este proyecto busca apoyar la toma de decisiones mediante un enfoque basado en datos, facilitando la planificación de diagnósticos técnicos y futuras inversiones en infraestructura educativa.

---

## Objetivos

- Procesar los datos de las encuestas de caracterización.
- Aplicar criterios de evaluación y ponderación.
- Calcular un puntaje de priorización para cada sede educativa.
- Generar indicadores y visualizaciones para el análisis.
- Identificar las 33 sedes con mayor prioridad de atención.

---

## Estructura del Proyecto

```text
AD_SEDES_EDUCATIVAS/
│
├── datos-generales-2026-06-01.xlsx   # Base de datos fuente
├── datos.ipynb                       # Notebook principal de análisis
├── README.md                         # Documentación del proyecto
├── requirements.txt                  # Dependencias del proyecto
└── .gitignore
```

---

## Herramientas Utilizadas

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- OpenPyXL

---

## Metodología de Análisis

1. Importación de la base de datos.
2. Limpieza y validación de registros.
3. Transformación de variables.
4. Asignación de puntajes por criterio.
5. Cálculo del puntaje total por sede.
6. Generación de estadísticas descriptivas.
7. Construcción del ranking de priorización.
8. Selección de las 33 sedes prioritarias.

---

## Resultados Esperados

El análisis permite obtener:

- Puntaje total por sede educativa.
- Distribución estadística de los resultados.
- Ranking de priorización.
- Identificación de sedes críticas.
- Gráficos e indicadores para la toma de decisiones.

---

## Instalación

Clonar el repositorio:

```bash
git clone https://github.com/usuario/AD_SEDES_EDUCATIVAS.git
cd AD_SEDES_EDUCATIVAS
```

Instalar dependencias:

```bash
pip install -r requirements.txt
```

---

## Ejecución

Abrir el notebook principal:

```bash
jupyter notebook datos.ipynb
```

---

## Autor

Proyecto desarrollado para apoyar procesos de diagnóstico y priorización de infraestructura educativa mediante técnicas de análisis de datos.