# 1. Imagen base con Java 21
FROM eclipse-temurin:21-jdk-alpine

# 2. Directorio de trabajo dentro del contenedor
WORKDIR /app

# 3. Copiar el archivo ejecutable (JAR) a la caja
COPY target/alquiler-service-0.0.1-SNAPSHOT.jar app.jar

# 4. Abrir la ventana para que el tráfico entre
EXPOSE 8080

# 5. Comando para encender el motor
ENTRYPOINT ["java", "-jar", "app.jar"]