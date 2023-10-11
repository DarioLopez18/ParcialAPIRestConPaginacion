# EntregaTpAPIRestConPaginacion

 <p align="center">
     <img
         src="https://media.giphy.com/media/2IudUHdI075HL02Pkk/giphy.gif"
         alt="fullstackdeveloper"
         width="360px"
         height="190px"
        align="center"
    />
 </p>

# Datos del alumno👨‍🎓:

* Nombre: Lopez, Dario Angel Jose
* Legajo: 47822

# Datos institucionales📚:

* Universidad Tecnológica Nacional - Facultad Regional Mendoza
* Cátedra: Desarrollo de Software
* Comisión: 3K09
* Turno: tarde
* Año: 2023

# Acerca de la entrega💾:

* Se entrega un modelod de persistencia de un diagrama de clases dado por la cátedra.
* Existen las entidades, los repositorios de las mismas y una serie de enumeraciones para facilitar el trabajo
* Descargar el archivo zip, desempaquetarlo, esperar a que se instalen las dependencias y ejecutar el codigo en el ide.
* Realizar las siguientes actividades correspondientes al estudio del modelo de Biblioteca expresado en los videos de Colmena Tec
* 1-Crear el Modelo de Diagrama de Clase que se muestra en el video:
* Capturar la pantalla del diagrama y pegarla en un documento word. El nombre del archivo será apellidoLegajoDia.doc
* 2- Estudiar la siguiente Playlist:
* https://www.youtube.com/watch?v=rmCvCOBAqEA&list=PLRFOqDrY-6nueU8NwtjRIcX5-nsD6jkru&ab_channel=ColmenaTEC
* Desde el video :
* API REST con Spring Boot 1 Introducción HASTA el video  API REST con Spring Boot 12 Probando la API con Postman
* a-  No considerar la sección de auditoría de Enver.
* b- Refactorice el código  de los videos para utilizar una base de datos H2.
* c- Coloque las dependencias correspondientes de Swagger como dependencia en el buil.gradle:
* // https://mvnrepository.com/artifact/org.springdoc/springdoc-openapi-starter-webmvc-ui
* implementation group: 'org.springdoc', name: 'springdoc-openapi-starter-webmvc-ui', version:'2.1.0'
* d- Crearse una cuenta en Render
* f- Incorporar en el archivo de build.gradle:
* jar {
*    manifest {
*      attributes 'RestfakeApplication': 'com.facu.restfake.RestfakeApplication' // Reemplaza 'tu.paquete.MainClass' con la clase principal de tu aplicación
*   }
*}
* - Ejecute el comando gradle build  desde la terminal para crear el jar correspondiente.
* Se creará en el proyecto una carpeta:
* build/libs/restfake-0.0.1-SNAPSHOT.jar
* e-  Utilizar el Archivo Dockerfile que se propone en el github y actualizar el nombre de tu jar:
* FROM openjdk:17-alpine
* EXPOSE 9000
* COPY --from=build ./build/libs/elnombredetujar-0.0.1-SNAPSHOT.jar ./app.jar
* f - Descargar el proyecto MODELO AUXILIAR  a analizar desde el Link de Github:
* https://github.com/cortezalberto/claseFakeGenerico
* - Estudiar las entidadesProducto y Rating correspondientes y realizar la interpretación de las mismas.
* Las capas de la aplicación, los controladores genéricos, Servicios y repositorios.
* Rúbrica de evaluación del Tp:
*  Todas las clases
*  Todas las enumeraciones
*  Propiedades y métodos en las clases
*  Todas las relaciones 
* Todas las cardinalidades
* Todos los controladores - Todos los repositorios - Todos los Servicios
* El jar creado 
* El archivo del diagrama de clases creado
* Un archivo generado con postman para probar TU API - Una colleción
* El trabajo se entrega en un Repo en la nube, con todo lo solicitado

# Deploy

https://apirestconpaginacion-9kly.onrender.com

# Tecnologías utilizadas💻:

* ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
* ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
* ![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
* ![JAVA](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

# Contacto☎️:

* Email📩: darioangellopez38@gmail.com
* Celular📲: 2616150281
* Linkedin📫: https://www.linkedin.com/in/dario-angel-jose-lopez-2a3202234/
