# Use the previously created aem-base-image
FROM aem-base-image

# Expose AEM Publisher in port 4503
EXPOSE 4503

# Make the container start always in Publisher mode with Port 4503
ENTRYPOINT ["java", "-jar", "cq-quickstart.jar", "-Dsling.run.modes=publisher", "-p", "4503"]