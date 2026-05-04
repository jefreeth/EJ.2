# EJ.2
🎲 Simulación de Yahtzee con Montecarlo

Este proyecto implementa una simulación del juego Yahtzee para dos jugadores utilizando un enfoque de inteligencia artificial basado en el método de Montecarlo.

🧠 Descripción

El programa simula partidas completas de Yahtzee donde ambos jugadores son controlados por un sistema automático que toma decisiones óptimas mediante simulaciones probabilísticas.

El algoritmo evalúa múltiples escenarios posibles en cada turno y selecciona la mejor jugada según el valor esperado.

⚙️ Características
Simulación completa del juego con 2 jugadores
Uso de 5 dados con distribución uniforme
Hasta 3 lanzamientos por turno
Evaluación de todas las categorías del juego
Implementación de estrategia con Montecarlo
Estadísticas de lanzamientos y resultados
Sistema automático de decisión
🧩 Estructura del proyecto

El sistema está dividido en módulos:

Utilidades de dados: generación de valores aleatorios
Puntuación: cálculo de combinaciones (full house, escalera, etc.)
Estado del juego: manejo de jugadores y turnos
Montecarlo: toma de decisiones basada en simulación
Flujo del juego: control de la ejecución
Resultados: impresión de marcador y estadísticas
🤖 Método Montecarlo

El algoritmo utiliza simulaciones repetidas para estimar el mejor movimiento posible.
En cada turno:

Se prueban diferentes combinaciones de dados a conservar
Se simulan posibles resultados futuros
Se calcula el puntaje esperado
Se elige la mejor decisión

📊 Resultados

El programa muestra:

Puntaje final de cada jugador
Categorías utilizadas
Ganador
Estadísticas de frecuencia de los dados
