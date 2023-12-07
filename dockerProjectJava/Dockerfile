FROM java:8u111-jdk-alpine
COPY . /usr/src/myapp
WORKDIR /usr/src/myapp/src
RUN javac Main.java
CMD ["java", "Main"]