# CREACIÓN DE ENTORNO SEGURO 
---
 Empezamos descargando el paquete de `firetools`si no lo tenemos isntalado ya en kali.

``` bash 
    sudo apt update && sudo apt install firetools
```
Luego continuamos abriendo **firejail** y dentro de el podemos observar que se puede añadir una aplicación, sabiendo esto podemos abrir desde el menú una terminal de administrador, hacer click derecho encima y darle a *"editar"* entonces ahí podremos ver la orden de ejecución. 

![paso1](https://raw.githubusercontent.com/vjp-hectorBG/PPSUnidad1-ActividadSandboxingHectorBlazquezGomez/refs/heads/main/paso1.png)

Una vez copiado y pegado en la barra inferior podemos guardar la configuración y cuando queramos abrir la terminal como root se nos abrirá el entorno seguro (Se puede verificar porque al ejecutar el comando `mount`vemos que hay archivos temporales).

![paso2](https://raw.githubusercontent.com/vjp-hectorBG/PPSUnidad1-ActividadSandboxingHectorBlazquezGomez/refs/heads/main/paso2.png)

![paso3](https://raw.githubusercontent.com/vjp-hectorBG/PPSUnidad1-ActividadSandboxingHectorBlazquezGomez/refs/heads/main/paso3.png)

Y ahora solo nos hace falta comprobar si tenemos instalado python , meternos en la carpeta del proyecto y ejecutar el entorno virtual de python para tenerlo todo listo.

![paso4](https://raw.githubusercontent.com/vjp-hectorBG/PPSUnidad1-ActividadSandboxingHectorBlazquezGomez/refs/heads/main/paso4.png)

![paso5](https://raw.githubusercontent.com/vjp-hectorBG/PPSUnidad1-ActividadSandboxingHectorBlazquezGomez/refs/heads/main/paso5.png)

Para acabar ejecutamos nuestra aplicación en el entorno seguro que acabamos de crear.

![paso6](https://raw.githubusercontent.com/vjp-hectorBG/PPSUnidad1-ActividadSandboxingHectorBlazquezGomez/refs/heads/main/paso6.png)
