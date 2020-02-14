# JHipster generated Docker-Compose configuration

## Usage

Launch all your infrastructure by running: `docker-compose -f docker-compose.yml up -d`.


make sure to create docker images of each project by running: `mvnw package -Pdev verify jib:dockerBuild`
note: -Pdev for development, -Pprod for production.
## Configured Docker services

### Service registry and configuration server:

- [JHipster Registry](http://localhost:8761)

### Applications and dependencies:

- IJSchoolManagerAdministrationService (microservice application)
- IJSchoolManagerAdministrationService's mysql database
- IJSchoolManagerGateway (gateway application)
- IJSchoolManagerGateway's mysql database

### Additional Services:

- Kafka
- Zookeeper
- [Keycloak server](http://localhost:9080)
