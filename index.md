# Visión por Computadora 2024

Este es un curso introductorio a la visión computacional (CV). Haremos un recorrido por las técnicas estándar para el procesamiento de imágenes digitales, el diseño de filtros básicos y aplicaciones de transformaciones, las cuales sirvan como base para el desarrollo de aplicaciones inteligentes asociadas a imágenes.

Aprenderemos y estudiaremos los algoritmos más comunes para la detección, extracción y comparación de características. Abordaremos también el estudio geométrico de imágenes de una vista (*one-point-view*) y de dos vistas (*two-point-view*), y sus transformaciones asociadas. Estos algoritmos se utilizan para alinear y unir imágenes para crear una única imagen de una escena más grande, y para recrear escenas 3D a partir de imágenes planas.

Abordaremos también grandes temas como la clasificación y segmentación de imágenes, y estudiaremos los métodos actuales de aprendizaje automático para este objetivo, principalmente redes neuronales convolucionales. Abordaremos también temas como la detección de objetos en una imagen, así como estimación de movimiento y seguimiento de objetos con aprendizaje automático. Al final del curso y si el tiempo lo permite haremos un breve recorrido por metodologías y herramientas actuales de IA generativa, para producir imágenes a partir de descripciones.

El curso requiere madurez por parte del estudiante, pues se integran contenidos de muchos cursos de computación, matemática y estadística. Entre los prerrequisitos se encuentra tener un buen dominio de las técnicas vistas en los cursos de matemática discreta, grafos, álgebra lineal, programación y algoritmos, cálculo diferencial e integral, y estadística. 


# Programa del curso
<div id='id-programa'/>

[Programa del curso](programa/Programa-cv2024.pdf){:target="_blank"}

### Horario
<div id='id-horario'/>

* Martes, de 18:10 a 19:45 horas. Jueves, de 17:20 a 18:55 horas.

### Office Hours
<div id='id-office'/>

* Miércoles y viernes, de 19:00 a 20:00 horas, por solicitud del estudiante. También pueden enviar sus dudas por correo electrónico.


# Material del curso
<div id='id-material'/>

**No.**  | **Fecha**    | **Tópicos**                                                       | **Recursos**
-------- | ------------ | ----------------------------------------------------------------- |  -------------------------------------
01       | 09.01.2024   | Introducción. Ejemplos de tareas en CV y aplicaciones. <br/> [Aula 01](aulas/Aula01.pdf){:target="_blank"} | 
02       | 11.01.2024   | Tipos de imágenes: binarias, escala de grises, RGB.  | 
03       | 16.01.2024   | Transformaciones básicas. Histogramas. Conversión RGB a gris. Corrección gamma.  | 
04       | 18.01.2024   | Ecualización de histograma. Algoritmos de binarización: Otsu, Riddler-Calvard, local.  |
T1       | 18.01.2024   | [Lista 01](listas/lista01.pdf){:target="_blank"} <br/> **Fecha de Entrega: jueves 1 de febrero.** | [saigon.jpeg](listas/saigon.jpeg){:target="_blank"} [monkey.jpeg](listas/monkey.jpeg){:target="_blank"} [rice.jpg](listas/rice.jpg){:target="_blank"}
05       | 23.01.2024   | Otros algoritmos de binarización. Segmentación de imágenes usando $k$-means.  |
06       | 25.01.2024   | Comentarios sobre espacios de color, luminancia y cromaticidad.  |
07       | 30.01.2024   | Operadores Morfológicos. <br/> [Aula 06](aulas/Aula06.pdf){:target="_blank"} | González y Woods, Cap. 9.
08       | 01.02.2024   | Componentes Conexas. Operador *Hit or Miss*. <br/> | González y Woods, Cap. 9.
L1       | 01.02.2024   | [Lab 01](labs/lab01.pdf){:target="_blank"} <br/> **Fecha de Entrega: jueves 15 de febrero.** | [fingerprint.jpeg](labs/fingerprint.jpeg){:target="_blank"} [brain-scan.jpeg](labs/brain-scan.jpeg){:target="_blank"} [rice.jpg](labs/rice.jpg){:target="_blank"} [microscope.png](labs/microscope.png){:target="_blank"} [butterfly.jpeg](labs/butterfly.jpeg){:target="_blank"} [quetzalgris.png](labs/quetzalgris.png){:target="_blank"} [chestxray.jpeg](labs/chestxray.jpeg){:target="_blank"}
09       | 06.02.2024   | Filtros lineales. Convolución. Filtro de medias. | 
10       | 08.02.2024   | Filtros de Prewitt, Sobel y Laplace. Filtros de orden. | 
11       | 13.02.2024   | Filtros binarios. Correlación y detección de formas. <br/> | 
12       | 15.02.2024   | Transformada de Hough. <br/> | 
13       | 20.02.2024   | Transformada de Fourier en imágenes. <br/> | 
14       | 27.02.2024   | Filtros usando la transformada de Fourier. <br/> | 
15       | 29.02.2024   | Filtros de Gabor. Bancos de Filtros. <br/> | 
16       | 05.03.2024   | Filtros de Haar. Detección de objetos con método cascada. Algoritmo de Viola-Jones. | [Paper Viola-Jones (2001)](https://www.cs.cmu.edu/~efros/courses/LBMV07/Papers/viola-cvpr-01.pdf)){:target="_blank"}
17       | 07.03.2024   | Ejemplos de detección de caras y detección de personas. | 




# Proyectos
<div id='id-proj'/>

A lo largo del curso de desarrollarán varios proyectos, los cuales se indicarán más adelante.

## Proyecto 1
<div id='id-proj1'/>

**No.**  | **Fecha**    | **Tópicos**                                   | **Recursos**
-------- | ------------ | --------------------------------------------- |  -------------------------------------
 1       | 04.02.2024   | Proyecto 1 - *Angiogramas coronarios*.        | [Proyecto 1](proyectos/pr1/Proyecto1.pdf){:target="_blank"} <br/>  [database.zip](proyectos/pr1/database.zip){:target="_blank"} 
 2       | 29.02.2024   | Entrega del proyecto.                         | 

    
# Referencias
<div id='id-ref'/>

### Textos:

* [R. Szeliski (2022). *Computer Vision: Algorithms and Applications*.](http://library.lol/main/5B158374B784FA7FC9D6559B45352EA1){:target="_blank"}

### Otras Referencias:

* [D. Forsyth y J. Ponce (2011). *Computer Vision: A Modern Approach*.](http://library.lol/main/11030C8AE6B3351ACE96677C84FF5440){:target="_blank"}

* [R. Hartley y A. Zisserman (2004). *Multiple View Geometry in Computer Vsion*.](http://library.lol/main/14DABCC0A4E8122A553ECE1C75DDD694){:target="_blank"}

* [R. Gonzalez y R. Woods (2007). *Digital Image Processiong*. 3rd Edition](http://library.lol/main/D2A46CA990847C353EF18F0A4270A083){:target="_blank"}

* [R. Gonzalez y R. Woods (2018). *Digital Image Processiong*. 4th Edition](http://library.lol/main/033DDCB069E05B84F9D176DDD7455010){:target="_blank"}

---
