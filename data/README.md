# Preparación de Datos

La carpeta `data/` almacena los conjuntos de datos utilizados para entrenar y evaluar los modelos.

## Estructura

```
data/
└── raw/
    ├── created/   # Datos capturados con drones y preparados manualmente
    └── online/    # Datos descargados de fuentes externas
```

## Cómo preparar los datos

1. Coloca las imágenes capturadas por los drones en `data/raw/created/`.
2. Descarga o genera conjuntos adicionales y guárdalos en `data/raw/online/`.
3. Utiliza scripts en `src/` o tus propios notebooks para:
   - Limpiar y etiquetar las imágenes.
   - Convertir las anotaciones al formato requerido por el modelo (por ejemplo, YOLO).
4. Una vez procesados, mueve los datos listos para entrenamiento a la estructura que esperen los scripts de entrenamiento.

> Consulta la documentación del TFM en `docs/` para más detalles sobre el formato de los datos y las herramientas recomendadas.
