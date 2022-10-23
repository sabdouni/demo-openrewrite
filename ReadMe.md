./mvnw org.openrewrite.maven:rewrite-maven-plugin:4.36.0:run \
-Drewrite.recipeArtifactCoordinates=org.openrewrite.recipe:rewrite-spring:4.29.0 \
-DactiveRecipes=org.openrewrite.java.spring.boot2.SpringBoot1To2Migration

./mvnw org.openrewrite.maven:rewrite-maven-plugin:4.36.0:run \
-Drewrite.recipeArtifactCoordinates=org.openrewrite.recipe:rewrite-spring:4.29.0 \
-DactiveRecipes=org.openrewrite.java.spring.NoRequestMappingAnnotation