FROM tomcat:8.0-alpine
COPY MyMavenProject.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]/MyMavenProject.war


#FROM maven:3.5.4-jdk-8-alpine as maven

#COPY ./pom.xml ./pom.xml

#COPY ./src ./src

#RUN mvn dependency:go-offline -B

#RUN mvn package

#FROM openjdk:8u171-jre-alpine

#WORKDIR /mygitrepos

#COPY --from=maven target/MyMavenProject-*.war ./MyMavenProject.war

#CMD ["java", "-war", "./MyMavenProject.war"]