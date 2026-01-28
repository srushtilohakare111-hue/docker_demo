from maven:3.8.5-openjdk-17
workdir /opt
copy . /opt/
run mvn clean package -Dskiptests
expose 8080
cmd ["java", "-jar", "target/student-registration-backend-0.0.1-SNAPSHOT.jar"]]