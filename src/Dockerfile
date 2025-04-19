FROM openjdk:11-jre-slim
COPY src/main/java/test.java /usr/src/app/
WORKDIR /usr/src/app/
RUN javac test.java
CMD ["java", "Test"]
