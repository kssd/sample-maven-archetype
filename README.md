sample-maven-archetype
======================
  [Maven-Archetype-Page](www-mvn-arch)   

Sample maven archetype with commonly used stuff as:
    1. Slf4J + Logback
    2. TestNG
    3. Jmockito

Command Used for generating this archetype stencil
--------------------------------------------------

```
mvn archetype:generate -DartifactId=sample-maven-archetype -Dversion=1.0.0-SNAPSHOT \
    -DgroupId=in.sangram.archetype \
    -DarchetypeArtifactId=maven-archetype-archetype \
    -DinteractiveMode=false
```

[www-mvn-arch]: http://maven.apache.org/guides/mini/guide-creating-archetypes.html
