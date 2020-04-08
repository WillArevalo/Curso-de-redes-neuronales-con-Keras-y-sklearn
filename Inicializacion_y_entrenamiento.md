# Inicializacion y entrenamiento

A traves de las investigaciones se ha demostrado que inicializar los pesos de las redes repercute en un buen entrenamiento.

No es lo mismo inicializar todo en 0s o 1s, para eso y por defecto viene por defecto la tecnica mejor valorada

*Glorot* debido al investigador Xavier Glorot

Existe `glorot_uniform` y `glorot_normal`.

El descenso de gradiente permite disminuir el error al bjar la pendiente e intentar llevar el error a 0 por otro lado es importante tener en cuenta el Learning_rate(taza de aprendizaje) que es la magnitud con que se desciende en la gradiente. Un lr muy alto nunca convergera(Llegara a su punto minimo) ya que rebotara contra las paredes de los puntos minimos y un lr muy bajo se quedara corto en el entrenamiento, ya que dara pasos muy cortos y no llegara a un minimo local o global.
