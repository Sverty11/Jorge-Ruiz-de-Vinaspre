# PINN-DE: Physics-Informed Neural Networks for Differential Equations

Este branch contiene la implementación y el estudio de **Redes Neuronales Informadas por la Física (PINNs)** para la resolución de ecuaciones diferenciales, tomando como base fundamental el trabajo de **M. Raissi, et al.**. El proyecto se desarrolla para el ramo Física computacional, bajo la tutela de Dr. Ariel Norambuena y Dr. Nicolás Viaux.

## 🎯 Objetivo del Proyecto
El objetivo principal es implementar y evaluar la eficacia de las PINNs para resolver problemas de valores iniciales y de contorno, comparando arquitecturas de **tiempo continuo** y **tiempo discreto**. Se busca automatizar la resolución de ecuaciones como el oscilador armónico simple, optimizando la convergencia mediante técnicas avanzadas de optimización.

---

## 📂 Estructura del Branch:
### [Avance 1] - Fundamentos y Proof of Concept
* **Codigos**: Todos los códigos con los modelos 1 a 3 se encuentran en el notebook PINNs Avance 1, este cuenta con los plots resultantes
* **Informe**: El informe 
* **Avances futuros**: Estos se irán publicando en carpetas, de manera similar y paralela al avance 1

---

## 🛠️ Requisitos del Entorno
Para ejecutar los notebooks en este repositorio (`PINNs Avance 1.ipynb`), se recomienda un entorno con:
* **Python 3.11+**
* **PyTorch**: Manejo de tensores y diferenciación automática.
* **NumPy y Matplotlib**: Procesamiento numérico y visualización de MSE.
* **CUDA**: se recomienda ejecutar con CUDA para mayor agilidad. Se recomienda usar google colab para la ejecución con CUDA para el notebook
---
**Desarrollado por:** Jorge Ruiz de Viñaspre Estudiante de Ingeniería Civil Física - UTFSM.
**contacto**: jruizdevinaspre@usm.cl