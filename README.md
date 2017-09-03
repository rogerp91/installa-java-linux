
# Install Java

```command
sudo add-apt-repository ppa:webupd8team/java
sudo apt-get update
sudo apt-get install oracle-java8-installer
```

Oracle:

```bash
Instalar
Las instrucciones que figuran a continuación son para la instalación de la versión Java 8 Update 73 (8u73). Si va a instalar una versión distinta, cambie el número de la versión según corresponda cuando escriba los comandos en el terminal. Ejemplo: para Java 8u79, sustituya 8u73 por 8u79. Tenga en cuenta que, como en el ejemplo anterior, el número de versión va a veces precedido por la letra u, y otras veces por un guion bajo, por ejemplo, jre1.8.0_73.

Nota para el acceso raíz: Para instalar Java en una ubicación que afecte a todo el sistema, como /usr/local, debe conectarse como el usuario raíz para contar con todos los permisos necesarios. Si no tiene acceso de usuario root, instale Java en su directorio de inicio o en un subdirectorio para el que disponga de permiso de escritura.

    Cambie al directorio en el que desee efectuar la instalación. Escriba:
    cd nombre_ruta_acceso_directorio
    Por ejemplo, para instalar el software en el directorio /usr/java, escriba:
    cd /usr/java/

    Mueva el archivo binario de almacenamiento .tar.gz al directorio actual.
    Desempaquete el tarball e instale Java
    tar zxvf jre-8u73-linux-x64.tar.gz

    Los archivos de Java se instalan en un directorio denominado jre1.8.0_73 en el directorio actual. En este ejemplo, se ha instalado en el directorio /usr/java/jre1.8.0_73. Una vez finalizada la instalación se mostrará la palabra Terminado.
    Suprima el archivo .tar.gz si desea ahorrar espacio en el disco.
```
