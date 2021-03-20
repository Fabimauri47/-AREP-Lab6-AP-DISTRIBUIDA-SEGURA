# -AREP-Lab6-AP-DISTRIBUIDA-SEGURA


## Introducción Del Proyecto

En este laboratorio 5 aprendimos a crear una pequeña aplicación web, usando un micro-framework de Spark Java, el cual se encargará de crear aplicaciones pequeñas sin mayor esfuerzo. En donde una vez se tenga una aplicación se procederá a construir un contenedor, para hacer uso de Docker, en la aplicación. Lo cual nos permitirá desplegarlo y configurarlo desde nuestra maquina local.


### Pre-Requisitos

- Para la realización de este laboratorio es necesario el uso de los aplicativos mencionados abajo de la descripción, en donde si no cuenta con alguno de estos,
       solo es necesario darle clic al que necesite y lo dirigirá a la página de instalación:


    * [Java 11](https://www.java.com/es/) - Codificación
    * [Maven](https://maven.apache.org/) - Manejo de Dependencias
    * [Git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git) - Control de Sistemas de veriones.
    * [AWS](https://aws.amazon.com/es/education/awseducate/) - Despligue de Ambiente Web
    * [CircleCI](https://circleci.com/) - Calidad y ejecución del codigo


### AWS Virtual Machine

>[![AWS Virtual Machine]()


### Integracion Continua con Circle CI
>[![CircleCI](https://circleci.com/gh/The-Developers-Eci/2020-2-PROYCVDS-THE_DEVELOPERS_ECI.svg?style=svg)](https://app.circleci.com/pipelines/github/Fabimauri47/-AREP-Lab3-CLIENTES-Y-SERVICIOS)
>

### Guia de Instalación

1. Primero se debe clonar el repositorio, con el siguiente comando descrito:

       git clone https://github.com/Fabimauri47/-AREP-Lab5-MODULARIZACI-N-CON-VIRTUALIZACI--E-INTRODUCCI-N-A-DOCKER-Y-AWS
    

2. Luego proceda abrir el cmd (Ventana de comandos) en donde tiene el repositorio alojado y ejecute el siguiente comando:

       mvn package
    

3. Ejecutamos el programa con el siguiente comando:

       mvn exec:java -D "exec.mainClass"="edu.escuelaing.demo.NanoSparkWebDemo"
   

4. Gereramos la documentación con el siguiente comando ejecutandolo desde consola:

       mvn javadoc:javadoc
   
 5. Si desea ejecutar el programa de forma local, procedemos a ejecutar el siguiente comando:

        java -cp target/classes edu.escuelaing.arep.RoundRobin.SparkWebServer

## Corriendo Pruebas

Para correr las pruebas, usamos el siguiente comando en una terminal CMD o en una terminal GIT:

         mvn test

 
## Desarrollo e Informe

- Para conocer más sobre el desarrollo del proyecto, descargue el proyecto como se explica arriba o revise el informe:

    -[Presione Aqui para revisar documento](https://github.com/Fabimauri47/-AREP-Lab5-MODULARIZACI-N-CON-VIRTUALIZACI--E-INTRODUCCI-N-A-DOCKER-Y-AWS/blob/main/Lab_5_Taller_de_modularizaci_n_con_virtualizaci_n__Docker_y_AWS.pdf)

## Construido con

* [Java 11.0](https://www.java.com/es/) - Codificación y Lenguaje de Programacíon.
* [Maven](https://maven.apache.org/) - Manejo de Dependencias.
* [IntelliJ IDEA](https://www.jetbrains.com/es-es/idea/) - Programa usado para la Codificacíon.
* [AWS](https://aws.amazon.com/es/education/awseducate/) - Despligue de Ambiente Web
* [Docker](https://www.docker.com/) - Control y despliegue del proyecto


## Autor

* **Fabián Mauricio Ramirez Pinto** [Fabimauri47](https://github.com/Fabimauri47)


## Licencia

Este proyecto cuenta con la licencia GNU: General Public License - see the [LICENSE.md](https://github.com/Fabimauri47/AREP-Lab1-Calculadora/blob/main/LICENSE.txt) 
