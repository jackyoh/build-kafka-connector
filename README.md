### How to build the Kafka Connector worker project?

```
$ gradle clean
$ gradle jar packageDistribution
```

### How to running the Kafka Connector worker?

1.Uncompress zip file for kafka-worker-dir
```
$ unzip kafka-worker-dir.zip
```

2.Please setting the connect-distributed.properties file
```
$ vi config/connect-distributed.properties
```

3.Below running the Kafka Connector Worker command
```
$ cd kafka-worker-dir/bin
$ ./connect-distributed ../config/connect-distributed.properties
```