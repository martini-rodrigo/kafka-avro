## kafka avro is project with generic serializer kafka

#### Apache Avro is a data serialization system. It uses JSON for defining data types/protocols and serializes data in a compact binary format. In the following tutorial, we will configure, build and run an example in which we will send/receive an Avro message to/from Apache Kafka using Apache Avro, Spring Kafka, Spring Boot and Maven.

https://codenotfound.com/spring-kafka-apache-avro-serializer-deserializer-example.html

```
{
  "namespace": "br.com.lelo.avro",
  "type": "record",
  "name": "User",
  "fields": [
    {
      "name": "name", 
      "type": "string"
    },
    {
      "name": "favorite_number",  
      "type": ["int", "null"]
    },
    {
      "name": "favorite_color", 
      "type": ["string", "null"]
    }
  ]
}
```

- mvn generate-resources to generate User.java
