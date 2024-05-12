# springboot-kafka-docker

This application is a demo example for how to implement Kafka consumer and producer to read and write data from kafka.
Use the confluent docker-compose

#### To start and stop kafka on docker use following commands:
1.  docker compose -f zk-single-kafka-single.yml up
2.  docker compose -f zk-single-kafka-single.yml down

Then start the SpringBoot application.

Via Postman, use the "/publish" endpoint and "message" parameter to send messages via kafka producer.