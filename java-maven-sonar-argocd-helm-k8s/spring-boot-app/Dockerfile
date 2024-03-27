# You can change this base image to anything else
# But make sure to use the correct version of Java
FROM adoptopenjdk/openjdk11:alpine-jre

# Simply the artifact path
ARG artifact=spring-boot-web/spring-boot-web.jar

RUN ls

WORKDIR /home/Sharni/actions-runner/_work/Jenkins-Zero-To-Hero/Jenkins-Zero-To-Hero/spring-boot-app/spring-boot-web

RUN ls 

COPY spring-boot-web.jar app.jar

# # This should not be changed
ENTRYPOINT ["java","-jar","app.jar"]
