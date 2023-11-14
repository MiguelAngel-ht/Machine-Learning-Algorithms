# Guía de Redes Neuronales: FFNN y RNN

Este repositorio ofrece una comprensión profunda de dos arquitecturas de redes neuronales clave: Redes Neuronales Feedforward (FFNN) y Redes Neuronales Recurrentes (RNN). Además, se exploran sus implementaciones mediante TensorFlow y Keras, destacando sus diferencias, ventajas, desventajas y aplicaciones en problemas de aprendizaje automático.

## FFNN (Feedforward Neural Networks)

Las Redes Neuronales Feedforward, o FFNN, son la forma más directa de redes neuronales. En estas redes, la información se mueve solo en una dirección: hacia adelante desde las capas de entrada, a través de las capas ocultas y, finalmente, a la capa de salida. No hay ciclos o bucles en estas redes, lo que las hace arquitectónicamente más sencillas.

### Implementación con TensorFlow y Keras
TensorFlow y Keras facilitan la creación de modelos FFNN con su API intuitiva y flexible. Puedes definir capas, funciones de activación, procesos de entrenamiento y más con solo unas pocas líneas de código.

### Aplicaciones
- Clasificación de imágenes
- Detección de fraudes
- Predicciones de series temporales (simple)
- Sistemas de recomendación

## RNN (Recurrent Neural Networks)

Las Redes Neuronales Recurrentes, o RNN, son una clase de redes neuronales ideales para procesar secuencias y series temporales. A diferencia de las FFNN, las RNN tienen conexiones de retroalimentación que les permiten procesar no solo la entrada actual sino también la información recibida anteriormente.

### Implementación con TensorFlow y Keras
Implementar RNN con TensorFlow y Keras es igualmente accesible. Keras proporciona capas específicas como `SimpleRNN`, `LSTM` y `GRU` que son fundamentales para construir redes recurrentes.

### Aplicaciones
- Procesamiento de lenguaje natural
- Reconocimiento de voz
- Análisis de series temporales
- Generación de música

## Diferencias entre FFNN y RNN

| Característica | FFNN | RNN |
| --- | --- | --- |
| Flujo de Información | Unidireccional | Con retroalimentación (temporal) |
| Manejo de Secuencias | No adecuado para secuencias | Diseñado para secuencias y series temporales |
| Complejidad | Más simple | Más compleja (manejo de dependencias temporales) |

## Ventajas y Desventajas

### FFNN
- **Ventajas**: Simplicidad, efectividad en problemas lineales, fácil de entrenar.
- **Desventajas**: No adecuadas para datos secuenciales, limitadas en complejidad y expresividad.

### RNN
- **Ventajas**: Excelentes para datos secuenciales, pueden manejar información de secuencias de longitud variable, poderosas para capturar dependencias temporales.
- **Desventajas**: Más difíciles de entrenar (problemas de gradientes que desaparecen), computacionalmente más intensivas.

---

Este repositorio ofrece ejemplos prácticos, guías y recursos para comprender y aplicar estas poderosas herramientas en una variedad de problemas de aprendizaje automático. Con TensorFlow y Keras, estas arquitecturas de redes neuronales se vuelven accesibles para experimentar y aplicar en tareas reales de ML.
