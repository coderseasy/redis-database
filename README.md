# redis-database
### para la instalacion de redis descargar el archivo Redis-x64-3.0.504.zip que se encuentra en este repositorio

instalar redis video de referencia
[video de instalacion](https://www.youtube.com/watch?v=lwcikOT97lc&list=PLCTD_CpMeEKRjdM94onQPs3qTISaPkmxa&index=2)
# para utilizar en php es nesesario la instalacion
## descargar el archivo php_redis-5.3.5-7.4-ts-vc15-x64.rar que se encuentra en este repositorio
#### una ves descargado el archivo se procede a copiar los archivos  php_redis.dll  y php_redis.pdb a donde se encuentra los archivos de configuracion de php, en el caso de que estes trabajando con xampp este es el directorio C:\xampp\php\ext y pegar los dos archivos.
#### luego entrar al archivo php.ini si es el caso de xampp se encuentra en C:\xampp\php y agregar
#### extension=php_redis.dll
## revisar la guia [guia para agregar redis a php](https://ourcodeworld.co/articulos/leer/1502/como-instalar-y-usar-la-extension-redis-en-xampp-localmente-en-windows-10)

#### guia alternativa [guia alternativa instalacion de redis extension en php](https://programmerclick.com/article/4153123382/)

# instalacion de paquetes en laravel mediante predis
## `composer require predis/predis`
# configurar en el archivo .env
### PREDIS_CLIENT=predis
