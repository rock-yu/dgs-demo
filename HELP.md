# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Gradle documentation](https://docs.gradle.org)
* [Spring Boot Gradle Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.1.3/gradle-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.1.3/gradle-plugin/reference/html/#build-image)

### Additional Links
These additional references should also help you:

* [Gradle Build Scans – insights for your project's build](https://scans.gradle.com#gradle)



### Test application
```
curl -XPOST 'http://localhost:8080/graphql' \
	-H 'Content-Type: application/json' \
	--data-raw '{"query":"{\n    shows {\n        title\n        releaseYear\n    }\n}\n"}' 
```