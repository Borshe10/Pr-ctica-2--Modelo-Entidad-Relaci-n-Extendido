A continuacion se redactan los pasos que se siguieron a cabo para poder llevar a cabo el levantamiento en una computadora.

1. Se accedio al repositorio de github del proyecto de sismos, en donde se llevaron a cabo las instrucciones del archivo README
2. Uno de los requisitos fue tener instalado git para la clonación del proyecto.
3. Se vio un video de youtube sobre la instalacion de Git y se siguieron los pasos para obtenerlo
4. Una vez teniendo instalado Git, se creo una carpeta dentro del equipo en donde se llevo a cabo la clonacion del repositorio
5. Con git bash, una vez estando en la terminal de la carpeta, se llevo a cabo el siguiente comando "git clone https://github.com/gabrielhuav/DWSismos.git" seguido de "cd DWSismos"
6. Con el repositorio una vez ya clonado, se llevo a cabo el levantamiento del contenedor de docker con el siguiente comando "docker-compose up -d"
7. Despues que el se creo la base de datos correspondiente, se siguió las instrucciones sobre su uso, acceder al localhost con el puerto asignado en el archivo docker-compose, en este caso el 80, sin embargo,
   al acceder, la pagina decia que no tenia los permisos para acceder, por lo que investigando, se accedio al localhost mediante el archivo html dentro de la carpeta src
