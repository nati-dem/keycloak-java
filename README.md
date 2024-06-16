# keycloak-java

Run keycloak server
- use docker script in keycloak-server folder

- Run command to build image <br/><br/>
	docker build -t mykeycloak_img .

- Run command to run docker container in dev mode  <br/><br/>
	docker run --name mykeycloak_img -p 8080:8080 -e KEYCLOAK_ADMIN={admin-username} -e KEYCLOAK_ADMIN_PASSWORD={admin-password} -e KC_DB_USERNAME={db-username} -e KC_DB_PASSWORD={db-password} mykeycloak_img start-dev
