FROM openjdk:8 as builder
COPY App.java /
RUN  javac App.java

FROM openjdk:8-jre
WORKDIR /app
COPY --from=builder App.class .
CMD ["java","App"]
