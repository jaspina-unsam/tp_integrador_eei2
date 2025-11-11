# Trabajo Práctico Integrador - Estadística e Inferencia II

**Universidad Nacional de San Martín - Escuela de Ciencia y Tecnología**  
**2do Cuatrimestre 2025**

**Autor:** Javier Spina  
**Email:** jaspina@estudiantes.unsam.edu.ar

---

## Resumen

Análisis bayesiano del dataset **Iris** y del **World Happiness Report (WHR)**, mediante modelos bayesianos, modelos de mezcla gaussianos y procesos gaussianos. Para el estudio de WHR, se estudia la relación entre condiciones estructurales (desarrollo humano, desigualdad, inversión en educación, desempleo, equidad de género) y el índice de felicidad en países agrupados por región geopolítica.

**Dataset:** Quality of Government Standard Dataset (Universidad de Gotemburgo)  
**Periodo:** 2006-2023 | **Países:** 150+ | **Observaciones:** 1800+

---

## Contenido

### 📂 `notebooks/`

- **`Parte1.ipynb`**: EDA, Modelos bayesianos lineales y jerarquicos
- **`Parte2_v2.ipynb`**: EDA, Modelos jerárquicos (GLMs), modelos de mezcla, procesos gaussianos

### 📂 `datasets/`

- `qog_bas_ts_jan25.csv`: Dataset original QoG
- `WHR25_Data_Figure_2.1v3.xlsx`: Dataset del WHR

## Tecnologías

![Python](https://img.shields.io/badge/Python-3.11-blue)
![PyMC](https://img.shields.io/badge/PyMC-5.x-orange)
![ArviZ](https://img.shields.io/badge/ArviZ-0.x-green)

**Stack:** PyMC, ArviZ, PreliZ, NumPy, Pandas, Matplotlib, Seaborn, GeoPandas

---

## Principales Hallazgos

- **HDI** es el predictor más robusto de felicidad (β ≈ 0.85, HDI 94%)
- **Desigualdad económica** tiene efecto negativo significativo controlando por desarrollo
- Estructura jerárquica **región → país** captura efectos contextuales importantes
- Distribución de felicidad sugiere ~6 clusters

---

## Referencias

- **QoG Institute**: https://www.gu.se/en/quality-government
- **World Happiness Report**: https://www.worldhappiness.report/

---

## Licencia

Este trabajo es material académico de la Universidad Nacional de San Martín.
