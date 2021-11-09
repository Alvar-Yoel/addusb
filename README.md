# addusb
Este script diseñado en *bash*, sirve para guardar de una forma facil y sencilla un *dispositivo* en nuestra maquina linux, y que este sea detectado **automaticamente** al conectarlo de nuevo o al **apagar** y **reiniciar** la maquina

## Despliegue 🔧
Lo primero que tendremos que hacer es **clonar el repositorio** a nuestra maquina

```bash 
linux@home/linux/:~$ git clone https://github.com/Alvar-Yoel/addusb
```

Cuando lo tengamos clonado **entraremos** en el repositorio ya clonado previamente

```bash
linux@home/linux/:~$ cd addusb
```

Ahora dentro de la carpeta le daremos permisos de **ejecucion** al script

```bash 
linux@home/linux/addusb:~$ chmod +x addusb.sh
```

## Uso🛠️
Cuando le hayamos dado permisos de **ejecucion** lo *ejecutaremos*

```bash 
linux@home/linux/addusb:~$ ./addusb.sh
```

Ahora podremos elegir si queremos guardar una **Impresora🖨️** o una **Camara📷**
```bash
Que quiere guardar una Impresora o una Camara
1) Impresora
2) Camara
3) Salir
#?
``` 

### Impresora🖨️
Podremos elegir lo que queremos por numeros por ejemplo si queremos guardar una impresora lo que tendremos que hacer es presionar el **1** y darle a **Enter**
```bash
Que quiere guardar una Impresora o una Camara
1) Impresora
2) Camara
3) Salir
#? 1
```
***-Dato:*** El script no funciona si escribimos ~~Impresora~~ o ~~Camara~~ nos saldra **Error**

Ahora podremos elegir si queremos elegir el modo Automatico o Manual
``` 
Por favor, seleccione un modo Automatico, Manual o Salir [1/2/3]
1) Automatico
2) Manual
3) Salir
#?
```

### Automatico
***-Dato:*** El modo _Automatico_ solo funciona si el dispositivo tiene **Idserial** o **IdProduct** si no lo tendra que hacer _Manual_ para que detecte en que **puerto** este conectado y solo podra conectarlo a ese puerto (En el modo _Automatico_ da igual en que puerto este conectado)

Si elegimos el modo automatico tendremos que seleccionar la opcion **1**
``` 
Por favor, seleccione un modo Automatico, Manual o Salir [1/2/3]
1) Automatico
2) Manual
3) Salir
#? 1
```

Ahora en la siguiente nos pedira tener **desconectado** el dispositivo, cuando lo tengamos, presionaremos **1**
```
Por favor, desconecte el dispositivo a indentificar [1/2]
1) Siguiente
2) Salir
#? 1
```

Ahora tendremos que **conectar** el dispositivo por que lo que va a realizar es una _comprobacion de los dispositivos conectados anteriormente_ y el que acabamos de _conectar_
```
Por favor, conecte el dispositivo a indentificar [1/2]
1) Siguiente
2) Salir
#? 1
```

Ahora hara una serie de _comprobaciones_ y apuntara el dispositivo a _guardar_ y nos dara la opcion de ponerle **nombre** el cual le voy a poner **Impresora1** 
```
Introduce el nombre del dispositivo: Impresora1
```

### Manual
Si elegimos el modo _Manual_ tendremos que seleccionar la opcion **2**
``` 
Por favor, seleccione un modo Automatico, Manual o Salir [1/2/3]
1) Automatico
2) Manual
3) Salir
#? 2
```

## Autores ✒️
- Alvar Yoel Ordoñez Gamez
