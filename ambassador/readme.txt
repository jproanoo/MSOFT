Esto ejecutará dos contenedores: uno para el servicio Python y 
otro para el Ambassador (NGINX). El Ambassador actuará como intermediario, 
redirigiendo las solicitudes recibidas en el puerto 80 a la aplicación de 
servicio que se ejecuta en el puerto 5000.

Puedes acceder al servicio a través del puerto 80, ya que el Ambassador 
escucha en ese puerto y redirige las solicitudes al servicio Flask.