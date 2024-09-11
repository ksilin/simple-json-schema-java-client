## simple-json-schema-java-client

### using generic JSON Schema type - JsonNode

### run it

`./gradlew run`

### changing the main class

change the `mainClassName` in `build.gradle.kts`: 

```
application {
    mainClass.set("com.example.ConsumerApp")
    //mainClass.set("com.example.ProducerApp")
}
```

### setting env vars:

fill out the `.env_*` file and apply it. E.g. 

`set -a; source .env_ccloud; set +a`

