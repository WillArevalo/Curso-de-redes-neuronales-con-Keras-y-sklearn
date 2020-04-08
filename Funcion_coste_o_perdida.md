# Funcion de coste o perdida4

Son aquellas que permiten tomar un valor del error por epoca en los entrenamientos

## Funciones de perdida para variables de regresion

### Mean Absolute Error (MAE)

- Describe la magnitud tipica de los residuos.
- Robusta frente a outliers.
- Facil interpretacion y sus unidades son las mismas de la funcion analizada.

### Mean Squared Error (MSE)

Penaliza mas el error

- Penaliza en gran forma el modelo cuando existen grandes errores.
- Suele ser la funcion de perdidas por defecto.
- Sensible a outliers.

### Mean Absolute Percentage Error (MAPE)

- Penaliza el modelo cuando existen grandes errores.
- Robusto frente a outliers por el uso de valor absoluto.

## Funciones de perdida para variables categoricas

En un caso donde un cliente esta en riesgo de dejar de pagar su hipoteca si o no se utilizaria *Binary Cross-entropy*

En caso de tener multiples categorias en necesario utilizar *Categorical Cross-entropy*