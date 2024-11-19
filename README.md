# ConversorDeMonedas
Conversor de Monedas en Java
Descripción
Este es un Conversor de Monedas desarrollado en Java que permite convertir entre varias monedas utilizando tasas de cambio obtenidas a través de una API. El programa proporciona una interfaz de consola para interactuar con el usuario, mostrando un menú con opciones para realizar las conversiones de monedas.

El objetivo principal de este proyecto es permitir a los usuarios convertir entre diversas monedas, incluyendo Dólar (USD), Peso Mexicano (MXN), Real Brasileño (BRL) y Peso Colombiano (COP), entre otras.

Tecnologías
Java: El proyecto está desarrollado en Java, utilizando la versión 11 en adelante.
API de tasas de cambio: El proyecto se integra con una API externa para obtener las tasas de cambio actualizadas.
Gson: Utilizado para analizar las respuestas en formato JSON de la API.
HttpClient y HttpRequest: Herramientas de Java para realizar solicitudes HTTP y manejar las respuestas.
Requisitos
Antes de ejecutar el proyecto, asegúrate de tener instalados los siguientes programas:

Java JDK 11 o superior: Asegúrate de tener configurada la variable de entorno JAVA_HOME y que el comando java esté disponible en tu terminal.

Descargar Java JDK: Oracle JDK
Biblioteca Gson: Puedes incluir la biblioteca Gson en tu proyecto agregando el archivo JAR correspondiente o configurando un archivo pom.xml si usas Maven.

Dependencia para Maven:

<dependency>
    <groupId>com.google.code.gson</groupId>
    <artifactId>gson</artifactId>
    <version>2.10.1</version>
</dependency>
Postman: Para probar las respuestas de la API y verificar su funcionamiento antes de la integración.

Instalación
Clonar el repositorio:

En tu terminal, usa el siguiente comando para clonar el repositorio:

git clone https://github.com/tu-usuario/conversor-de-monedas-java.git
Importar el proyecto:

Si estás usando un IDE como IntelliJ IDEA o Eclipse, importa el proyecto para empezar a trabajar en él.

Configurar las dependencias:

Si usas Maven, agrega la dependencia de Gson en tu archivo pom.xml. Si usas otro sistema de dependencias, descarga e importa el archivo JAR de Gson.

Uso
Ejecutar el programa:

En la terminal, navega a la carpeta del proyecto y ejecuta el siguiente comando:

java ConversorMonedas
Interacción con el programa:

Al ejecutar el programa, verás un menú con las siguientes opciones:


***************************************************************************
Sea bienvenido/a al Conversor de Monedas
1) Dólar => Peso Mexicano
2) Peso Mexicano => Dólar
3) Dólar => Real Brasileño
4) Real Brasileño => Dólar
5) Dólar => Peso Colombiano
6) Peso Colombiano => Dólar
7) Salir
***************************************************************************
Elija una opción válida:
Luego, ingresa la opción que desees y la cantidad que quieres convertir. El programa realizará la conversión y mostrará el resultado.

Salir del programa:

Si eliges la opción 7, el programa terminará y te dará un mensaje de despedida.

Ejemplo de Ejecución

***************************************************************************
Sea bienvenido/a al Conversor de Monedas
1) Dólar => Peso Mexicano
2) Peso Mexicano => Dólar
3) Dólar => Real Brasileño
4) Real Brasileño => Dólar
5) Dólar => Peso Colombiano
6) Peso Colombiano => Dólar
7) Salir
***************************************************************************
Elija una opción válida: 1
Ingrese la cantidad a convertir: 100
100.00 USD equivalen a 2050.00 MXN
Fases del Proyecto
Este proyecto se ha desarrollado en varias fases:

Fase 1: Configuración del entorno de desarrollo en Java.
Fase 2: Uso de la clase HttpClient para realizar solicitudes a la API.
Fase 3: Configuración de solicitudes con HttpRequest.
Fase 4: Manejo de respuestas con la interfaz HttpResponse.
Fase 5: Análisis de la respuesta JSON con la biblioteca Gson.
Fase 6: Implementación de la lógica de conversión.
Fase 7: Interacción con el usuario y pruebas.
Contribuciones
Si deseas contribuir al proyecto, por favor sigue estos pasos:

Haz un fork del repositorio.
Crea una nueva rama para tu característica (git checkout -b feature/nueva-caracteristica).
Realiza tus cambios y haz commit de ellos (git commit -am 'Añadir nueva característica').
Empuja tus cambios a tu fork (git push origin feature/nueva-caracteristica).
Crea un pull request con una descripción de los cambios.
