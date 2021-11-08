# addusb
Este script diseñado en *bash*, sirve para guardar de una forma facil y sencilla un *dispositivo* en nuestra maquina linux, y que este sea detectado **automaticamente** al conectarlo de nuevo o al **apagar** y **reiniciar** la maquina

## Despliegue 📦
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
Cuando le hayamos dado permisos de ejecucion lo *ejecutaremos*

```bash 
linux@home/linux/addusb:~$ ./addusb.sh
```

Ahora podremos elegir si queremos guardar una *impresora* o una *camara*
```bash
Que quiere guardar una Impresora o una Camara
1) Impresora
2) Camara
3) Salir
#?
``` 

Podremos elegir lo que queremos por numeros por ejemplo si queremos guardar una impresora lo que tendremos que hacer es presionar el 1 y darle a Enter
```bash
Que quiere guardar una Impresora o una Camara
1) Impresora
2) Camara
3) Salir
#?1
```
***Dato:*** El script no funciona si escribimos ~~Impresora~~ o ~~Camara~~ nos saldra **Error**

Ahora podremos elegir si queremos elegir el modo Automatico o Manual
``` 
Por favor, seleccione un modo Automatico, Manual o Salir [1/2/3]
1) Automatico
2) Manual
3) Salir
#?
```

### Automatico
Si elegimos el modo automatico tendremos que 

### Manual
## Autores ✒️
- Alvar Yoel Ordoñez Gamez
