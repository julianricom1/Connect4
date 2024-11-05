# Connect 4 Agent: Aprendiendo a Jugar Connect 4 con Reinforcement Learning

Este proyecto implementa un agente que aprende a jugar Connect 4 utilizando técnicas de aprendizaje por refuerzo. La estructura del proyecto se divide en múltiples notebooks para mantener el código modular y organizado.

## Estructura del Proyecto

1. **notebook_tablero.ipynb**: 
   - Define el tablero de Connect 4 y proporciona métodos para interactuar con él.
   - **Funciones principales**:
     - `colocar_ficha(columna)`: Coloca una ficha en la columna especificada.
     - `verificar_ganador()`: Verifica si hay un ganador después de cada movimiento.
     - `mostrar_tablero()`: Muestra el estado actual del tablero.
     - Métodos adicionales para gestionar el estado del juego.

2. **notebook_agente.ipynb**:
   - Define el agente de aprendizaje por refuerzo que jugará Connect 4.
   - **Características del agente**:
     - Implementación de un algoritmo de aprendizaje, como Q-learning o redes neuronales.
     - Métodos para seleccionar acciones, actualizar políticas y aprender del juego.

3. **notebook_entrenamiento.ipynb**:
   - Importa `notebook_tablero.ipynb` y `notebook_agente.ipynb` utilizando `nbimporter`.
   - Ejecuta el entrenamiento del agente, permitiéndole jugar múltiples partidas y aprender de la experiencia.
   - Registra el progreso del agente y evalúa su rendimiento con diferentes estrategias.

## Instalación y Configuración

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/tuusuario/connect4-agent.git
   ```
2. Instala las dependencias necesarias (si las hay). Asegúrate de tener Python y Jupyter Notebook instalados.
3. Instala `nbimporter` para importar notebooks:
   ```bash
   pip install nbimporter
   ```

## Cómo Usar el Proyecto

1. Abre `notebook_tablero.ipynb` y verifica la implementación del tablero de Connect 4.
2. Abre `notebook_agente.ipynb` para revisar o modificar el agente de aprendizaje por refuerzo.
3. Abre `notebook_entrenamiento.ipynb` para entrenar al agente y observar su progreso.

