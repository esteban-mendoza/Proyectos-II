# Proyectos II
*Introducción a las redes neuronales y el aprendizaje profundo*

Aquí estaremos principalmente subiendo todos los códigos y herramientas de software que usaremos durante el curso.

## Bitácora

### Semana 1 (Antecedentes).
Paradigamas de aprendizaje, perceptrón e introducción a Pytorch.
### Semana 2 (Introducción a las redes neuronales artificiales). 
  * Redes neuronales completamente conectadas unidireccionales.
  * Comentario de teorema de aproximación universal.
  * Propagación hacia adelante (*forward pass*)
  * Comentario de propagación de errores hacia atrás (*backpropagation*)
  * *Batch* vs *Stochastic* vs *Mini-batch*.
  * Función objetivo.
  * Primer ejemplo de clasificación multiclase en pytorch (primera parte).
### Semana 3 (Algoritmos de optimización).
  * Lunes 4 de octubre: Primer ejemplo de clasificación multiclase en pytorch (segunda parte).
  * Miércoles 6 de octubre: *Momentum*, *Adagrad* y *Adadelta*.
  * Viernes 8 de octubre: *RMSProp*, *Adam* y *Nesterov* (semana 4).
### Semana 4 (Regularización de redes).
  * Lunes 11 de octubre: *Capacity* (Flexibilidad del modelo), *Underfitting vs Overfitting*.
  * Miércoles 13 de octubre: Penalización de parámetros, regularización L^2 (primera parte).
  * Viernes 15 de octubre: Regularización (segunda parte), *Dropout*, ejemplo de regularización en pytorch.
### Semana 5 (Redes convolucionales 2D [CNN 2D]).
  * Lunes 18 de octubre: Motivación, representación de imágenes digitalizadas(RGB).  
  * Miércoles 20 de octubre: Definición de capas convolucionales para imágenes con uno y C canales, ejemplos.
  * Viernes 22 de octubre: *Padding, Stride*, operador *Pooling*, comentario sobre LeNet y clasificación de digitos usando LeNet.
### Semana 6 (Redes convolucionales).
  * Lunes 25 de octubre: Clasificación binaria *dogs vs cats* en Pytorch.
  * Miércoles 27 de octubre: Regularización de CNNs (*Transfer learning*, *Data augmentation*), congelamiento de capas y *fine tuning*.
  * Viernes 29 de octubre: Ejemplo de redes convolucionales en 1D, *batch normalization*
### Semana 7 (Redes recurrentes [RNN]).
  * Miércoles 3 de noviembre: Motivación, datos secuenciales, arquitectura: *input*, *output*, *hidden unit*; tipos de flujo de información.
  * Viernes 5 de noviembre: Unidad *Long short term memory*. 
### Semana 8 (Exposiciones parte I).
  * Miércoles 10 de noviembre (Hendrix): Introducción al aprendizaje por refuerzo.
  * Viernes 12 de noviembre (Montserrat): Autoencoders & ClusterNet.
### Semana 9 (Exposiciones parte II).
  * Miércoles 17 de noviembre (Raúl): ResNet.
  * Viernes 19 de noviembre (Ivana): *Bidirectional* RNNs & *Gated recurrent units*. 
### Semana 10 (Exposiciones parte III).
  * Lunes 22 de noviembre (Pendiente): *Backpropagation through time*
  * Miércoles 24 de noviembre (Pendiente): *Deep Q-Networks*
  * Viernes 26 de noviembre (Daniel): *Denoising Autoencoders*
### Semana 11 (Exposiciones parte IV).
  * Lunes 29 de noviembre (Diego): Deep Q-Networks.
  * Miércoles 1 de diciembre (Roberto): Pendiente
  * Viernes 3 de diciembre (Jorge): *Backpropagation through time* (BPTT).
### Semana 12 (Exposiciones parte V)
  * Lunes 6 de diciembre (Itzel): Introducción a la redes generativas antagónicas (GANs).
  * Miércoles 8 de diciembre: Inicio de asesorías para desarrollar el trabajo final.
  
## Software
Ocuparemos Python3 para los códigos que haremos, salvo que lo mencionemos, sugiero instalar la **versión 3.9.7**. A continuación dejo la las bibliotecas que estaremos usando:

* ``torch==1.9.0``
* ``jupyter==1.0.0``
* ``matplotlib==3.4.3``
* ``torchvision==0.10.1``
* ``tqdm==4.62.3``

**Nota:** Esta lista se va a ir actualizando conforme avance el curso. La versión que aparece es la que estoy manejando - Sergio.

También puden ejectuar el siguiente comando en la terminal dentro del repositorio.

``pip3 install -r requirements.txt``

### Colab 
*Proximamente*

## Bibliografía

Para la parte práctica recomendamos revisar los libros de autores **Stevens** y **Zhang**. El primero explica de manera sencilla los conceptos y comandos de Pytorch. El segundo combina la parte práctica de Pytorch con algunos aspectos teóricos de *Deep Learning*, también incluye en la parte final los temas que los estudiantes deben saber para introducirse a DL. 

Para empezar a estudiar *machine learning* desde un punto de vista matemático recomiendo seguir el libro de autor **Deisenroth**, lo más importante para nuestro curso son los capítulos 5 *Vector Calculus* y 7 *Continuos Optimization*. Para profundizar en aspectos teóricos de las redes neuronales y *machine learning* es buena opción empezar con el **Bishop**.

El libro de autor Dawani esta muy condensado, pero introduce a DL desde una perspectiva matemática, tiene muy buena notación y menciona los temas antecedentes, es bastante intuitivo para los que tenemos formación matemática. El Goodfellow es un poco más pesado de leer, pero también aborda bastantes temas interesantes para el área.

El curso [DEEP LEARNING](https://atcold.github.io/pytorch-Deep-Learning/) de **Yann LeCun** y **Alfredo Canziani** también se ve muy completo y tiene una versión en español.

Si alguien prefiere trabajar con una herramienta más sencilla que Pytorch una buena opción es Keras y en ese caso recomiendo seguir el libro de **Chollet**. No vienen muchas matemáticas, pero la parte práctica esta muy completa.

### Pytorch:
* Stevens, E., Antiga, L. (2019). [*Deep Learning with Pytorch*](https://pytorch.org/assets/deep-learning/Deep-Learning-with-PyTorch.pdf). Manning.
* Zhang, A., Lipton, Z. C., Li, M., Smola A. J.(2020). [*Dive into Deep Learning*](https://d2l.ai).IA.

### Matemáticas para *machine learning*:
* Deisenroth, M. P., Faisal, A. A., Ong, C. S. (2020). [*Mathematics for Machine Learning*](https://mml-book.github.io/book/mml-book.pdf)
* Bishop, Christopher M. (2006). [*Pattern Recognition and Machine Learning*](http://users.isr.ist.utl.pt/~wurmd/Livros/school/Bishop%20-%20Pattern%20Recognition%20And%20Machine%20Learning%20-%20Springer%20%202006.pdf). Springer.

### Matemáticas para *deep learning*:
* Dawani, Jay. (2020). *Hands-On Mathematics for Deep Learning*. Packt Publishing
* Goodfellow, I., Bengio, Y., and Courville A. (2016). [*Deep Learning*](https://www.deeplearningbook.org). MIT Press().
* Zhang, A., Lipton, Z. C., Li, M., Smola A. J.(2020). [*Dive into Deep Learning*](https://d2l.ai).IA.

### Keras
* François Chollet. (2018). [*Deep Learning with Python*](https://tanthiamhuat.files.wordpress.com/2018/03/deeplearningwithpython.pdf). Manning.

### Physics-based Deep Learning:
* Thuerey, N., Hol, P., Mueller M., Schnell, P., Trost, F., Um, K. (2021). [*Physics-based Deep Learning*](https://physicsbaseddeeplearning.org). WWW.


