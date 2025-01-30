# Methax 1 - PROCESO OBSOLETO
Método de modificación de consola 3Ds


Methax es un proceso de modificación de la consola 3Ds que mezcla parte del proceso Pichaxx [https://gist.github.com/zoogie/931c87ca8cae98c28e931182af26f89b] que logra realizar la instalación del Boot9 mediante SafeB9SInstaller [https://github.com/d0k3/SafeB9SInstaller/releases/tag/v0.0.7].

- En primer lugar, necesitaremos:

3ds/2ds de modelo Old o New y en región U/E/J.
Descargar el juego Pokemon Picross desde la eshop (para consolas de residencia en LATAM deberán cambiar su residencia a EEUU).
Apuntar nuestro código de amigo.

- En segundo lugar, acudiremos a:

https://discord.gg/8Fv8GDg para sacar el archivo .sed. Se obtiene añadiendo el código de amigo y los dígitos de carpeta correspondiente al juego Pokemon Picross (están en el interior de la carpeta Nintendo 3ds)
https://www.librescene.com/hack-3ds para sacar el archivo .sav (se obtiene añadiendo el .sed anterior). Este .sav debemos meter en la siguiente ruta: sdmc:/Nintendo 3DS/long hex number/another long hex number/title/00040000/0017c100/data/ y remplazar el ya existente.

- En tercer lugar, introduciremos los archivos hack paso 1 (se encuentra luma 10.2.1 y godmode9 1.9.2) en la raíz de la sd: https://mega.nz/file/a3wghThS#FpU0kXyT9S_hb0k0XFZacuG2pHCkrxJGDlTs7Is0Bns

- En cuarto lugar, acudiremos a la consola y abriremos el juego de Pokemon Picross. En esta ocasión se flasheará y saldrá el SafeB9SInstaller. A continuación, ejecutaremos la combinación de botones que nos indique. Al finalizar se acabará de instalar el Boot9 de 2017.
Acto seguido, saldrá el menú de Luma (de no ser así, con la consola apagada, lo abriremos con Select+Power) y marcaremos la opción: Mostrar NAND o texto personalizado en Conf. Pulsaremos Star para que inicie nuestra consola ya modificada.


- En quinto lugar, ingresaremos al godmode9. 

1. Le daremos a la [B] para no generar una fecha ni una hora determinadas.

2. Pulsaremos el botón [HOME] para desplegar un panel de opciones.

3. Acudiremos a la opción Scripts... 

4. Ejecutaremos el scripts Yakarear_3DS_2020. Tendremos que darle permisos. 

Acto seguido, saldrá el menú de Luma (de no ser así, con la consola apagada, lo abriremos con select+power) y marcaremos la opción: Mostrar NAND o texto personalizado en Conf. Pulsaremos Star para que inicie nuestra consola ya modificada y actualizada con el Boot9 de 2020. con este script, además, podremos encender nuestra consola sin la SD, priviene los arranques rotos [los llamados BB] y es más rápido y estable que el de 2017. 

- En sexto lugar, formatearemos la Sd y meteremos los Archivos Hack Paso 2: https://mega.nz/file/T3pAhbqb#lIthoGWLKypTi6RRgJaHxGQPd_omnOGT0bVEknRtOlA

Verificaremos nuevamente que Luma [Select+Power] tiene activa las opciones de Mostrar NAND o texto personalizado en Conf. y la opción del Splash en [Antes] (es opcional pero muy recomendable para idenficiar errores de arranque). Pulsaremos Star para que inicie nuestra consola ya modificada.

Por últimos, nos quedará:
- Instalar el FBI desde el Godmode9 o mediante Rosalina.
- Inyectar el Splash de seguridad (es opcional pero muy recomendable para idenficiar errores de arranque).
- Crear respaldo NAND.

AGRADECIMIENTOS:

- Zoogie por descubir la vulnerabilidad en el juego Pichaxx.
- d0k3 por el soporte de SafeB9SInstaller.
- Yakara por su script de mejora del boot9.
- López Tutoriales por las traduciones de Luma.  
- Team Preshax por brindar el soporte del minado en Discord La Presa.
