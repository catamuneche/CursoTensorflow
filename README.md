# CursoTensorflow
 Curso hecho para aprender TensorFlow, el framework de Google para Deep Learning
 
 * Perceptrón -> Neurona artificial 
 * Red Neuronal Artificial -> Unión de perceptrones, conjunto de neuronas conectadas entre si para transmitir señales.
     - La información de entrada atraviesa la red neuronal produciendo valores de salida.
     - Cada neurona artificial se conecta con otra mediante enlaces.
     - El valor de salida de la neurona se multiplica por el peso del enlace.
 * Función de Activación -> Sirve para definir el valor de salida en función de los datos de entrada.
     - Función de activación Sigmoide: Transforma los valores introducidos a una escala de valores entre 0 y 1.
     - Función de activación Tangente Hiperbólica (Tanh): Transforma los valores introducidos a una escala de valores de salida entre -1 y 1.
     - Función de activación Unidad Lineal Rectificada (ReLu): Transforma los valores introducidos, al máximo entre 0 y un valor positivo en la entrada. Si el valor es negativo, la salida es 0. Si el valor es positivo, la salida será el mismo valor de la entrada.
 * Función de Coste -> Sirve para evaluar el rendimiento de una neurona, mide qué distancia hay entre el valor estimado por la neurona y el valor real.
     - Función de Coste Cuadrático: Los errores se hacen más grandes por estar al cuadrado y ralentiza la velocidad de aprendizaje de la red neuronal.
     - Función de Entropía Cruzada: Cuando mayor es la diferencia entre el valor real y la predicción de la neurona, mayor será la rapidez de aprendizaje. 
 * Algoritmo del Gradiente Descendiente -> Algoritmo de optimización para encontrar el valor mínimo de una función de coste, es decir, encontrar el valor de los pesos exactos "W" en la red neuronal para que el valor de la función de coste "C" sea el valor mínimo posible.
 
 
