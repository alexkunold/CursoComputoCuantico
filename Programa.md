# Cómputo Cuántico

> - **Duración:** 11 semanas
> - **Sesiones:** 2 por semana, 2 horas 15 minutos cada una
> - **Formato:** Teórico-práctico (con Qiskit en Google Colab)


## Parte I – Fundamentos de Mecánica Cuántica para Computación
**Semanas 1 a 3**
> **Objetivo:** Introducir conceptos de mecánica cuántica esenciales para entender el cómputo cuántico. Se incluirán ejemplos en Qiskit desde la segunda sesión.

### Semana 1
#### Sesión 1:
>1. Introducción al curso, objetivos y programa de estudios.
>1. Historia de la computación cuántica
>1. Aplicaciones de la computación cuántica
>1. Tipos de computadoras cuánticas
>1. Cómputo Cuántico. ¿Qué es?
>1. Qubits y bra-kets 

#### Sesión 2:
>1. Operadores cuánticos y su acción sobre qubits
>1. Breve introducción a Qiskit
> - Ejercicio: creación de un circuito básico de 1 qubit en Qiskit y visualización de su estado

### Semana 2
#### Sesión 3:
>1. Análisis de algunos ejemplos de circuitos de un qubit usando las compuertas M, X y H.
>1. Análisis de alugnos ejemplos de circuitos de varios qubits usando las compuertas M, X y H.
> - Ejercicio: Escribir el código de varios circuitos en Qiskit y analizarlos teóricamente

#### Sesión 4:
>1. La ecuación de Schrödinger y el Hamiltoniano
>2. El operador de evolución temporal como matriz unitaria
>3. Qubits y compuertas cuánticas como vectores y matrices
>4. Ejercicio en Qiskit: compuerta Hadamard y medición
>5. Visualización de estados con `plot_bloch_multivector`

### Semana 3
#### Sesión 5:
>1. Síntesis de compuertas de un qubit
>2. Síntesis de compuertas de varios qubits
>3. Transpilación con bases de matrices
>4. Transpilación con una computadora cuántica genérica
>5. Profundidad de los circuitos cuánticos
> - Ejercicio: Implementar compuertas unitarias con `QuantumCircuit.unitary()`, transpilar con una base de matrices y con una computadora cuántica genérica. Cálculo de la profundidad del circuito.

### Semana 4
#### Sesión 6:
>1. Mediciones en bases de estados arbitrarios
>2. Retroceso de fase (phase kickbak)
>- Ejercicio: Medir un estado en bases arbitrarias


### Semana 4
#### Sesión 6:
>1. Compuertas controladas
>2. La compuerta CU (unitaria controlada)
> - Ejercicio: implementación de una compuerta CU
>3. Haciendo mediciones en distintas bases
> - Ejercicio: medición de un qubit en distintas bases

# Parte II – Introducción Formal a Qiskit y Circuitos Cuánticos
**Semanas 4 a 7**
> **Objetivo:** Dominar la construcción de circuitos cuánticos en Qiskit y entender formalmente los elementos básicos de la computación cuántica.

### Semana 4
#### Sesión 7:
>1. Representación de un qubit como vector, matriz y ket
>1. Estado cuántico de múltiples qubits

#### Sesión 8:
>1. Producto de Kronecker
>    - Ejercicio: crear circuitos de 2 qubits en Qiskit, medir y analizar

### Semana 5
#### Sesión 9:
>1. Representación de compuertas de un qubit como matrices y operadores
>1. Compuerta Hadamard, Pauli X, Y, Z, fase S, T

#### Sesión 10:
>1. Implementación práctica de compuertas de un qubit en Qiskit
> - Ejercicio: secuencia de compuertas y evolución del estado

### Semana 6
#### Sesión 11:
>1. Compuertas de más de un qubit
>1. Producto de Kronecker en compuertas multiqubit

#### Sesión 12:
>1. Compuerta CNOT: definición, acción y visualización
>    - Ejercicio: demostración de entrelazamiento con Hadamard + CNOT

### Semana 7
#### Sesión 13:
>1. Compuerta general de un qubit: parametrización
>1. Teorema de universalidad

#### Sesión 14:
>1. Cadenas de Pauli
>1. Las compuertas de cadenas de Pauli
>    - Ejercicio práctico: construir una compuerta arbitraria con compuertas básicas + CNOT
>1. Introducción a los estados de Bell

## Parte III – Algoritmos Cuánticos y Proyecto Final
**Semanas 8 a 11**

> **Objetivo:** Comprender y aplicar algoritmos cuánticos. Los estudiantes trabajarán en un proyecto final.

### Semana 8
#### Sesión 15:
>1. Estados de Bell: teoría y construcción
>    - Ejercicio: construcción de los 4 estados de Bell

#### Sesión 16:
>1. Medición en estados entrelazados
>1. Entropía de entrelazamiento (introductoria y cualitativa)

### Semana 9
#### Sesión 17:
>1. Introducción al algoritmo de determinación de fase
>    - Ejercicio en Qiskit: construcción del circuito de fase

#### Sesión 18:
>1. Teoría del algoritmo de VQE (Variational Quantum Eigensolver)
>1. Idea de funciones costo y optimización clásica

### Semana 10
#### Sesión 19:
>1. Implementación práctica del VQE con un Hamiltoniano simple (ej. de H₂)
>1. Uso del módulo qiskit.algorithms y qiskit_nature

#### Sesión 20:
>1. Inicio del proyecto final (en parejas o individual)
>1. Definición del problema y diseño del circuito

### Semana 11
#### Sesión 21:
>1. Asesoría y revisión de avances de los proyectos
>1. Preguntas abiertas y discusión de problemas

#### Sesión 22:
> 1. Presentación de proyectos finales
> 1. Retroalimentación grupal y cierre del curso
