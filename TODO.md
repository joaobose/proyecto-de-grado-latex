# Capitulo 5

- Modificar el resumen del capitulo 5 para que se refleje que lo que hizo es realmente el corazon del trabajo, en el sentido de que se logro implementar el algoritmo con los pocos recursos de computo y sobretodo, en concordancia con el entonrno de trabajo de ACSL.

# Capitulo 6

- Argumentar la presencia de un pequeño Bias en el dataset y como esto se amplifica por el hecho de que el dataset tiene 7 veces mas samples que el dataset original.

- Resaltar un poco en la explicacion de la comparación de costos que ese benchmark fue propuesto en este trabajo (voices de Gerardo).

---

- Si hace falta: Mencionar la posibilidad de problema de sintonizacion del controlador, mencionar limitaciones del controlador y la imposibilidad de realizar cambios o controlar el controlador a bajo nivel. Asi como tambien la presencia de un controlador proporcional improvisado que no es el mejor para el caso.

- Si hace falta: Mencionar la posibilidad de que es posible que se haya alcanzado un minimo local con respecto al dataset de 1 m/s (un minimo local en donde la politica solo va hacia la izquierda pues eso cubre la mayoria de los casos).

- Si hace falta: Agregar comparación entre simulación y realidad, quizas una combinación de las dos tablas.

- Si hace falta: Agregar más metricas para los vuelos, algo que permita evaluar las metricas. Quizas agregar el resto de graficas (las de velocidad, posicion, attitude, etc).

# Conclusion

- Importante agregar "que se resolvio" en la conclusion.

- Algo tiene que haberle quedado a ACSL, por ejemplo:

- Que se logro implementar el algoritmo en SOTEN y que si se logra realizar un finetune adecuado, se puede tener _ya funcionando_ un algoritmo de evasion de obstáculos.

- Que se Probó lo complicado que puede ser ejecutar aplicaciones con redes neuronales en un sistema embebido como lo es un dron ligero, y que sin embargo, se logro ejecutar satisfactoriamente.

- Que se vio lo sensible que son los algoritmos que utilizan redes neuronales a la calidad de los datos de entrenamiento, y que el metodo original no genera datasets buenos para velocidades relativamente lentas.

- Resaltar mucho (voice de Gerardo) todo esto

- Creo que esto se pudiera agregar luego de las recomendaciones a trabajos futuros, como un sort of "para finalizar, es importante resaltar que este trabajo adicionalmente logro..."
