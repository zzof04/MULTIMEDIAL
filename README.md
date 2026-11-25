<style>
  .markdown-body > h1:first-of-type,
  header h1,
  .site-title {
    display: none !important;
  }

  /* Fondo negro en todos los contenedores del tema */
  html, body, .wrapper, .container, .container-lg, .page-content, main, article,
  section, header, footer, .inner, .markdown-body, #main_content_wrap, #header_wrap {
    background-color: #000000 !important;
    color: #eaeaea !important;
  }

  body {
    font-size: 17px;
    line-height: 1.75;
  }

  /* Columna de lectura centrada */
  .wrapper, .container, .inner, main, article, section {
    max-width: 900px !important;
    width: auto !important;
    float: none !important;
    margin-left: auto !important;
    margin-right: auto !important;
    padding-left: 20px;
    padding-right: 20px;
  }

  /* Todo el texto visible sobre negro */
  h1, h2, h3, h4, h5, h6, p, li, strong, em {
    color: #eaeaea !important;
  }

  h2 {
    margin-top: 2.4em;
    padding-bottom: .3em;
    border-bottom: 1px solid rgba(255,255,255,0.18);
  }

  h3, h4 {
    margin-top: 1.8em;
  }

  a {
    color: #ff85b3 !important;
    word-break: break-all;
  }

  /* Imágenes: todas del mismo tamaño y con marco */
  img {
    display: block;
    width: 100%;
    max-width: 100%;
    height: auto;
    aspect-ratio: 16 / 9;
    object-fit: contain;
    background: #000;
    border: 1px solid rgba(255,255,255,0.14);
    border-radius: 10px;
    margin: 1.5em 0 .6em 0;
  }

  /* Cuadros de texto / código con transparencia */
  div.highlighter-rouge,
  div.highlighter-rouge .highlight,
  div.highlighter-rouge pre {
    background-color: rgba(255,255,255,0.07) !important;
    color: #f2f2f2 !important;
  }

  div.highlighter-rouge {
    border: 1px solid rgba(255,255,255,0.18);
    border-left: 4px solid #ff85b3;
    border-radius: 10px;
    margin: 1.5em 0;
    backdrop-filter: blur(6px);
  }

  div.highlighter-rouge pre {
    padding: 1em;
    border-radius: 8px;
    overflow-x: auto;
    white-space: pre-wrap;      /* las líneas largas se ven completas */
    word-break: break-word;
    font-size: 14px;
    line-height: 1.55;
  }

  div.highlighter-rouge code,
  div.highlighter-rouge pre code span {
    background: transparent !important;
    color: #f2f2f2 !important;
  }
</style>

<img src="https://raw.githubusercontent.com/zzof04/MULTIMEDIAL/refs/heads/main/img/Adobe%20Express%20-%20Grabaci%C3%B3n%20arbol.gif" width="1920" height="auto"/>

## <span style="color: pink;">MULTIMEDIAL</span>

#### Exploración creativa de arte, tecnología y medios digitales interactivos.

### Unidad I. Hipervínculo

1. [Mi primera página.(#1-mi-primera-p%C3%A1gina).<br>](https://github.com/zzof04/MULTIMEDIAL/blob/main/README.md#1-mi-primera-p%C3%A1gina)
2. Sitio Web 

### Unidad II. Programación visual creativa

1. Intro TouchDesigner
2. Ejercicios  
   2.1. link primeros ejercicios  
   2.2. L'system  
3. Proyecto Final  
   3.1. Espacio recorrible  
   3.2 Estrellas y el pasado  
4. Comfy desktop / prompt
   
## Unidad I

### Página y vínculos

#### 1. Mi primera página: 

```js
<!DOCTYPE html>
<!-- Indica al navegador que este documento usa HTML5 -->

<html>
<!-- Inicio del documento HTML -->

<head>
<!-- Sección donde van metadatos, título y estilos -->

<meta charset="UTF-8">
<!-- Define la codificación de caracteres para que se vean bien tildes y símbolos -->

<title>Multimedial</title>
<!-- Título de la página que aparece en la pestaña del navegador -->

<style>
/* Aquí comienza la sección de estilos CSS que define la apariencia visual */

body{
/* "body" se refiere a todo el contenido visible de la página */

  background-color: white;
  /* Define que el fondo de toda la página sea blanco */

  color: black;
  /* Define que el color del texto sea negro */

  margin: 0;
  /* Elimina los márgenes que los navegadores agregan por defecto */

  height: 100vh;
  /* Hace que el alto del cuerpo sea igual al 100% de la altura de la pantalla */

  display: flex;
  /* Activa el sistema Flexbox para organizar y centrar elementos */

  justify-content: center;
  /* Centra el contenido horizontalmente */

  align-items: center;
  /* Centra el contenido verticalmente */

  font-family: Arial, sans-serif;
  /* Define la tipografía del texto */

  font-size: 60px;
  /* Define el tamaño grande del texto */

}
/* Fin de las reglas de estilo del body */

</style>
<!-- Fin de la sección de estilos -->

</head>
<!-- Fin de la sección head -->

<body>
<!-- Inicio del contenido visible de la página -->

MULTIMEDIAL
<!-- Texto que aparece en el centro de la pantalla -->

</body>
<!-- Fin del contenido visible -->

</html>
<!-- Fin del documento HTML -->
```

#### 2. Resultados página Web

[ https://zzof04.github.io/MULTIMEDIAL/w/index.html](https://zzof04.github.io/MULTIMEDIAL/w/index.html)  

## Unidad II

### Introducción a TouchDesigner.

#### Link drive primeros ejercicios.

[https://drive.google.com/drive/folders/1H-1MCiFf7Ah3RitZw5CoLaFOJG1MuUVW?usp=drive_link](https://drive.google.com/drive/folders/1H-1MCiFf7Ah3RitZw5CoLaFOJG1MuUVW?usp=drive_link) 

```text 
Comenzamos conociendo herramientas y nodos básicos como el TOP, CHOP, además de integrar sliders y botones como herramientas de interacción. Personalmente experimenté con imágenes que ya poseía, agregándole filtros de imágenes del programa y nodos para la creación de una figura reactiva al sonido. Quise seguir desarrollando mi temática enfocada en la unión entre arte y ciencia, específicamente la astronomía. 
```
<img src="https://github.com/zzof04/MULTIMEDIAL/blob/main/img/Proyecto1.png?raw=true" width="auto" height="auto"/> Ejercicio inicial

En paralelo al taller quise desarrollar mi proyecto de grado. Esto con el fin de llegar a un cruce entre arte, ciencia y cómo este dialoga con la tecnología, espacio y espectador. 
Integré al proyecto un sensor ultrasónico conectado a un Arduino, con el fin de darle al cuerpo del espectador un rol activo que altera la visualidad de la obra.  

<img src="https://raw.githubusercontent.com/zzof04/MULTIMEDIAL/refs/heads/main/img/2026-06-25_195215.jpg" width="auto" height="auto"/> Storyboard

<img src="https://raw.githubusercontent.com/zzof04/MULTIMEDIAL/refs/heads/main/img/IMG_0994%20(1).jpg" width="auto" height="auto"/> Instalación, sala 31.
Proyector, computador con conexión a arduino + sensor

<img src="https://raw.githubusercontent.com/zzof04/MULTIMEDIAL/refs/heads/main/img/IMG_0924.jpg" width="auto" height="auto"/> Conexión sensor ultrasónico

<img src="https://raw.githubusercontent.com/zzof04/MULTIMEDIAL/refs/heads/main/img/Adobe%20Express%20-%20IMG_1005.gif" width="auto" height="auto"/> 


### Ejercicios.

#### 1. L'system

<img src="https://raw.githubusercontent.com/zzof04/MULTIMEDIAL/refs/heads/main/img/IMG_2801.PNG" width="auto" height="auto"/> 

<img src="https://raw.githubusercontent.com/zzof04/MULTIMEDIAL/refs/heads/main/img/IMG_2799.PNG" width="auto" height="auto"/> 

#### Link Drive
[https://drive.google.com/drive/folders/1e38di-CiK1ChWk6DJTIdB44sNnNaRe1O?usp=drive_link ](https://drive.google.com/drive/folders/1e38di-CiK1ChWk6DJTIdB44sNnNaRe1O?usp=drive_link)

#### 2. Desarrollo proyecto final
El desarrollo del proyecto anterior me permitió entender la dimension tecnológica de mi proyecto de tesis.
La integración del sensor ultrasónico al TouchDesiner significó un desafío tecnico que debia comprender: ¿Cómo funciona un sensor?, ¿cómo lo conecto al programa?, ¿cual será su disposición en el montaje? Sin embargo, si bien usaba imágenes que ludían al cosmos estas no tenian un significado más allá de su función electronica y visual. Me pregunté qué era lo que realmente quería contar.

##

#### Espacio recorrible.

Una de las cosas que llamó mi atención del ejercicio del L'system era su visualidad en el espacio "vacio", además que el ejercicio contaba con un nodo "camera" que permitía cambiar la visualidad del objeto en el render. 

Esta cualidad hizo que me preguntara por el recorrido tridimensional del objeto y pensar en este mismo como respuesta a la interacción del espectador en la obra. ¿Que pasa si le entrego el control de recorrido al espectador dentro de un espacio digital? Aún sin llegar a la visualidad del proyecto, decidí aprender cómo podía materializar mi idea: 

#### 1: como primer paso, debía conectar un joystick conectado a arduino a la cámara que controlaba la visualidad del render, con el fín de controlar a tiempo real el recorrido tridimensional.

Con la ayuda de Claude, se creó este código: 

```text
import math

def onFrameStart(frame):
    cam = op('/project1/container1/cam_main1')
    joy = op('/project1/sys_input/joy_raw_chop')

    if me.fetch('inicializado', False) is False:
        me.store('heading', 0.0)
        me.store('pitch', 0.0)
        me.store('smoothX', 0.0)
        me.store('smoothY', 0.0)
        me.store('centerOffsetX', 0.0)
        me.store('centerOffsetY', 0.0)
        me.store('calibrando', True)
        me.store('calibFrames', 0)
        me.store('calibSumX', 0.0)
        me.store('calibSumY', 0.0)
        me.store('posX', 0.0)
        me.store('posY', 2.0)
        me.store('posZ', -6.0)
        me.store('inicializado', True)
        return

    rawX = joy['x'][0]
    rawY = joy['y'][0]
    btnA = joy['a'][0] > 0.5
    btnB = joy['b'][0] > 0.5
    btnC = joy['c'][0] > 0.5
    btnD = joy['d'][0] > 0.5

    mapX = (rawX - 0) / (1023 - 0) * (1 - (-1)) + (-1)
    mapY = (rawY - 0) / (1023 - 0) * (1 - (-1)) + (-1)

    calibMax = 40
    if me.fetch('calibrando'):
        me.store('calibSumX', me.fetch('calibSumX') + mapX)
        me.store('calibSumY', me.fetch('calibSumY') + mapY)
        cf = me.fetch('calibFrames') + 1
        me.store('calibFrames', cf)
        if cf >= calibMax:
            me.store('centerOffsetX', me.fetch('calibSumX') / cf)
            me.store('centerOffsetY', me.fetch('calibSumY') / cf)
            me.store('calibrando', False)
        joyX, joyY = 0, 0
    else:
        joyX = aplicarRespuesta(mapX - me.fetch('centerOffsetX'))
        joyY = aplicarRespuesta(mapY - me.fetch('centerOffsetY'))

    lookSmoothing = 0.10
    smoothX = me.fetch('smoothX') + (joyX - me.fetch('smoothX')) * lookSmoothing
    smoothY = me.fetch('smoothY') + (joyY - me.fetch('smoothY')) * lookSmoothing
    me.store('smoothX', smoothX)
    me.store('smoothY', smoothY)

    turnSpeed = 1.2
    heading = me.fetch('heading') + smoothX * turnSpeed
    pitch = me.fetch('pitch') - smoothY * turnSpeed
    pitch = max(-75, min(75, pitch))
    me.store('heading', heading)
    me.store('pitch', pitch)

    moveSpeed = 0.03
    rad = math.radians(heading)
    rightX = math.cos(rad)
    rightZ = -math.sin(rad)

    targetVertical = (1 if btnA else 0) - (1 if btnC else 0)
    targetStrafe = (1 if btnB else 0) - (1 if btnD else 0)

    posX = me.fetch('posX') + rightX * targetStrafe * moveSpeed
    posZ = me.fetch('posZ') + rightZ * targetStrafe * moveSpeed
    posY = me.fetch('posY') + targetVertical * moveSpeed

    me.store('posX', posX)
    me.store('posY', posY)
    me.store('posZ', posZ)

    cam.par.rx = pitch
    cam.par.ry = heading
    cam.par.tx = posX
    cam.par.ty = posY
    cam.par.tz = posZ


    return


def aplicarRespuesta(v):
    deadzone = 0.07
    curve = 1.6
    if abs(v) < deadzone:
        return 0
    signo = -1 if v < 0 else 1
    mag = (abs(v) - deadzone) / (1 - deadzone)
    mag = max(0, min(1, mag))
    mag = mag ** curve
    return signo * mag
```
<img src="https://raw.githubusercontent.com/zzof04/MULTIMEDIAL/refs/heads/main/img/IMG_1424.jpg" width="500" height="auto"/> 

Joystick Shield

<img src="https://raw.githubusercontent.com/zzof04/MULTIMEDIAL/refs/heads/main/img/Adobe%20Express%20-%20Grabaci%C3%B3n%20arbol.gif" width="1920" height="auto"/> 

#### 2. Con el control técnicamente ya armado, mi próximo paso fue integrar más "objetos" dentro el espacio digital:

<img src="https://raw.githubusercontent.com/zzof04/MULTIMEDIAL/refs/heads/main/img/3A14A8B0-E3CD-465B-934A-E1FCE48B09FF.jpg" width="400" height="auto"/> 

##
#### Estrellas y el pasado.

El desarrollo poético de la obra me hizo replantear mi mirada sobre el cosmos. 

El universo y mis ganas por representarlo me llevaron a mi punto de partida, mi hogar de origen gracias a la pregunta de mi tio hace más de ocho años: ¿sabías que cuando miramos las estrellas, realmente vemos la luz de su pasado? a raíz de esto, me pregunté por aquella distancia y el tiempo que separa al observador. Tanto la luz de una estrella como mi casa natal son un pasado que aún llega hasta mi. 

Mi casa natal se manifiesta de forma intangible, a través del recuerdo, los sueños, el recuerdo. Metodológicamente, necesitaba encontrar una manera de volver a recorrer aquellos recuerdos, es por esto, que di con una aplicación llamada Scaniverse, una plataforma inmersiva que permite, gracias a la tecnología LiDAR, escanear espacios y objetos físicos y llevarlos a modelos 3D detallados y de alta resolución. Su carácter gratuito y su facilidad de manejo me permitieron compartirla con alguien en mi ciudad natal. Para recolectar estos espacios, mi amiga de la infancia se dio la tarea de realizar un recorrido y habitar los mismos espacios que yo frecuentaba, escaneando pasillos, esculturas, espacios, etc, cada uno cargado de significado emocional y biográfico. 

Una de las características visuales que posee esta herramienta, es que los escáner no siempre quedan perfectos, hay partes que se fragmentan, datos que se pierden generando una imagen incompleta. Lejos de significar un error, lo tomo como una cualidad visual clave.

<img src="https://raw.githubusercontent.com/zzof04/MULTIMEDIAL/refs/heads/main/img/IMG_2625.PNG" width="400" height="auto"/> 

Escaner "casa" (scaniverse)

<img src="https://raw.githubusercontent.com/zzof04/MULTIMEDIAL/refs/heads/main/img/f44b1017-97cf-443d-bbcf-1919172351de.jpg" width="400" height="auto"/> 

Escaner "fuente" (scaniverse)

Estos escáner son exportados en el formato PLY, un formato de archivo 3D que almacena objetos gráficos en una colección de vértices, caras e incluso propiedades de color que luego son leídos en el programa TouchDesigner y traducidos a un sistema de puntos. En este paso, los lugares físicos se vuelven un dato programable que luego pasan a imagen. 

<img src="https://raw.githubusercontent.com/zzof04/MULTIMEDIAL/refs/heads/main/img/IMG_2795.PNG" width="700" height="auto"/> 

<img src="https://github.com/zzof04/MULTIMEDIAL/blob/main/img/Grabaci%C3%B3n%20espacio.gif?raw=true" width="700" height="auto"/> 


#### 3. Comfy desktop / prompt

Aprendimos el uso del programa Comfy Desktop para la creación de imágenes con inteligencia artificial. Con el fin de crear visuales que inspiren nuestros proyectos en TouchDesigner, además de visualizar opciones de montaje, bocetos, etc. 
Para mi proyecto, decidí generar opciones de montaje. Le pedí a la ia (Claude) la creación de las imágenes adjuntando los bocetos de referencia hechos a mano:

```text
A partir de las imágenes de referencia crea una imagen realista de cada una considerando: los bocetos se tratan de una instalación artística donde se proyecta, a oscuras, un proyecto visual en una sala blanca rectangular. Las imágenes que se proyectan corresponden a espacios físicos tridimensionales llevados a un sistema de puntos que resalta en contraste con el espacio oscuro, como la referencia. Estos se encuentran en un espacio digital mediado por el programa Touchdesigner.
En la imagen 1, se muestra esta proyección cubriendo todo el espacio de la pared en vista frontal. Al frente, se sitúa un plinto donde descansa un joystick conectado a Arduino a la altura óptima donde el espectador sea capaz de manipularlo. En la segunda imagen se muestra la proyección hacia una esquina de la sala, enfocando el proyector y el monitor donde corre el programa Touchdesigner.
```

Me arrojó 2 prompts que luego pasé por Gémini:

#### imagen 1: 
```text
Photorealistic interior photograph of a minimalist rectangular white gallery
room, completely dark, front view centered on the back wall. The entire wall is
covered by a large projection of a 3D point cloud: thousands of tiny glowing white
and slightly iridescent dots forming volumetric architectural spaces and organic
shapes, like a LiDAR or photogrammetry scan, sharp contrast against the black. In
the foreground, centered, a slim white plinth at waist height with an arcade-style
joystick connected to an Arduino board with thin wires, softly lit by the spill light of the
projection. Floor reflects faint dots of light. Symmetrical one-point perspective,
cinematic, long exposure, ultra-detailed, 35mm, f/2.8, contemporary art installation
documentation.
```
<img src="https://raw.githubusercontent.com/zzof04/MULTIMEDIAL/refs/heads/main/img/IMG_2442.PNG" width="auto" height="auto"/> imagen generada en Comfy desktop

#### imagen 2: 
```text
Photorealistic photograph of the corner of a dark white-walled exhibition
room, wide angle. A point-cloud projection of 3D scanned spaces (glowing white dots
on black) wraps across both walls of the corner, continuing seamlessly over the
vertical edge. A video projector sits on a low table in the foreground, emitting a
visible light beam through light haze, next to a desktop monitor and keyboard
running TouchDesigner, showing a node network with connected rectangular
operators, its screen glow lighting the table. Dark ceiling with a visible grid. Moody,
low-light, cinematic, high contrast, art installation documentation photo, 24mm lens.
```

<img src="https://raw.githubusercontent.com/zzof04/MULTIMEDIAL/refs/heads/main/img/IMG_2443.PNG" width="auto" height="auto"/> imagen generada en Comfy desktop
