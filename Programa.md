# Cómputo Cuántico

> - **Duración:** 11 semanas
> - **Sesiones:** 2 por semana, 2 horas 15 minutos cada una
> - **Formato:** Teórico-práctico (con Qiskit en Google Colab y Mathematica)

## Parte 1 Fundamentos de mecánica cuántica para computación
**Semanas 1 a 8**

**Objetivos:**

> 1. Introducir conceptos básicos de mecánica cuántica útiles para la computación cuántica. Algunos de estos conceptos son:
> a. Ecuación de Scrhodinger.
> b. Qbits como estados cuánticos.
> c. Evolución temporal.
> d. Compuertas cuánticas como operadores unitarios.
> e. Circuitos cuánticos

> 2. Aplicar estos conceptos básicos en algunos algoritmos simples como:
> a. Preparación de estados cuánticos.
> b. Tomografía cuántica.
> c. Producción de estados de Bell.
> d. Simulación cuántica.

**Lista de reproducción de las clases**

[Youtube Cómputo Cuántico ](https://www.youtube.com/playlist?list=PLjxJ-S12oTd5jTTAsQUoWqNT60uXOAtRW)

**Programa:**

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

### Semana 5
#### Sesión 7:
>1. Preparación de estados con la matriz de Householder
>2. Medición de las fases de las amplitudes de probabilidad con phase kickbak
>- Ejercicio: Preparar un estado usando la matriz de Householder y medir las probabilidades y fases usando phase kickbak con Mathematica
>- Ejercicio: Preparar un estado usando la matriz de Householder y medir las probabilidades y fases usando phase kickbak con un circuito de Qiskit

#### Sesión 8:
>1. Introducción al entrelazamiento cuántico.
>2. Compuertas controladas
>1. La compuerta CNOT = CX
>2. Implementación de CX
>3. Implementación de cualquier compuerta controlada: CH y CU
>4. Propiedades de las compuertas controladas
>5. Cambio de control de una compuerta controlada
>6. Productos de compuertas controladas

### Semana 6
#### Sesión 9:
>1. Entrelazamiento cuántico
>2. Los estados de Bell
>- Ejercicio: Preparar los estados de Bell por medio de Qiskit

#### Sesión 10:
>1. Tomografía cuántica de los estados de Bell con Mathematica
>2. Tomografía cuántica de los estados de Bell con Qiskit
> - Ejercicio: implementar el algoritmo de tomografía cuántica para los estados de Bell

### Semana 7
#### Sesión 11:
> 1. Teoría de la simulación cuántica
> 2. Tomografía cuántica de la simulación cuántica
> - Ejercicio: implementar en Qiskit la simulación cuántica de un espín 1/2 en un campo magnético.

#### Sesión 12:
> 1. Implementación en Qiskit de una simulación cuantica de una partícula de espín 1/2 en presencia de un campo magnético.
> 2. Implementación en Python de un algoritmo clásico para estudiar la dinámica de una partícula de espín 1/2 en presencia de un campo magnético.
> 3. Comparación entre los algoritmos clásico y cuántico.
> - Ejercicio: Implementar en Qiskit la simulación cuántica de un espín 1/2 en un campo magnético obteniendo la evolución temporal completa.
> - Ejercicio: Implementar en Python la dinámica por medio de un algoritmo clásico de un espín 1/2 en un campo magnético obteniendo la evolución temporal completa.

### Semana 8
#### Sesión 13:
>1. Implementación en Qiskit de la simulación cuántica de dos partículas de espín 1/2 en presencia de un campo magnético y bajo la interacción de intercambio.
>2. Implementación en Python del algoritmo clásico de dos partículas de espín 1/2 en presencia de un campo magnético y bajo la interacción de intercambio.
> - Ejercicio: Implementar con Qiskit la simulación cuántica de dos partículas de espín 1/2 en presencia de un campo magnético y bajo la interacción de intercambio.
> - Ejercicio: Implementar con Python el algoritmo clásico de la dinámica de dos partículas de espín 1/2 en presencia de un campo magnético y bajo la interacción de intercambio.
> - Ejercicio: Comparar los resultados de los algoritmos cuántico y clásico.

# Parte 2 Algoritmos cuánticos
**Semanas 9 a 11**

**Objetivos:**
> 1. Usando los conocimientos obtenidos en la Partte 1 implementar algoritmos cuánticos tales como:
> a. Bernstein-Vazerani
> b. Transformación cuántica de Fourier (QFT)
> c. Estimación de fase
> d. Variational Quantum Eigensolver (VQE)
> e. Deutsch-Jozsa

**Programa:**

### Semana 9
#### Sesión 15:
> 1. El algoritmo de Bernstein-Vazirani
> - Ejercicio: Implementación del algoritmo de Bernstein-Vazirani en Qiskit

#### Sesión 16:
> 1. El circuito cuántico del algoritmo de Deutsch-Jozsa.
> 2. Funciones binarias como transformaciones unitarias.
> 3. Funciones constantes y funciones balanceadas.
> 4. Análisis teórico del algoritmo de Deutsch-Jozsa.
> - Ejercicio: Implementación del algoritmo de Deutsch-Jozsa en Qiskit.

### Semana 10
#### Sesión 16:
> 1. Implementación de los alumnos de diversos algoritmos

#### Sesión 17:
> 1. Implementación de algoritmos por los alumnos.
> 1. Algoritmo de la transformada cuántica de Fourier
> 2. Algoritmo de estimación de la fase
> 3. Algoritmo de Grover
> 4. Algoritmo de simulación cuántica de la matriz de densidad

### Semana 11
#### Sesión 18:
> 1. Presentación de los algoritmos de los alumnos.

#### Sesión 19:
> 1. Presentación de los algoritmos de los alumnos.


