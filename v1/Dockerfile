FROM eclipse-temurin:17-jdk
COPY . .
RUN ./mvnw clean package -DskipTests
RUN mv target/*.jar app.jar
CMD ["java","-jar","app.jar"]