# clase-09-proyecto-mitad-semestre

## intsrucciones

* hacer login en GitHub.com
* entrar a este repositorio disponible en [https://github.com/aud5i022-2022-1/clase-09-proyecto-mitad-semestre](https://github.com/aud5i022-2022-1/clase-09-proyecto-mitad-semestre)
* hacer click en el botón "Fork" de este repositorio para copiarlo a tu cuenta personal.
* enviar el enlace de tu repositorio y la lista de integrantes a través de u-cursos al instructor.
* ahora puedes editar este archivo siguiendo este enlace [README.md](README.md) y haciendo click en el ícono de lápiz para editar.
* recomendación: grabar tus avances seguido, para que no pierdas tu avance, para esto, baja al final de la sección de edición, elige la opción " Commit directly to the main branch." luego haz click en el botón verde "Commit changes". repite esto cada vez que quieras grabar cambios.
* para subir imágenes, haz click en este enlace a la carpeta [imagenes/](imagenes/), luego haz click en el botón "Add files" y selecciona "Upload files". arrastra tus imágenes o añadelas con el enlace "choose your files". luego elige la opción "Commit directly to the main branch" y haz click en el botón verde "Commit changes"

## contenidos de este repositorio

* carpeta [codigo_arduino/](codigo_arduino/): carpeta para tener el codigo de tu proyecto
  * archivo [odigo_arduino/codigo_arduino.ino](codigo_arduino/codigo_arduino.ino) : debe incluir encabezado y comentarios describiendo tu proyecto
* carpeta [imagenes/](imagenes/): sube aquí las imágenes para tu proyecto.
  * archivo [/imagenes/00-ejemplo.jpg](/imagenes/00-ejemplo.jpg) como ejemplo.
* archivo [README.md](README.md)]: este mismo archivo, aquí escribe tus apuntes durante el proyecto.
* archivo [README.pdf](README.pdf): este archivo pero convertido a PDF, puedes borrarlo.

## ejemplos útiles

cada párrafo es una línea continua de texto. los puntos "." son para punto seguido.
esta línea está escrita en la siguiente línea en el archivo, pero se ve seguida a la anterior.

para hacer un nuevo párrafo, hay que dejar una línea en blanco entremedio.

* las
* listas
* son
* así
  * las sub-listas
  * son así
  * con dos espacios de indentación

los enlaces se hacen con corchetes y después paréntesis. el texto dentro de corchetes es lo que se ve en el enlace, y el texto dentro de paréntesis es dónde va ese enlace. les pido que sea el mismo texto. aquí ejemplos de enlaces a web y a otros archivos dentro de este repositorio.

* [https://www.wikipedia.org/](https://www.wikipedia.org/)
* [https://www.arduino.cc/](https://www.arduino.cc/)
* [imagenes/00-ejemplo.jpg](imagenes/00-ejemplo.jpg)
* [codigo_arduino/codigo_arduino.ino](codigo_arduino/codigo_arduino.ino)

para incluir imágenes que sean visibles en este documento, es igual que un enlace a una imagen, pero con un signo de exclamación antes de los corchetes "!", así:

![texto descripción de la foto](imagenes/00-ejemplo.jpg)

## borrador de muestra

a continuación les dejo un breve borrador con ejemplos, que si completan, tendrán todos los puntos de la pauta, suerte!

## Acerca de

Proyecto ARTE VISUAL DIGITAL: REPRESENTACION VIRTUAL DE DIODOS EMISORES DE LUZ

[Martes 10 de Mayo, 2022]

x Javier Burgos para aud5i022-2022-1. Diseño de interfaz eletrònica mediante Arduino - DOCENTE: Aaron Montoya Moraga - FAU.UCHILE -   

## Lista de materiales

* 1 Arduino Uno
* 1 protoboard
* 1 potenciómetro
* 1 pulsador
* 2 resistencias
* 3 leds (verde, rojo, azul)
* cables
* 

## armado de circuito

estos son los pasos para armar el circuito.

primero hacemos X y se ve así.

![texto descripción de la foto](imagenes/00-ejemplo.jpg)

después hacemos Y y se ve así.

![texto descripción de la foto](imagenes/00-ejemplo.jpg)

## Código para microcontrolador Arduino

El código está hecho para Arduino Uno, y está incluido el repositorio: [codigo_arduino/sketch_may10a.ino](codigo_arduino/sketch_may10a.ino).

-Código basado en:

ej_06_perilla_mapeo x montoyamoraga (v0.0.1 abril 2022): [https://github.com/montoyamoraga/aud5i022-2022-1/tree/main/clases/clase-05/ej_06_perilla_mapeo](https://github.com/montoyamoraga/aud5i022-2022-1/tree/main/clases/clase-05/ej_06_perilla_mapeo)

Recursos adicionales: 

* ej_02_pulsador_luz_intermitente_delay [https://github.com/montoyamoraga/aud5i022-2022-1/tree/main/clases/clase-05/ej_02_pulsador_luz_intermitente_delay](https://github.com/montoyamoraga/aud5i022-2022-1/tree/main/clases/clase-05/ej_02_pulsador_luz_intermitente_delay).
* ej_03_pulsador_luz_intermitente [https://github.com/montoyamoraga/aud5i022-2022-1/tree/main/clases/clase-05/ej_03_pulsador_luz_intermitente](https://github.com/montoyamoraga/aud5i022-2022-1/tree/main/clases/clase-05/ej_03_pulsador_luz_intermitente)
* Arduino.cc
  * [https://forum.arduino.cc/t/using-millis-for-timing-a-beginners-guide/483573](https://forum.arduino.cc/t/using-millis-for-timing-a-beginners-guide/483573)
  * [https://forum.arduino.cc/t/how-to-make-two-conditions-in-an-if-statement/202090](https://forum.arduino.cc/t/how-to-make-two-conditions-in-an-if-statement/202090)

PASOS:

Primero creamos las variables:

* pinEntrada / pin de lectura de informaciòn anàloga. (Potenciometro)
* pinBoton / pin de lectura de informacion analoga. (Pulsador)

* pinVER / pin para controlar led VERDE.
* pinRED / pin para controlar led ROJO.
* pinBLU / pin para controar led AZUL.

* estadoLED / variable para almacenar estado led.
* valorSensor / variable para almacenar valor de potenciometro.
* estadoBoton / variable para almacenar estado de pulsador.

* valorMin - ValorMax - rangoMin - rangoMax - valorMapeado / variables para mapeo de valores.

primero en setup() hacemos que los pines X e Y sean entradas digitales, el pin Z sea salida digital, y abrimos la comunicación serial.

luego en loop() leemos las entradas y usamos la salida Z para lograr prender una luz LED.

## conclusiones

en este proyecto tuvimos los siguientes aprendizajes: 

* botón pulsador
* circuito para 

lo más difícil de este proyecto fue bla. 

cometimos los siguientes errores durante el armado del circuito y en el código, y los solucionamos así y este error no lo supimos resolver.

este proyecto lo vemos como la base para lograr bla, nos hace pensar en bla, y nos gustaría expandirlo para 10 botones y mil luces y diez arduinos conectados por wifi.
