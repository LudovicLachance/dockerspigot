FROM openjdk:8
WORKDIR /spigot_data
COPY ./spigot_artifacts/spigot* /spigot_run/spigot.jar

EXPOSE 25565
EXPOSE 25575
ENTRYPOINT [ "java", "-jar", "/spigot_run/spigot.jar" ]