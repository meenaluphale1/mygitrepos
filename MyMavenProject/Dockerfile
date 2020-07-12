FROM java:8

RUN apt-get -y install git

RUN git clone https://meenaluphale1:RitwikUphale123@github.com/mygitrepos mygitfolder

COPY . /mygitfolder
WORKDIR /home/mygitfolder

RUN javac helloWorld.java

CMD ["java", "helloWorld"]


#FROM maven:3.5.4-jdk-8-alpine as maven

#COPY ./pom.xml ./pom.xml

#COPY ./src ./src

#RUN mvn dependency:go-offline -B

#RUN mvn package

#FROM openjdk:8u171-jre-alpine

#WORKDIR /mygitrepos

#COPY --from=maven target/MyMavenProject-*.war ./MyMavenProject.war

#CMD ["java", "-war", "./MyMavenProject.war"]