# AluraStoreLatam — Análisis de Tiendas

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4%2B-11557C?logo=python)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-F9AB00?logo=googlecolab)
![Status](https://img.shields.io/badge/Status-Completo-brightgreen)

---

## 📖 Descripción

**AluraStoreLatam** es un proyecto de análisis de datos desarrollado como parte del *Challenge 1 de Data Science de Alura LATAM*. El objetivo es apoyar la toma de decisiones del Sr. João, propietario de la cadena **AluraStore**, evaluando el desempeño de sus **4 tiendas** a través de métricas clave para determinar cuál debería venderse y así financiar un nuevo emprendimiento.

El análisis cubre desde la facturación total hasta la satisfacción del cliente, generando visualizaciones comparativas con **matplotlib** para comunicar los hallazgos de forma clara.

---

## 🎯 Objetivos del Análisis

| # | Análisis | Visualización |
|---|----------|---------------|
| 1 | **Facturación total** | Gráfica de barras con valores en millones |
| 2 | **Ventas por categoría** | Barras agrupadas + mapa de calor |
| 3 | **Calificación promedio** | Barras con línea de promedio general |
| 4 | **Productos más y menos vendidos** | Subplots separados por extremo |
| 5 | **Costo de envío promedio** | Barras con formato de moneda y promedio |

---

## 📁 Estructura del Proyecto

```
AluraStoreLatam/
│
├── AluraStoreLatam.ipynb    # Notebook principal con el análisis completo
└── README.md                # Documentación del proyecto
```

> 📌 Los datos se cargan directamente desde el repositorio oficial de Alura; no se requieren archivos CSV locales.

---

## 🗄️ Fuente de Datos

Los datos provienen del repositorio oficial del challenge:

```
https://github.com/alura-es-cursos/challenge1-data-science-latam
```

Se utilizan 4 archivos CSV (uno por tienda): `tienda_1.csv`, `tienda_2.csv`, `tienda_3.csv` y `tienda_4.csv`.

**Variables utilizadas:**

| Columna | Descripción |
|--------|-------------|
| `Precio` | Precio de venta del producto |
| `Categoría del Producto` | Categoría a la que pertenece el artículo |
| `Producto` | Nombre del producto vendido |
| `Calificación` | Puntuación otorgada por el cliente (1–5) |
| `Costo de envío` | Costo logístico de cada orden |

---

## ⚙️ Requisitos

No se requiere instalación local. El proyecto corre en **Google Colab**, que incluye `pandas` y `matplotlib` preinstalados. Solo necesitas una cuenta de Google y conexión a internet.

---

## 🚀 Cómo Ejecutar el Proyecto

1. Abre [Google Colab](https://colab.research.google.com/)
2. Ve a **Archivo → Abrir notebook → GitHub**
3. Ingresa la URL del repositorio y selecciona `AluraStoreLatam.ipynb`
4. Ejecuta todas las celdas con `Entorno de ejecución → Ejecutar todo`

---

## 📊 Resultados Esperados

Al ejecutar el notebook completo obtendrás visualizaciones comparativas para cada métrica y una **recomendación final** sobre qué tienda vender, respaldada en los datos analizados.


---

## 👤 Autor

 **Joshep Ccahuana para Challenge 1 — Data Science** de [Alura LATAM](https://www.aluracursos.com/).
