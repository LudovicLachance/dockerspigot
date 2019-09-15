FROM openjdk:8
RUN mkdir /spigot_build &&\
  cd /spigot_build &&\
  curl 'https://hub.spigotmc.org/jenkins/job/BuildTools/lastSuccessfulBuild/artifact/target/BuildTools.jar' > /spigot_build/BuildTools.jar;