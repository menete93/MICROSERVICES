#adicionar ou imagem do puxar jdk
FROM openjdk:25-ea-21-slim
# Identificar o mantedor da App
LABEL maintainer=eazybytes.com

#Copiar o jar e gerar um container
COPY target/accounts-0.0.1-SNAPSHOT.jar accounts-0.0.1-SNAPSHOT.jar

#executar a app
ENTRYPOINT ["java","-jar","accounts-0.0.1-SNAPSHOT.jar"]