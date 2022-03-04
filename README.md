# Assessment Notes

## Buld & Run Application via Docker Image

---

From root of project, run via CLI:
`mvn clean package`
`docker build --tag sdet-assessment-image .`
`docker run --publish 8080:8080 sdet-assessment-image`

API will be available at localhost:8080.
