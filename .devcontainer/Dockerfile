FROM mcr.microsoft.com/devcontainers/base:bullseye
RUN apt-get update
RUN apt-get -y install openjdk-11-jdk graphviz wget
RUN wget https://sourceforge.net/projects/plantuml/files/plantuml.jar/download -O /usr/local/bin/plantuml.jar 
RUN chmod +x /usr/local/bin/plantuml.jar
# RUN apt-get -y install libxrender1 libxtst6 libxi6
# RUN java -jar /usr/local/bin/plantuml.jar -version