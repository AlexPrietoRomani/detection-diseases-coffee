# Detección de Enfermedades en Plantas de Café

Este proyecto desarrolla un sistema basado en **Deep Learning** para detectar enfermedades en hojas de café a partir de imágenes. Utilizando modelos de clasificación, el sistema ayuda a identificar la condición de las plantas de manera rápida y precisa.

Este proyecto usa como base un Fine Turning de YOLO para poder reentrenar el modelo y poder clasificar las imagenes o video para detectar enfermedades en café.

## 📂 Estructura del Proyecto

```plaintext
notebooks/           # Jupyter Notebooks de experimentación y modelado
data/                # Archivos de datos (CSV de comparación de modelos)
images/              # Imágenes de prueba usadas para validación
predictions/         # Resultados y predicciones almacenadas
models/              # Modelos entrenados exportados
requirements.txt     # Librerías necesarias
.gitignore           # Archivos ignorados por Git
README.md            # Documentación general
```

## 🎯 Objetivo

Detectar enfermedades en hojas de café utilizando técnicas de aprendizaje automático, clasificando las imágenes en distintas categorías de salud o enfermedad.

## 🛠 Tecnologías Utilizadas

- Python 3

- TensorFlow / Keras (posiblemente si usaste redes neuronales)

- Scikit-learn

- Pandas

- NumPy

- Matplotlib

- OpenCV (para procesamiento de imágenes)

## 🚀 Cómo Usar

1. Clona el repositorio:

2. Crea un entorno virtual (opcional pero recomendado):

3. Instala las dependencias:

4. Abre y ejecuta los notebooks ubicados en la carpeta notebooks/.

## 📈 Resultados

Se compararon distintos modelos de clasificación evaluando métricas como:

- Precisión (Accuracy)

- Matriz de confusión

- Reportes de clasificación

El mejor modelo es exportado para su uso posterior en producción.

## 📜 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.


¡Si encuentras útil este proyecto, no olvides dejar una estrella ⭐️ y contribuir!
