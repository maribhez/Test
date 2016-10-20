#Ejercicios Tema 2. 

## 

###Ejericicio 1.

Instalar alguno de los entornos virutales de node.js (o de cualquier otro lenguaje con el que esté familiarizado) y, con ellos, instalar la última versión existente, la versión minor más actual de la 4.x y lo mismo para la 0.11 o alguna impar (de desarrollo).

- ***NVM - Node Version Maganer (Gestor de versiones de Node).***


Tal y como su nombre indica, se encarga de controlar diferentes versiones en un mismo ambiente, dejando cada una completamente aislada de las otras. Se puede llevar a cabo lo pedido en este ejercicio gracias a estas prestaciones: tener instaladas Node v0.4 y v.011 ejecutándolas según nuestras necesidades.

Nota: Adjuntar fotografía instalación y comprobación.

![Instalación NVM]([IMG]http://i345.photobucket.com/albums/p391/maribhez/instalacionNMV_zps5syy2rus.png[/IMG] "Instalación NVM.")

![Comprobación de instalación correcta]([IMG]http://i345.photobucket.com/albums/p391/maribhez/comprobacionInstalacionCorrecta_zpsdh2jeky5.png[/IMG] "Comprobación de instalación correcta.")

Ahora, después de la instalación del entorno virtual hay que pasar a instalar los lenguajes. Es necesario un paso previo, por supuesto, pues hay que comprobar cuáles son las versiones existentes para saber cuál es la última y proceder a su instalar. Así, ejecutamos el comando **nvm ls-remote**, y vemos que las versiones que vamos a instalar son *"v0.11.16"* y *v4.6.1* con **nvm install version**, siendo *version* la escogida por el usuario.

Después de documentarme para la realización de este ejercicio he visto que añadiendo la opción *-s* a nuestro comando permitimos la personalización posterior de la compilación de nuestro código, siendo por eso por lo que esta opción aparece sólo en una de las instalaciones. 

Después de la segunda instalación se quedará esta versión marcada como *versión por defecto*, pero basta ejecutar **"nvm use version"** para marcar *version* como principal. 



![Instalación versión v0.11.16]([IMG]http://i345.photobucket.com/albums/p391/maribhez/instalacion_version0_zpsubmjtrul.png[/IMG] "Instalación versión v0.11.6.")


![Instalación versión v41.6.1]([IMG]http://i345.photobucket.com/albums/p391/maribhez/instalacionVersion4_zps4lzfdd5m.png[/IMG] "Instalación versión v41.6.1.")