# Capitulo 5 y 6

- Modificar el resumen del capitulo 5 para que se refleje que lo que hizo es realmente el corazon del trabajo, en el sentido de que se logro implementar el algoritmo con los pocos recursos de computo y sobretodo, en concordancia con el entonrno de trabajo de ACSL.

- Antes de mostrar las pruebas, en donde se explican las configuraciones, recordar que la ejecucion esta limitada al plan xy.

- Agregar mas gráficas de las estadisticas de los vuelos (gráfica de caminos ejecutados simultáneos en donde se mencionan los N vuelos en simulación).

- Explicar o resaltar la limitacion del ACSL API para enviar velocidades angulares, explicar el control propocional improvisado.

- Colocar tablas para la comparación de los valores de la función de costo, adicionamente, profundizar un poco en la explicacion y de aporte en el benchmark (voices de Gerardo).

- Mejorar el caption de la cadena de figura 6.17 para que quede explicito que son parte de un mismo vuelo que termina en colision.

- Si es posible, agregar más metricas para los vuelos, algo que permita evaluar las metricas. Quizas agregar el resto de graficas (las de velocidad, posicion, attitude, etc).

- Para la figuras 6.28 y 6.29, reemplazar con grafica de los caminos ejecutados simultaneos. Quizas tambien, colocar una forma de vizualizar las desviaciones, quizas un histograma o un boxplot. Adicionalmente donde dice "mayor" o "menor" colocar el valor en metros. Revisar si despues de hacer estos cambios vale la pena concervar las figuras 6.28 y 6.29 o si se podrian eliminar.

- Para las graficas de la vida real, para cada secuencia de vuelo, luego de ver los screenshots, colocar la grafica top-down de la trayectoria. Alternativamente, colocar grafico x-y-z en funcion del tiempo.

- Agregar comparación entre simulación y realidad, quizas una combinación de las dos tablas.

# Conclusion

- Importante agregar "que se resolvio" en la conclusion.

- Algo tiene que haberle quedado a ACSL, por ejemplo:

- Que se logro implementar el algoritmo en SOTEN y que si se logra realizar un finetune adecuado, se puede tener _ya funcionando_ un algoritmo de evasion de obstaculos.

- Que se Probó lo complicado que puede ser ejecutar aplicaciones con redes neuronales en un sistema embebido como lo es un dron ligero, y que sin embargo, se logro ejecutar satisfactoriamente.

- Que se vio lo sensible que son los algoritmos que utilizan redes neuronales a la calidad de los datos de entrenamiento, y que el metodo original no genera datasets buenos para velocidades relativamente lentas.

- Resaltar mucho (voice de Gerardo) todo esto

- Creo que esto se pudiera agregar luego de las recomendaciones a trabajos futuros, como un sort of "para finalizar, es importante resaltar que este trabajo adicionalmente logro..."

# Con respecto al problema de solo ir hacia la izquierda

- Agregar tabla de comparación de la particion del dataset en _caminos que van hacia la izquierda_ y _caminos que no van hacia la izquierda_.

- Argumentar la presencia de un pequeño Bias en el dataset y como esto se amplifica por el hecho de que el dataset tiene 7 veces mas samples que el dataset original.

- Mencionar la posibilidad de problema de sintonizacion del controlador, mencionar limitaciones del controlador y la imposibilidad de realizar cambios o controlar el controlador a bajo nivel.

- Si hace falta: Mencionar la posibilidad de que es posible que se haya alcanzado un minimo local con respecto al dataset de 1 m/s (un minimo local en donde la politica solo va hacia la izquierda pues eso cubre la mayoria de los casos).
