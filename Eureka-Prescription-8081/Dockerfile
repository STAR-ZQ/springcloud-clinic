FROM java:8
COPY target/*.jar prescription.jar
RUN bash -c "touch /prescription.jar"
EXPOSE 8081
ENTRYPOINT ["java","-jar","prescription.jar"]