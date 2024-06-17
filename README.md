# kafka-cab-app
kafka-cab-app

Download:- https://kafka.apache.org/downloads


- start Zookeeper:- C:\kafka\bin\windows> .\zookeeper-server-start.bat ..\..\config\zookeeper.properties
- Start Kafka server:- C:\kafka\bin\windows> .\kafka-server-start.bat ..\..\config\server.properties
- Create a Topic:- C:\kafka\bin\windows> .\kafka-topics.bat --create --topic quickstart-events --bootstrap-server localhost:9092
- Write events to Kafka Topic:- C:\kafka\bin\windows> .\kafka-console-producer.bat  --topic quickstart-events --bootstrap-server localhost:9092
- Read events from Kafka Topic :- C:\kafka\bin\windows> .\kafka-console-consumer.bat --topic quickstart-events --from-beginning --bootstrap-server localhost:9092
