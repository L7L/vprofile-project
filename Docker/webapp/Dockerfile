FROM  openjdk:8 AS Build_java
RUN apt update && apt install maven -y
CMD mkdir target
COPY source dest  C:\Users\rsjat\Downloads\Devops_project\vprofile-project\src  target
RUN  cd target  &&  mvn install
