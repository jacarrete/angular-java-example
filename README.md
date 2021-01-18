# angular-java-example
Project to develop and build Angular application with Java

----------------------
# JAVA

## Run Java Code on 8080

mvn clean install

java -jar target/users-0.0.1-SNAPSHOT.jar

### List all users

http://localhost:8080/api/users

### DB h2

http://localhost:8080/h2-console

jdbc:h2:mem:testdb

----------------------
# ANGULAR

## Run Angular on port 4200

cd /src/main/ui

npm install

npm start

http://localhost:4200