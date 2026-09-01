# PINN-DE: Physics-Informed Neural Networks for Differential Equations

Este branch contiene la implementación y el estudio de **Redes Neuronales Informadas por la Física (PINNs)** para la resolución de ecuaciones diferenciales, tomando como base fundamental el trabajo de **M. Raissi, et al.**. El proyecto se desarrolla para el ramo Física computacional, bajo la tutela de Dr. Ariel Norambuena y Dr. Nicolás Viaux.

## 🎯 Objetivo del Proyecto
El objetivo principal es implementar y evaluar la eficacia de las PINNs para resolver ecuaciones diferenciales. El proyecto se enfoca en el desarrollo de un sistema "perfil estructural" oscilatorio de 4 grados de libertad. Se documenta la transición de funciones de activación tipo Tanh() a arquitecturas tipo Fourier Encoding y SIREN, también pasando del optimizador de primer orden Adam a uno de segundo orden SOAP.

---

## 📂 Estructura del Branch:
### [Avance 1] - Fundamentos y Proof of Concept
* **Codigos**: Todos los códigos con los modelos 1 a 3 se encuentran en el notebook PINNs Avance 1, este cuenta con los plots resultantes
* **Informe**: El informe 
* **Avances futuros**: Estos se irán publicando en carpetas, de manera similar y paralela al avance 1

### [Avance 2] - Planteamiendo sistema de 4 grados de libertad
* **Cambio de Contexto operacional**: Se plantea un sistema de estructura de edificio de 4 pisos a resolver ante forzamiento oscilatorio.
* **Cambio de arquitectura**: Se implementan redes SIREN con optimizador SOAP para solventar no-convergencia de arquitectura Tanh con optimizador ADAM
* **Modelo entrenado**: Se añadió el archivo con los pesos para la última versión del modelo SIREN.

### [Avance 3] - Expansión de análisis de resultados
* **Finalización de informe**: Se añaden análisis a mayor profundidad de los resultados finales obtenidos durante el proyecto.
* **Códigos de análisis**: Se incluyen códigos utilizados para llevar a cabo dichas correcciones, se utiliza el modelo cuyos pesos están subidos en el **Avance 2** (https://github.com/Sverty11/Jorge-Ruiz-de-Vinaspre/blob/proyecto_final/Avance%202/modelo_siren_4dof.pth)

---

## 🛠️ Requisitos del Entorno
Para ejecutar los notebooks en este repositorio se recomienda un entorno con:
* **Python 3.11+**
* **PyTorch**: Manejo de tensores y diferenciación automática.
* **NumPy y Matplotlib**: Procesamiento numérico y visualización de MSE.
* **CUDA**: se recomienda ejecutar con CUDA para mayor agilidad. Se recomienda usar google colab para la ejecución con CUDA para el notebook
---
**Desarrollado por:** Jorge Ruiz de Viñaspre Estudiante de Ingeniería Civil Física - UTFSM.
**contacto**: jruizdevinaspre@usm.cl
