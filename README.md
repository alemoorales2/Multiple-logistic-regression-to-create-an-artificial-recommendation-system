# ¿Qué comemos hoy? 🍔🤖

Este proyecto desarrolla un sistema de recomendación de restaurantes usando **regresión logística multinomial**, a partir de los datos de **edad** y **presupuesto** del usuario.

> Proyecto académico - Parte de la asignatura de Investigación Operativa del Grado de Matemáticas de la Universidad de Málaga.

---

## 🎯 Objetivo

Predecir el tipo de comida que prefiere un usuario entre estas categorías:

- 🍕 Italiana
- 🥘 Española
- 🍜 Asiática
- 🍔 Fast Food

---

## 📁 Archivos

- `Sistema_de_recomendacion.ipynb`: cuaderno con todo el código del modelo.
- `Trabajo_Regresion_Logistica.pdf`: informe explicativo completo.
- `data/`: carpeta opcional para incluir los archivos `.xlsx` usados.

---

## 📊 Resultados

- Precisión con datos desbalanceados: ~26%
- Precisión con datos equilibrados: ~64.5%
- Con nueva variable (género): hasta 94%

---

## ⚙️ Requisitos

```bash
pip install pandas numpy scikit-learn matplotlib
