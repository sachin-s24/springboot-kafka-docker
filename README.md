# springboot-kafka-docker

This application is a demo example for how to implement Kafka consumer and producer to read and write data from kafka.
Use the confluent docker-compose

To start and stop kafka on docker run following:
docker compose -f zk-single-kafka-single.yml up
docker compose -f zk-single-kafka-single.yml down

Start the SpringBoot application
Using the Postman, hit the publish endpoint to send messages via kafka producer