# Starting a broker

```console
bin/kafka-server-start.sh config/server.properties 
```

# Starting Zookeepers 

```console
bin/zookeeper-server-start.sh config/zookeeper.properties
```

# Creating a topc
```console
bin/kafka-topics.sh --create --topic topicName --zookeeper localhost:2181 --replication-factor 1 --partitions 1
```

# Viewing Topic Status

```console
bin/kafka-topics.sh --describe -- topic myTopic --zookeeper localhost:2181
```


