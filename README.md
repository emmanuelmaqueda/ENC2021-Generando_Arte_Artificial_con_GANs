# ENC2021 Generando Arte Artificial con GAN's

  
## [Tutorial ENC2021](http://computo.fismat.umich.mx/enc2021/tutoriales/GAN.pdf)

![image](https://user-images.githubusercontent.com/64985126/127394241-6ce7df81-02b3-4c85-909a-0bbdf0043086.png)
![image](https://user-images.githubusercontent.com/64985126/127394299-dbc93063-b790-4731-aba5-e1f94bc2fc44.png)

## Introducción

Las redes neuronales en general son una técnica de la IA la cuál se encuentra en auge en el
campo y son utilizadas usualmente, en especifico, las redes generativas adversarias (GANs) son
una técnica relativamente nueva la cuál tiene como finalidad (como su nombre lo indica)
generar nuevos datos (usualmente imágenes) a raíz de sus datos de entrenamiento los cuales
generalmente también son imágenes.
Las GANs se han usado en muchos aspectos como la generación de nuevas moléculas de
proteínas objetivo implicadas en el cáncer, la inflamación y la fibrosis, pueden reconstruir
modelos 3D de objetos a partir de imágenes, se usan para visualizar el efecto que tendrá el
cambio climático en sitios específicos o para simular apariencias de fotografías de rostros como
la senectud o el cambio de sexo, sin embargo una utilidad reciente y en tendencia ha sido el
llamado arte artificial siendo sus creadores los artistas digitales, artistas contemporáneos que
se enfocan en la generación de nuevas obras artísticas a través de éste tipo de técnicas.
¿Cómo sería una nueva obra de Rembrandt? o ¿Cuál sería el resultado sí combináramos el
estilo de arte de Monet y Frida Kahlo?. Con un aproximado podemos responder a estas
preguntas alimentando el generador de una GAN con obras de Rembrandt o de Monet y Frida 
Kahlo y dando salida a imágenes nuevas a raíz de las iniciales. Lo mismo puede hacerse con
fotografías, con diseños etc.
[Más información](http://computo.fismat.umich.mx/enc2021/tutoriales/GAN.pdf)

## Instrucciones para los asistentes

<b> 1. Descargar el dataset </b>  

Para prepararse para el tutorial deberá tenerse descargado un dataset con el cúal se entrenará la red neuronal GAN, decidimos dar libertad en este sentido así que ponemos a disponibilidad dos conjuntos de datos para generación de imágenes: 

<b> 1.1 Monet Dataset</b>

Conjunto de aproximadamente 900 imágenes de obras artísticas de Monet junto con algunas fotografías de imágenes reales de paisajes. Con este dataset podremos generar imágenes artificiales de paisajes con el estilo artístico de Monet.

[Descargar](https://turing.iimas.unam.mx/~ivanvladimir/gans/monet.zip)

<b> 1.2 CelebA Dataset</b>

CelebFaces Attributes Dataset (CelebA) es un conjunto de datos de atributos faciales a gran escala con más de 200.000 imágenes de celebridades, esta es una versión reducida de dataset con alrededor de 1000 imagenes. Las imágenes de este conjunto de datos cubren grandes variaciones de pose y desorden de fondo. Con este dataset podremos generar imágenes de rostros artificialmente.

[Descargar](https://turing.iimas.unam.mx/~ivanvladimir/gans/celeba.zip)

<b> * Al tener descargado el archivo comprimido debe subirse dicho archivo a su Google Drive personal en una carpeta facilmente ubicable junto a la notebook 'Artificial_Art_GAN's' que esta en este Github (se recomienda crear una carpeta llamada en el directorio raíz 'data_tutorial' con la notebook y el archivo comprimido del dataset elegido</b>

<b> * Tener en cuenta que se requiere alrededor de 1.5 GB libres en su Google Drive personal</b>
