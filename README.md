# FacialRecognition

Reconocimiento de Emociones con Python y OpenCV

Este proyecto reconoce emociones usando la cámara de la computadora.
Funciona en tres pasos: captura, entrenamiento y reconocimiento.

1. Captura de datos
Este paso toma fotos del rostro para crear la base de datos.

¿Qué hace el programa?
Enciende la cámara.
Detecta tu rostro con Haar Cascade.
Recorta solo la cara.
Guarda muchas imágenes dentro de una carpeta con el nombre de la emoción (por ejemplo: Felicidad, Tristeza, Enojo, Sorpresa).

¿Para qué sirve?
Para que el sistema tenga suficientes ejemplos y pueda aprender cada emoción.

2. Entrenamiento del modelo
Esta parte enseña al programa a reconocer emociones usando las fotos guardadas.

¿Qué hace?
Lee todas las imágenes de cada emoción.
Les asigna una etiqueta (0, 1, 2, 3, etc.).
Entrena tres modelos:
EigenFaces
FisherFaces
LBPH
Guarda los modelos entrenados en archivos XML.

¿Para qué sirve?
Para que el sistema aprenda los patrones de cada emoción y pueda diferenciarlas más adelante.

3. Reconocimiento en tiempo real
Aquí es donde el proyecto muestra si realmente funciona.

¿Qué hace?
Activa la cámara.
Detecta tu rostro.
Lo compara con lo aprendido en el entrenamiento.

Muestra en pantalla qué emoción reconoce, por ejemplo:
Feliz, Triste, Enojado, Sorprendido.

![Image](https://github.com/user-attachments/assets/96465881-8796-4bf5-95e0-fad61aba70b9)
