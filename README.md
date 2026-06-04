# Regresión Logística para Predicción de Admisión Universitaria

## 📋 Descripción del Proyecto

Este proyecto implementa un modelo de **Regresión Logística Binaria desde cero** (sin usar librerías de Machine Learning como scikit-learn) para predecir si un estudiante será admitido en un programa de posgrado en Ingeniería de Sistemas.

El modelo utiliza dos variables predictoras continuas:
- **Promedio de pregrado** (escala 0-100)
- **Puntaje en examen de ingreso** (escala 0-100)

Y genera como salida:
- **Probabilidad de admisión** (valor entre 0 y 1)
- **Clasificación binaria** (Admitido = 1 / Rechazado = 0)

---

## 👤 Autor

- **Nombre:** Gabriela Dávalos Nuñez
- **Materia:** Métodos Numéricos
- **Carrera:** Ingeniería de Sistemas
- **Fecha:** 05/06/2026

---

## 🎯 Caso de Uso

El problema resuelto corresponde al **Escenario C** de la investigación: predicción de una variable discreta/categórica (admitido/rechazado) a partir de variables predictoras continuas (promedio y examen).

**Aplicación en Ingeniería de Sistemas:**
Este modelo puede integrarse como un microservicio dentro de un sistema de gestión universitaria, automatizando la preselección de candidatos y reduciendo sesgos subjetivos en el proceso de admisión.

---

## 📁 Estructura del Proyecto

├── 📄 README.md

├── 📄 Aplicación del metodo.ipynb

├── 📄 datos_estudiantes.csv

├── 🖼️ grafica_resultados.png

└── 📄 requirements.txt

---

## 💻 Requisitos y Dependencias

### Requisitos de Hardware
- **Mínimo:** 2GB RAM, cualquier procesador
- **Recomendado:** 4GB RAM (para ejecutar sin problemas)

### Requisitos de Software
- **Sistema operativo:** Windows 10/11, macOS, o Linux (cualquier distribución)
- **Python:** Versión 3.7 o superior
- **Navegador web:** Chrome, Firefox, o Edge (para Google Colab)

### Dependencias de Python

| Librería | Versión | ¿Para qué sirve? |
|----------|---------|------------------|
| numpy | ≥ 1.19.0 | Operaciones matemáticas y arrays |
| pandas | ≥ 1.2.0 | Manejo de datos tabulares |
| matplotlib | ≥ 3.3.0 | Generación de gráficas |

### Instalación de dependencias (solo para ejecución local)

Abre tu terminal (CMD, PowerShell, o terminal de Linux/macOS) y ejecuta:

```bash
pip install numpy pandas matplotlib

