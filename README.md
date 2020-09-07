# teachablemachine: ¨applications on mapping¨

Imagine a ** [IA] (https://towardsdatascience.com/search?q=Artificial%20inteligent) ** model that automatically classifies any ** path or path of a river or drainage ** by simply looking at a map or satellite image:

<img src='./img/777-min.gif' alt='Logo Head' align='center' width='30%'></img>
<br>

This is a simple example developed in ** [Teachable Machine] (https://teachablemachine.withgoogle.com/) ** that shows the quick way to create a deep learning model [Deep learning mapping] (https: // towardsdatascience .com / deep-learning-for-visual-searches-and-mapping-89b85061ef9e) or automatic in geographic applications.
** Teachable Machine ** is a web-based tool that makes it possible to create machine learning models quickly.
## How does it work:

<img src='./img/Captura2.PNG' alt='how' align='center' width='70%'></img>
<br>

The model works from a series of images of rivers and roads preloaded on layers of [OPS] (https://blog.openstreetmap.org/category/operations/) (openstreetmap), which serve to train a model of * * [IA] (https://towardsdatascience.com/search?q=Artificial%20inteligent) ** which performs for each dataset an analysis in 50 cycles or epochs, with iterations every 16 images, which allows you to classify images in two classes:
* 1. Rivers
* 2. Ways

The model can classify any image using files from your PC or your webcam as input data.

<img src='./img/Captura.PNG' alt='class' align='center' width='70%'></img>
<br>

## Example link:

**[script OPS](https://teachablemachine.withgoogle.com/models/dhroGiDRg/)**
    
## Descarga del modelo:
This model trained under layers of [OPS] (https://blog.openstreetmap.org/category/operations/) was developed under [TensorFlow.js] (https://www.tensorflow.org/js?hl=es- 419) that works anywhere with javascript. Therefore, it is perfectly compatible with tools such as [Glitch] (https://glitch.com/), [P5.js] (https://p5js.org/), [Node.js] (https: // nodejs .org / en /) and many others. you can download it here:
* [Script] (https://github.com/Alexanderariza/teachablemachine/blob/master/model.json)

----------------------------------------------------
<div>Teachable Machine Image Model</div>
<button type="button" onclick="init()">Start</button>
<div id="webcam-container"></div>
<div id="label-container"></div>
<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@1.3.1/dist/tf.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@teachablemachine/image@0.8/dist/teachablemachine-image.min.js"></script>
<script type="text/javascript">
    // More API functions here:
    // https://github.com/googlecreativelab/teachablemachine-community/tree/master/libraries/image
 
--------------------------------------------------------------------------------------------------

# teachablemachine: ¨aplicaciones sobre mapas¨

Imagine un modelo de **[IA](https://towardsdatascience.com/search?q=Artificial%20inteligent)** que clasifique de manera automática cualquier **vía o camino de un rio o drenaje** al mirar simplemente un mapa o imagen de satélite: 

<img src='./img/777-min.gif' alt='Logo Head' align='center' width='30%'></img>
<br>

Este es un ejemplo sencillo desarrollado en **[Teachable Machine](https://teachablemachine.withgoogle.com/)** que muestra la forma rápida de crear un modelo de aprendizaje profundo [Deep learning mapping](https://towardsdatascience.com/deep-learning-for-visual-searches-and-mapping-89b85061ef9e) o automático en aplicaciones geográficas.
**Teachable Machine** es una herramienta basada en la Web que hace posible crear modelos de aprendizaje automático de manera rápida.
## Como funciona:

<img src='./img/Captura2.PNG' alt='how' align='center' width='70%'></img>
<br>

El modelo funciona a partir de una serie de imágenes de ríos y caminos precargados sobre capas de [OPS](https://blog.openstreetmap.org/category/operations/) (openstreetmap), que sirven para entrenar a un modelo de **[IA](https://towardsdatascience.com/search?q=Artificial%20inteligent)** el cual realiza para cada conjunto de datos un análisis en 50 ciclos o épocas, con iteraciones cada 16 imágenes, lo que le permite clasificar imágenes en dos clases:
* 1. Rios
* 2. Vias

El modelo puede clasificar cualquier imagen utilizando para ello archivos de tu PC o tu webcam como datos de entrada.

<img src='./img/Captura.PNG' alt='class' align='center' width='70%'></img>
<br>

## Enlace de ejemplo:

**[script OPS](https://teachablemachine.withgoogle.com/models/dhroGiDRg/)**
    
## Descarga del modelo:
Este modelo entrenado bajo capas de [OPS](https://blog.openstreetmap.org/category/operations/) fue desarrolado bajo [TensorFlow.js](https://www.tensorflow.org/js?hl=es-419) que funciona en cualquier sitio con javascript. Por tanto, es perfectamente compatible con herramientas como [Glitch](https://glitch.com/), [P5.js](https://p5js.org/), [Node.js](https://nodejs.org/es/) y muchas otras. puedes descargarlo aqui:
* [Script](https://github.com/Alexanderariza/teachablemachine/blob/master/model.json)

----------------------------------------------------
<div>Teachable Machine Image Model</div>
<button type="button" onclick="init()">Start</button>
<div id="webcam-container"></div>
<div id="label-container"></div>
<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@1.3.1/dist/tf.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@teachablemachine/image@0.8/dist/teachablemachine-image.min.js"></script>
<script type="text/javascript">
    // More API functions here:
    // https://github.com/googlecreativelab/teachablemachine-community/tree/master/libraries/image
 
--------------------------------------------------------------------------------------------------
