# Usa la imagen base de OpenJDK 17 en una versión ligera
FROM openjdk:17-jdk-slim

# Define la variable ARG para el archivo JAR
ARG JAR_FILE=demo/target/demo-0.0.1-SNAPSHOT.jar

# Copia el archivo JAR al contenedor
COPY ${JAR_FILE} app_videojuego.jar

# Expone el puerto 8080
EXPOSE 8080

# Define el comando de inicio para ejecutar la aplicación
CMD ["java", "-jar", "app_videojuego.jar"]
