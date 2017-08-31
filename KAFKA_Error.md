# kafka-server:unrecognized service

## [lauch cloudera express error - kafka-server:unrecognized service](https://community.cloudera.com/t5/Hadoop-101-Training-Quickstart/CDH5-8-lauch-cloudera-express-error-kafka-server-unrecognized/td-p/44574)
 
The "Launch Cloudera Express" shortcut on the Desktop? That's expected to
emit a message about Kafka. Kafka is not installed in the VM by default,
but if you do install it, it will be taken care of in the migration just
like the other CDH services. So what you're seeing is it checking and then
just ignoring it.

The HBase and Hive services should start up (or at least fail with more
helpful messages, like telling you that you need to start HDFS and YARN
first respectively). I'd suggest clicking on those services, looking at the
processes tab, and then seeing what errors are given in the logs.

## [Install Kafka](https://www.cloudera.com/documentation/kafka/latest/topics/kafka_installing.html)
### [Cloudera Distribution of Apache Kafka Overview](https://www.cloudera.com/documentation/kafka/latest/topics/kafka.html)
### [Using Kafka](https://www.cloudera.com/documentation/kafka/latest/topics/kafka_using.html)
### [Cloudera Distribution of Apache Kafka Versions](https://www.cloudera.com/documentation/kafka/latest/topics/kafka_packaging.html#concept_tm5_gx3_dp)
