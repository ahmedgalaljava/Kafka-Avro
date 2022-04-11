

Project contains Kafka Producer/Consumer examples.

1-The AvroProductDemo class takes following Program Arguments:

'KafkaAvroMessage avro2.csv'

2-The AvroConsumer class takes following Program Arguments:
'KafkaAvroMessage AvroProducer'

Steps :
1- Start the all services in order :
E:\dwh\confluent-6.1.1\bin\windows>zookeeper-server-start.bat ../../etc/kafka/zookeeper.properties
E:\dwh\confluent-6.1.1\bin\windows>kafka-server-start.bat ../../etc/kafka/server.properties
E:\dwh\confluent-6.1.1\bin\windows>schema-registry-start ../../etc/schema-registry/schema-registry.properties

2- Run the AvroProductDemo .

3- Run AvroProductDemo