FROM openjdk:8
ADD target/standalone-1.0.jar /standalone-1.0.jar
COPY data .
CMD ["java","-jar","/standalone-1.0.jar"]
