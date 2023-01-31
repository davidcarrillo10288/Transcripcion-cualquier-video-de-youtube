# TRANSCRIPCION DE CUALQUIER VIDEO DE YOUTUBE

![database Analytics andesearch](https://user-images.githubusercontent.com/104275645/213613840-04100249-44b5-4dda-8aa6-adcaa4fd7fb9.png)

Este proyecto, lo realicé con la finalidad de poder transcribir cualquier video de Youtube, en un formato de texto. La finalidad de este proyecto es poder colocar las transcripciones en los videos de Youtube.

# Primera Parte:

Para esto, utilizamos Python y sus librerias, principalmente pytube para descargar un video de una URL de YouTube y la libreria moviepy para convertir el video en un archivo de audio mp3, y luego de mp3 a wav. Si bien es cierto, en el proyecto, se observa que se instalan más librerias, estas fueron realizadas ya que el programa las pedia necesarias al correr el mismo.

Primero imprimimos las resoluciones disponibles del video, luego se le pregunta al usuario qué resolución desea utilizar para descargar el video. Despues de eso, se procede a descargar el video en la resolución seleccionada, en un formato .mp4; se convierte este archivo en uno de audio mp3. Finalmente, convertimos el archivo mp3 a un archivo wav. Se convierte en archivo wav, ya que esta extensión es necesaria para correrla en la segunda parte del programa, cuando realicemos el reconocimiento de voz.

# Segunda Parte:

En esta parte, se procede a realizar el reconocimiento de voz con la libreria de python SpeechRecognizer, la cual nos permitirá pasar el archivo de audio a texto. Tenemos que tener en cuenta, que esta libreria tiende a presentar errores cuando se le hace procesar archivos de audio extensos, mayores a 5 min. Por lo cual, decidimos particionar el audio a analizar en partes iguales de 2 min cada una, con lo cual el proceso  fue exitoso.

Nota:
Si consideras que se puede mejorar el archivo, no dudes en comentarme. Saludos

# ##NuncaParesdeAprender
