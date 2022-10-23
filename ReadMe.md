## Updgrade to Spring Boot 2.X
Run the following command
```
./mvnw org.openrewrite.maven:rewrite-maven-plugin:4.36.0:run \
-Drewrite.recipeArtifactCoordinates=org.openrewrite.recipe:rewrite-spring:4.29.0 \
-DactiveRecipes=org.openrewrite.java.spring.boot2.SpringBoot1To2Migration
```
## Change @RequestMapping to @GetMapping & @PostMapping
Run the following command
```
./mvnw org.openrewrite.maven:rewrite-maven-plugin:4.36.0:run \
-Drewrite.recipeArtifactCoordinates=org.openrewrite.recipe:rewrite-spring:4.29.0 \
-DactiveRecipes=org.openrewrite.java.spring.NoRequestMappingAnnotation
```
