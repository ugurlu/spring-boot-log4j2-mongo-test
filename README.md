
```
gradle bootrun
```

```
12:29:26.109 [st:27017] INFO  o.m.d.connection - Opened connection [connectionId{localValue:1, serverValue:352}] to localhost:27017
12:29:26.109 [st:27017] INFO  o.m.d.connection - Opened connection [connectionId{localValue:2, serverValue:351}] to localhost:27017
12:29:26.125 [st:27017] INFO  o.m.d.cluster - Cluster description not yet available. Waiting for 30000 ms before timing out
2022-02-08 12:29:26,125 cluster-ClusterId{value='620237f68befcb4b8592eb9c', description='null'}-localhost:27017 ERROR Recursive call to appender mongodb
12:29:26.489 [main] INFO  o.m.d.cluster - Cluster created with settings {hosts=[localhost:27017], mode=SINGLE, requiredClusterType=UNKNOWN, serverSelectionTimeout='30000 ms'}
```
