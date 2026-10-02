# Introducción a la Computación Cuántica — Universidad de Nariño 2026

Curso teórico-práctico de 9 horas sobre los fundamentos de la computación cuántica y su implementación con [Qiskit](https://www.ibm.com/quantum/qiskit), ofrecido a estudiantes del Departamento de Física de la Universidad de Nariño del 30 de septiembre al 2 de octubre de 2026.

## Objetivo general

Comprender los principios fundamentales de la computación cuántica y explorar su aplicación mediante la construcción, simulación y análisis de circuitos cuánticos, utilizando Qiskit para implementar y experimentar con algoritmos cuánticos.

## Objetivos específicos

Al finalizar el curso, los participantes estarán en capacidad de:

- Comprender los conceptos básicos de qubit, superposición, medición y entrelazamiento como elementos fundamentales de la computación cuántica.
- Representar y construir circuitos cuánticos mediante compuertas cuánticas, interpretando su funcionamiento y evolución.
- Utilizar Qiskit para diseñar, simular y ejecutar circuitos cuánticos, interpretando los resultados obtenidos.
- Reconocer las principales aplicaciones y desafíos actuales de la computación cuántica, particularmente en optimización, criptografía, inteligencia artificial y ciencia de datos.

No se requieren conocimientos previos en computación cuántica. Se asume álgebra lineal básica (vectores, matrices, producto interno).

## Notebooks del curso

Cada sesión es un notebook autocontenido (teoría + código + visualizaciones + ejercicios) pensado para Google Colab.

| Sesión | Contenido | Abrir en Colab |
|---|---|---|
| **1 — Fundamentos** | Qubit, superposición, medición (regla de Born), entrelazamiento, compuertas de 1 y 2 qubits, estados de Bell | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nicoavilan/Intro-Comp-Cuant-UNarino-2026/blob/main/Sesion1_Fundamentos_Computacion_Cuantica.ipynb) |
| **2 — Circuitos y simulación** | Transpilación, compuertas paramétricas ($R_x,R_y,R_z$), ruido , teletransportación cuántica | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nicoavilan/Intro-Comp-Cuant-UNarino-2026/blob/main/Sesion2_Circuitos_Transpilacion_Ruido.ipynb) |
| **3 — Algoritmos cuánticos y aplicaciones** | Algoritmo de Bernstein-Vazirani.  QAOA el problema Max-Cut | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]((https://github.com/nicoavilan/Intro-Comp-Cuant-UNarino-2026/blob/main/Sesion3_Algoritmos_Aplicaciones.ipynb)) |


Cada notebook es independiente: instala sus propias dependencias en la primera celda, así que puedes abrir cualquiera directamente en Colab sin configuración previa.

## Cómo usar este repositorio

1. Haz clic en el botón **Open in Colab** de la sesión que quieras trabajar.
2. En Colab, guarda tu propia copia (`Archivo → Guardar una copia en Drive`) antes de empezar a editar.
3. Ejecuta las celdas en orden — cada sesión asume que completaste la anterior.
4. Los ejercicios al final de cada notebook incluyen celdas de código con el esqueleto listo para completar.

## Requisitos

Ninguno además de una cuenta de Google para usar Colab. Cada notebook instala `qiskit`, `qiskit-aer` y las dependencias de visualización en su primera celda.

## Estructura del curso

El curso está diseñado como 3 bloques de 3 horas (9 horas totales), con una proporción aproximada de 40% teoría / 60% práctica en cada uno:

1. **Fundamentos** → construir intuición y verificar los postulados básicos en código.
2. **Circuitos y simulación** → pasar de "circuito lógico" a lo que realmente se ejecuta en hardware (transpilación, ruido).

## Referencias

- Nielsen, M. A. & Chuang, I. L. *Quantum Computation and Quantum Information*. Cambridge University Press.
- [IBM Quantum Learning](https://quantum.cloud.ibm.com/learning/)
- [Documentación de Qiskit](https://docs.quantum.ibm.com)

## Contacto

Nicolás Avilán — Universidad del Rosario
