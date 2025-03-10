# regresion-lineal-
## realisado por miguel angel rodriguez Hernadez 
# Regresión Lineal con Datos de Pokémon

Este proyecto utiliza regresión lineal para predecir el ataque (`attack`) de un Pokémon en función de su altura (`height`) y peso (`weight`). Se utilizan datos del archivo `pokedex.csv`.

## Requisitos

Antes de ejecutar el código, instala las siguientes librerías si aún no las tienes:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Uso

1. Cargar los datos de `pokedex.csv`.
2. Seleccionar `height` y `weight` como variables predictoras y `attack` como variable objetivo.
3. Dividir los datos en conjuntos de entrenamiento y prueba.
4. Entrenar un modelo de regresión lineal.
5. Evaluar el modelo con métricas como MSE y R².
6. Visualizar los resultados con gráficos de dispersión.

## Ejecución

Ejecuta el script en un entorno de Jupyter Notebook o Python:

```python
python regresion_pokedex.py
```

## Resultados

El modelo genera predicciones sobre el ataque de los Pokémon en función de su altura y peso, mostrando la relación con gráficos de dispersión.

---

© 2024 - Proyecto de Regresión Lineal con Pokémon
