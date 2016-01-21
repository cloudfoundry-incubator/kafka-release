# kafka-release

### Dev-Ops

##### Adjust Partition Count ([Reference](https://kafka.apache.org/081/ops.html))
```
bin/kafka-topics.sh --zookeeper zk_host:port/chroot --alter --topic my_topic_name --partitions 40
```

