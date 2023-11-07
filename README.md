# Reconocimiento de gestos dinamicos en la lengua de señas Chilena

# Resumen 

La comunicación a través del uso de los gestos es uno de los métodos de comunicación más
importante para un sector de la población que sufren de dificultades auditivas, en concreto en
Chile esta lengua es llamada Lengua de señas Chilena. Podemos clasificar estos gestos en dos
grandes grupos, por una parte los gestos Estáticos, y por otra los dinámicos que implican un
movimiento en el espacio en un transcurso de tiempo. Hoy en día, en Chile, existen proyectos
dedicados a resolver el reconocimiento de los gestos de la LSCH, pero estas se concentran en los
gestos llamados estáticos.
En este proyecto se ofrece una solución para el reconocimiento de gestos dinámicos a través
del uso de modelos de aprendizaje automático aplicado a visión por computadora.
Para la recolección de los datos se usa una librería de google llamada Mediapipe Holistic que
permite tener puntos de referencia de varias partes de la mano y del cuerpo.
Los datos obtenidos se utilizan para reconocer los gestos dinámicos, esto por medio de Redes
neuronales recurrentes(RNNs). En el entrenamiento se consideraron diferentes configuraciones
de hiperparámetros.
La experimentación muestra que el modelo basado en GRU con dos capas de 64 neuronas logra una presión del conjunto de testeo del 95.67%, demostrando que es posible el reconocimiento
de señas dinámicas de la lengua de señas chilena.
Finalmente, esta solución plantea un aporte al desarrollo de mejores aplicaciones inclusivas
orientadas a un grupo de personas con dificultades auditivas.
Palabras Clave— Reconocimiento de gestos, Lengua de señas Chilena, LSCH, Redes Neuronales Recurrentes, RNNs.
