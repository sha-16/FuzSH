# FuzSH
Este es un fuzzer que me he creado en Bash; es medianamente rápido y preciso... Les invito a probarlo!

## Requerimientos
Tener instalada la utilidad ```curl```.
```bash 
$ sudo apt install curl -y
```

## Instalación y uso 
```bash
$ git clone https://github.com/sha-16/fuzsh.git
$ cd fuzsh/
$ chmod +x fuzsh
$ ./fuzsh 
```

**Nota:** si deseas ejecutar el script sin indicar su ruta absoluta, deberás añadirlo a 
cualquiera de las rutas del path en tu sistema. Estas las puedes ver ejecutando la 
siguiente sentencia, para ver la variable de entorno ```$PATH```: ```$ echo $PATH```.
