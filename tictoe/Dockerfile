FROM openjdk:8
COPY src/tictoe.java /tmp
WORKDIR /tmp
RUN ["javac","tictoe.java"]
ENTRYPOINT ["java","tictoe"]