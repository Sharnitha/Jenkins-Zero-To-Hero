# You can change this base image to anything else
# But make sure to use the correct version of Java
FROM adoptopenjdk/openjdk11:alpine-jre

# Simply the artifact path
ARG artifact=spring-boot-web/spring-boot-web.jar

RUN pwd

WORKDIR /home/Sharni/actions-runner/_work/Jenkins-Zero-To-Hero/Jenkins-Zero-To-Hero/java-maven-sonar-argocd-helm-k8s/spring-boot-app/

RUN ls 

COPY ${artifact} app.jar

# # This should not be changed
ENTRYPOINT ["java","-jar","app.jar"]
