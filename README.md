flume-ng-kafka-sink
================

This project is used for [flume-ng](https://github.com/apache/flume) to communicate with [kafka 0.8.1](http://kafka.apache.org/).

Configuration of Kafka Sink
----------

    agent_log.sinks.kafka.type = org.apache.flume.sink.kafka.KafkaSink
    agent_log.sinks.kafka.channel = all_channel
    agent_log.sinks.kafka.metadata.broker.list = 127.0.0.1:9092
    agent_log.sinks.kafka.topic = all
    agent_log.sinks.kafka.producer.type = sync

Speical Thanks
---------

In fact I'm a newbie in Java. I have learnt a lot from [flumg-ng-rabbitmq](https://github.com/jcustenborder/flume-ng-rabbitmq). Thanks to [Jeremy Custenborder](https://github.com/jcustenborder).

