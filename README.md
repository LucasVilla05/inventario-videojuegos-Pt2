# inventario-videojuegos-Pt2
Este repositorio contiene el prototipo del sistema desarrollado como parte del trabajo práctico final para la cátedra de Seminario de Práctica de la Licenciatura en Informática – Universidad Siglo 21.

## 📌 Descripción

El sistema permite a los usuarios registrar, gestionar y controlar su inventario personal de videojuegos, evitando duplicados y facilitando recomendaciones personalizadas. Utiliza Java para el desarrollo del backend y MySQL para la persistencia de datos.

## 🛠️ Tecnologías

- Java 17
- JDBC
- MySQL
- IDE: IntelliJ IDEA / NetBeans
- Diagrama UML: Draw.io
- GitHub

## 📁 Estructura del proyecto

- `src/`: Clases Java base para el prototipo (Usuario, Videojuego, Conexion)
- `sql/`: Scripts de base de datos para crear, insertar y consultar registros
- `docs/`: Diagramas E-R y de clases en formato imagen

## 🚀 Cómo ejecutar

1. Crear la base de datos MySQL usando `sql/create_tables.sql`
2. Insertar datos de ejemplo desde `sql/insert_example.sql`
3. Compilar las clases Java en `src/`
4. Ejecutar desde consola o IDE

## 👤 Autor

Lucas Matías Villavicencio  
Estudiante de la Licenciatura en Informática  
Universidad Siglo 21

## 🔒 Consideraciones

Este sistema cumple con la Ley 25.326 de Protección de Datos Personales de Argentina. Se sugiere no utilizarlo con datos reales fuera de entornos de prueba.
