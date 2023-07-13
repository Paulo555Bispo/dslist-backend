# dslist-backend
<p align="center">
Projeto DSList - Intensivão Java Spring</p>

<p align="center">
<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

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
