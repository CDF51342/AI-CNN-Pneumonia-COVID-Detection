# PRÁCTICA 2

IA en la Salud 
Aplicaciones Avanzadas de la IA  
Máster Universitario en Ingeniería Informática (2024/25)

---

## 1. Introducción

Este repositorio corresponde a la **Práctica 2** de la asignatura _Aplicaciones Avanzadas de la IA_ del Máster Universitario en Ingeniería Informática (curso 2024/25)

---

## 2. Contexto del Problema


---

## 3. Objetivos de la Práctica

---

## 4. Estructura de los Ficheros

La organización del repositorio es la siguiente:

```
root/
│── data/  # Datos
│   └── covid-chest-xray/  # Datos originales
└── README.md
```

- **[`data/`](./data/)**: Contiene los directorios de cada dataset.
- **[`README.md`](./README.md)** (este fichero): Explica el contexto general, los objetivos y la estructura del proyecto.

---

## 5. Autores del Proyecto

Este proyecto ha sido realizado para la asignatura _Aplicaciones Avanzadas de la IA_ por el _Grupo 9_:

- **Carlos Díez Fenoy - 100451342**
- **Juan Romero Sanz - 100535977**
- **Juan María Villard Bardón - 100439614**

Máster Universitario en Ingeniería Informática (2024/25)

---

## 6. Uso y Ejecución (VER)

1. **Instalación de Dependencias**  
   Es recomendable utilizar un entorno virtual (por ejemplo, `venv` o `conda`) con Python 3.7+ y las librerías `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, entre otras. De todas formas, se añaden las líneas de código necesarias para ejecutar los notebooks en los mismos.
   Para que los notebooks funcionen, es necesario ejecutar el fichero [`requirements.txt`](./requirements.txt):
   ```bash
   pip install -r requirements.txt
   ```
2. **Estructura de Datos**  
   Verifica que los archivos Excel se encuentren en las subcarpetas Driver1, Driver2, etc., dentro de [`data/`](./data/).
3. **Ejecución de Notebooks**
   - [`1. Preprocesamiento y Exploración.ipynb`](./1.%20Preprocesamiento%20y%20Exploración.ipynb): Para limpiar y explorar los datos.
   - [`2. Segmentación y Modelado.ipynb`](./2.%20Segmentación%20y%20Modelado.ipynb): Donde se definen las ventanas temporales y se entrena el modelo de IA.
   - [`3. Resultados, Análisis y Conclusiones.ipynb`](./3.%20Resultados,%20Análisis%20y%20Conclusiones.ipynb): Para evaluar métricas, comparar estrategias (ventanas overlapping o no) y extraer conclusiones.

---

## 7. Conclusiones Generales

