# ConfigServer

Añadir la dependencia
spring-cloud-config-server

Añadir en propertis:
El puerto: server.port=2222
El nombre: spring.config.name=configserver
La ruta a github: spring.cloud.config.server.git.uri=https://github.com/CapSteam-Grupo-2/config-microserver.git


En el runner añadir la anotacion
@EnableDiscoveryClient