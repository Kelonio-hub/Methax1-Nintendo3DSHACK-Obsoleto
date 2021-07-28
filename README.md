# Methax-3
Método de modificación de consola 3Ds


Methax es un proceso de modificación de la consola 3Ds que mezcla parte del proceso Pichaxx [https://gist.github.com/zoogie/931c87ca8cae98c28e931182af26f89b] que logra realizar la instalación del Boot9 mediante SafeB9SInstaller [https://github.com/d0k3/SafeB9SInstaller/releases/tag/v0.0.7].

En primer lugar, necesitaremos:

3ds/2ds de modelo Old o New y en región U/E/J.
Descargar el juego Pokemon Picross desde la eshop (para consolas de residencia en LATAM deberán cambiar su residencia a EEUU).
Apuntar nuestro código de amigo.
En segundo lugar, acudiremos a:

https://discord.gg/8Fv8GDg para sacar el archivo .sed. Se obtiene añadiendo el código de amigo y los dígitos de carpeta correspondiente al juego Pokemon Picross (están en el interior de la carpeta Nintendo 3ds)
https://www.librescene.com/hack-3ds para sacar el archivo .sav (se obtiene añadiendo el .sed anterior). Este .sav debemos meter en la siguiente ruta: sdmc:/Nintendo 3DS/long hex number/another long hex number/title/00040000/0017c100/data/ y remplazar el ya existente.
En tercer lugar, introduciremos los archivos hack (se encuentra luma 10.2.1 y godmode9 1.9.2) en la raíz de la sd: 

En cuarto lugar, acudiremos a la consola y abriremos el juego de Pokemon Picross. En esta ocasión se flasheará y saldrá el SafeB9SInstaller. A continuación, ejecutaremos la combinación de botones que nos indique. Al finalizar se acabará de instalar el Boot9.

Acto seguido, saldrá el menú de Luma (de no ser así, con la consola apagada, lo abriremos con select+power) y marcaremos la opción: Show current NAND in System Settings. Pulsaremos star para que inicie nuestra consola ya modificada.

A continuación entraremos al godmode9 [star+power] le daremos al botón Home y acudiremos a la opción Scripts...
Ejecutaremos el scripts Yakarear_3ds_2020. Con ello actualizaremos el boot9 mediante el fork de Yakara, teniendo mayor estabilidad frente al boot9 de 2017. 
Además, podremos encender la consola sin la tarjeta Sd y, sobre todo, lograremos evitar Arranques Rotos (los llamados BB).

Por íultimos, nos quedará:
Instalar el FBI desde el Godmode9 o mediante Rosalina.
Inyectar el Splash de seguridad (es opcional pero muy recomendable para idenficiar errores de arranque).
Crear respaldo NAND.
AGRADECIMIENTOS:

Zoogie por descubir la vulnerabilidad en el juego Pichaxx.
d0k3 por el soporte de SafeB9SInstaller.
Yakara por su script de mejora del boot9. 
Team Preshax por brindar el soporte del minado en Discord La Presa.
