
# Proyecto: Creación de Base de Datos para Netflix
### Esta base de datos se crea con el objetivo de gestionar eficientemente la información relevante de la plataforma de streaming Netflix, con estos indicadores específicos: 

 ➡ Almacenamiento Eficiente: Organizar y almacenar datos sobre series, contenido, actores y actuaciones de manera estructurada y fácilmente accesible.

 ➡ Relaciones Claras: Establecer relaciones claras entre diferentes entidades (series, contenido, actores, actuaciones) para facilitar consultas complejas y análisis de datos.

 ➡ Consulta y Recuperación Rápida: Permitir la recuperación rápida y eficiente de información relevante, como los detalles de una serie, el elenco de actores en una película, o las actuaciones de un actor específico.

 ➡ Mantenimiento y Actualización: Facilitar el mantenimiento y la actualización de la base de datos con nuevas series, películas, actores y actuaciones conforme se agregan o modifican.

 ➡ Soporte para Análisis de Datos: Proveer una base sólida para realizar análisis de datos, como estadísticas de visualización, popularidad de contenido, y tendencias de género y clasificación.

 ➡ Interoperabilidad: Integrarse con otras aplicaciones y servicios, permitiendo la exportación e importación de datos, así como la interoperabilidad con sistemas externos.

 ➡ Seguridad y Privacidad: Asegurar que los datos se almacenen y gestionen de manera segura, protegiendo la privacidad de la información sensible de los usuarios y del contenido.
## Requerimientos

➡ MySQL: Instalación del servidor de bases de datos MySQL.

➡ Herramienta de Gestión: MySQL Workbench u otra herramienta para la administración de bases de datos.

➡ Conocimiento Básico: Familiaridad con SQL y diseño de bases de datos relacionales.

## Descripción del Proyecto
➡ Diseño: Primero, diseñarás el esquema de la base de datos en MySQL Workbench, definiendo las tablas y sus relaciones.

➡ Implementación: Crearás las tablas y las insertarás con datos de muestra para pruebas.

➡ Consultas: Desarrollarás diversas consultas SQL para interactuar con los datos de la base de datos.

➡ Pruebas: Realizarás pruebas para asegurarte de que las consultas y las estructuras de datos funcionen correctamente.

➡ Optimización: Optimizarás la base de datos para mejorar el rendimiento en consultas complejas.

## Estructura de la Base de Datos:
### Paso 1: Crear la base de datos " NetflixDB "
Primero, debes crear la base de datos en MySQL. Aquí te dejo el comando SQL para hacerlo:
![image](https://github.com/user-attachments/assets/8c38cb94-25e5-4071-9e8f-d23c189666cc)

### Paso 2: Crear la tabla Series
A continuación, crearemos la tabla para almacenar información sobre contenido disponible en la plataforma.

![image](https://github.com/user-attachments/assets/f0629a56-27e7-4fe3-ac7d-9c31ff620c39)


### Paso 3: Crear la tabla Contenido
Luego, creamos la tabla que almacenará la información de episodios

![image](https://github.com/user-attachments/assets/5c2fbeed-333f-4872-b0ba-01949efe31fe)


### Paso 4: Crear la tabla Actores

![image](https://github.com/user-attachments/assets/29187e3a-05d2-42fb-9666-6a238073bbb2)

### Paso 5: Crear  la tabla Actuaciones (relación muchos a muchos entre Actores y Series)

![image](https://github.com/user-attachments/assets/4031507f-3229-450e-8452-879d670a032a)


### Paso 6: Insertar datos de prueba
Puedes insertar algunos datos de prueba en las tablas para asegurarte de que todo funciona correctamente.

![image](https://github.com/user-attachments/assets/5b8d4079-228d-4430-81a9-53bc88669e28)

![image](https://github.com/user-attachments/assets/38342e9e-0905-4f2d-b18c-3344d0c048df)

![image](https://github.com/user-attachments/assets/767136fb-535f-46f1-b68f-59f9f5a7505b)

![image](https://github.com/user-attachments/assets/6ae56657-0270-42e8-9ff1-0268184333e3)



# Consultas SQL
Finalmente, puedes ejecutar algunas consultas SQL para verificar los datos en la base de datos.

 ➡ ACTORES: 
 
 ![image](https://github.com/user-attachments/assets/acdf00be-6155-4891-ae97-0326d756f3e2)

 ➡ ACTUACIONES: 
 
 ![image](https://github.com/user-attachments/assets/c6f83df8-8a1f-4743-ae38-c713073ee7bb)

 ➡ EPISODIOS: 
 
 ![image](https://github.com/user-attachments/assets/4114ab0f-6973-427f-b9f7-9dc34cd05328)

 ➡ SERIES: 
 
 ![image](https://github.com/user-attachments/assets/80dfdf34-4c2e-41df-a9c2-1ca92d035bb6)

# Conclusión
🤓 Este proyecto proporciona una estructura robusta y eficiente para la gestión de datos de una plataforma de streaming como Netflix utilizando MySQL.
 
✨ A través de la creación de varias tablas relacionadas, se logra una organización clara y accesible de la información sobre series, contenido, actores y sus respectivas actuaciones. 

✨ La implementación de esta base de datos permite realizar consultas complejas y obtener datos relevantes de manera rápida y eficiente, facilitando el análisis y la toma de decisiones. 

✨ Además, el diseño modular y escalable de la base de datos garantiza su capacidad para adaptarse y crecer con futuras necesidades. 

✨ Este proyecto no solo sirve como una valiosa herramienta de almacenamiento y gestión de datos, sino que también ofrece una base sólida para futuros desarrollos y análisis en el ámbito del streaming de contenidos.



