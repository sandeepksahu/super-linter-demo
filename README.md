## command to run application locally
mvn spring-boot:run

### url to test application
http://localhost:8080

## command to run super-linter locally
docker run -e RUN_LOCAL=true -e DEFAULT_WORKSPACE=/tmp/lint -v $(pwd):/tmp/lint github/super-linter:slim-v4
