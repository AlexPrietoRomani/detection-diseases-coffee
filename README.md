# Detección de Enfermedades en Plantas de Café

Este Trabajo Fin de Máster (TFM) utiliza imágenes capturadas por **drones** para detectar enfermedades en hojas de café y así habilitar aplicaciones focalizadas de insecticidas y fungicidas. El sistema se basa en técnicas de **Deep Learning** que permiten identificar rápidamente la condición de las plantas a partir de fotografías.

Como punto de partida se realiza un *fine tuning* de YOLO para reentrenar el modelo y clasificar imágenes o video con el fin de detectar enfermedades en café.

## 📂 Estructura del Proyecto

```plaintext
notebooks/           # Jupyter Notebooks de experimentación y modelado
data/
└── raw/
    ├── created/     # Datos capturados con drones
    └── online/      # Datos provenientes de fuentes externas
models/
└── base/            # Modelos pre-entrenados
└── fine_tuned/      # Modelos ajustados con nuestros datos
outputs/             # Resultados, métricas y artefactos generados
src/                 # Scripts de entrenamiento e inferencia
docs/                # Memoria del TFM y documentación adicional
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

1. Clona el repositorio.
2. Crea un entorno virtual (opcional pero recomendado).
3. Instala las dependencias desde `requirements.txt`.
4. Prepara los datos siguiendo las instrucciones en [`data/README.md`](data/README.md).
5. Entrena un modelo ejecutando `python notebooks/Modelos.ipynb` o los scripts ubicados en `src/`.
6. Realiza inferencias sobre nuevas imágenes mediante los scripts de `src/` o adaptando el notebook anterior.

> La memoria del TFM y documentación adicional se encuentran en el directorio [`docs/`](docs/).

## 📈 Resultados

Se compararon distintos modelos de clasificación evaluando métricas como:

- Precisión (Accuracy)

- Matriz de confusión

- Reportes de clasificación

El mejor modelo es exportado para su uso posterior en producción.

## 📜 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.


¡Si encuentras útil este proyecto, no olvides dejar una estrella ⭐️ y contribuir!
