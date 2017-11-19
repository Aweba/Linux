# Prueba de entrada : Comandos
## Crear en la carpeta /tmp el archivo mi.prueba
```[Aweba@localhost ~]$ cd /tmp/```    
```[Aweba@localhost ~]$ touch mi.prueba```    
## Tipear en el archivo PeruRumboGSoC2020
```[Aweba@localhost ~]$ vi mi.prueba  
* Ahora en vi vamos a escribir *
ESC + i  
PeruRumboGSoC2020  
*Copiaremos 30 veces lo mismo*
ESC yy 30p  
*Buscamos y reemplazamos*  
ESC :%S/PeruRumboGSoC2020/PeruRumboGSoC2018/g  
*Guardamos los cambios*  
ESC :wq!  
##Mostraremos de la linea 15 a la 25  
```[Aweba@localhost ~]$ head -25 mi.prueba | tail -11```  
## Mostraremos los archivos que han sido modificados hace 7 dias y pesan 300 MB
```[Aweba@localhost ~]$ find -mtime -7 -size -300M```  

