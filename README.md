### Apache Flink First Steps

On a machine JDK>11, do a maven clean compile with `./mvnw clean compile` and run **Main** class with this vm argument:

```
--add-opens java.base/java.lang=ALL-UNNAMED
```



links:
- https://nightlies.apache.org/flink/flink-docs-release-1.20/docs/learn-flink/datastream_api/