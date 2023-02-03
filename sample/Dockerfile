FROM ubuntu
WORKDIR /app
RUN apt-get update && sudo apt install default-jre
COPY . .
RUN javac helloworld.javac
COPY /app/helloworld.class .
CMD ["java", "helloworld" ]


