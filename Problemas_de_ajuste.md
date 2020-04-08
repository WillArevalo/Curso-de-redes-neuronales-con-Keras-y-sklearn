# Problemas de ajuste

## Problemas frecuentes(Underfitting y Overfitting)



Estos son los problemas más comunes que pueden surgir en el proceso de entrenar algoritmos:

**Underfitting (Subajustar)** 

Se presenta cuando un modelo no puede capturar la tendencia de los datos. Es generalmente el resultado de un modelo extremadamente simple.
<br>

**Overfitting (Sobreajustar)** 

Se presenta cuando un algoritmo está perfectamente adaptado a los datos con los que lo entrenamos., pero si tratamos de predecir nuevos datos , lo más probable es que nos de error.

Consejo para resolver el Underfitting:

    Se recomienda tratar de agregar más features al dataset, es decir, agregar más columnas con condiciones al modelo.

Consejos para resolver el Overfitting:

    Se recomienda disminuir la cantidad de features al dataset, es decir, quitar columnas con condiciones al modelo.
    También se recomienda agregar más ejemplos para el entrenamiento, es decir, agregar renglones con ejemplos de datos para el modelo.

![Over_and_underfitting](https://raw.githubusercontent.com/WillArevalo/Intro-Machine-Learning/5dd192ebe9dc4011190b58be50c12cbc0825f119/Apuntes%20Jupyter/problemsMachineLearn.png)

Mas referencias:

    https://github.com/WillArevalo/Intro-Machine-Learning/blob/master/Apuntes%20Jupyter/18%20-%20Problemas%20Frecuentes%20en%20Machine%20Learning.ipynb

    https://github.com/WillArevalo/Curso-de-Machine-Learning-Aplicado-con-Python/blob/master/18%20-%20Ajustando%20Modelos%20de%20Machine%20Mearning,%20Underfitting%20y%20Overfitting.ipynb?short_path=d1e8467