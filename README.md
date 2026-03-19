# Evaluador de Sesgo y Fuga de Talento STEM

## Descripción del proyecto

Este proyecto analiza la **brecha de género en el sector tecnológico** mediante técnicas de Inteligencia Artificial y Machine Learning

El objetivo es estudiar tres problemas principales:

1. **Abandono de carrera en mujeres STEM**  
   Se utiliza un modelo de **árbol de decisión** para identificar qué factores pueden influir en que una mujer abandone su carrera profesional en tecnología.

2. **Brecha salarial en el sector tecnológico**  
   Se utiliza un modelo de **regresión** para estimar salarios según variables como experiencia, cargo, sector y género, con el fin de detectar posibles diferencias salariales.

3. **Sesgo de género en ofertas de empleo**  
   Se analiza el texto de ofertas de trabajo del sector tecnológico mediante técnicas de **procesamiento de lenguaje natural (NLP)** para clasificar el nivel de sesgo en el lenguaje utilizado.

---

## Estructura del proyecto

```bash
proyecto-stem/
│
├── data/
│   ├── raw/                 # Datos originales
│   └── processed/           # Datos limpios o transformados
│
├── notebooks/
│   ├── 01_arbol_decision.ipynb
│   ├── 02_regresion_salarial.ipynb
│   └── 03_nlp_sesgo_ofertas.ipynb
│
├── src/
│   ├── preprocessing.py     # Funciones de limpieza de datos
│   ├── train_decision_tree.py
│   ├── train_regression.py
│   └── train_nlp.py
│
├── images/                  # Gráficas o capturas para informe/presentación
├── requirements.txt         # Librerías necesarias
└── README.md