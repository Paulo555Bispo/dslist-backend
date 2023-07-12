# dslist-backend
Projeto DSList - Intensivão Java Spring

Modelo de domínio DSList
![image](https://github.com/Paulo555Bispo/dslist-backend/assets/63209799/bd2f94e7-bd9f-451f-8759-dca8208a1e20)

Trechos de código
Plug-in Maven

<plugin>
	<groupId>org.apache.maven.plugins</groupId>
	<artifactId>maven-resources-plugin</artifactId>
	<version>3.1.0</version> <!--$NO-MVN-MAN-VER$ -->
</plugin>

application.properties

spring.profiles.active=${APP_PROFILE:test}
spring.jpa.open-in-view=false

cors.origins=${CORS_ORIGINS:http://localhost:5173,http://localhost:3000}
