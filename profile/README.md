# Configuración del Entorno de Desarrollo de Java para Spring Framework 6 y Spring Boot 3

## Prerrequisitos

Antes de comenzar, asegúrate de tener lo siguiente instalado en tu máquina:

- [Java Development Kit (JDK) 17](https://www.oracle.com/java/technologies/javase-jdk17-downloads.html)
- [Maven](https://maven.apache.org/download.cgi)
- [IntelliJ IDEA](https://www.jetbrains.com/idea/download/) o tu IDE preferido
- [Git](https://git-scm.com/downloads)

## Paso 1: Instalar JDK 17

1. Descarga el JDK 17 desde la [página de descargas de Oracle JDK](https://www.oracle.com/java/technologies/javase-jdk17-downloads.html).
2. Sigue las instrucciones de instalación para tu sistema operativo.

### Verificar la Instalación del JDK

Después de instalarlo, verifica la instalación ejecutando el siguiente comando en tu terminal o símbolo del sistema:

```sh
java -version
```

Deberías ver una salida similar a:

```sh
java version "17.0.1" 2021-10-19 LTS
Java(TM) SE Runtime Environment (build 17.0.1+12-LTS-39)
Java HotSpot(TM) 64-Bit Server VM (build 17.0.1+12-LTS-39, mixed mode, sharing)
```

## Paso 2: Instalar Maven

1. Descarga Maven desde la [página de descargas de Maven](https://maven.apache.org/download.cgi).
2. Sigue las instrucciones de instalación para tu sistema operativo.

### Verificar la Instalación de Maven

Después de instalarlo, verifica la instalación ejecutando el siguiente comando en tu terminal o símbolo del sistema:

```sh
mvn -version
```

Deberías ver una salida similar a:

```sh
Apache Maven 3.8.1 (NON-CANONICAL_2021-05-20T23:00:13Z_root)
Maven home: /usr/local/apache-maven/apache-maven-3.8.1
Java version: 17.0.1, vendor: Oracle Corporation, runtime: /usr/local/java/jdk-17
Default locale: en_US, platform encoding: UTF-8
OS name: "linux", version: "5.10.16.3-microsoft-standard-wsl2", arch: "amd64", family: "unix"
```

## Paso 3: Configurar el IDE

1. Descarga e instala [IntelliJ IDEA](https://www.jetbrains.com/idea/download/) o tu IDE preferido.
2. Abre IntelliJ IDEA y configura el JDK 17 y Maven en las preferencias del IDE.

## Paso 4: Crear un Proyecto con Spring Boot

1. Abre IntelliJ IDEA y selecciona **New Project**.
2. Elige **Spring Initializr** y configura el proyecto:
   - Selecciona la versión de Java 17.
   - Agrega las dependencias necesarias como Spring Web, Spring Data JPA, y H2 Database.
3. Haz clic en **Next** y luego en **Finish** para crear el proyecto.

## Paso 5: Ejecutar la Aplicación

1. Navega al directorio del proyecto en tu terminal.
2. Ejecuta el siguiente comando para compilar y ejecutar la aplicación:

```sh
mvn spring-boot:run
```

Deberías ver que la aplicación se inicia correctamente y está lista para ser utilizada.

¡Listo! Ahora tienes tu entorno de desarrollo configurado para trabajar con Spring Framework 6 y Spring Boot 3.
