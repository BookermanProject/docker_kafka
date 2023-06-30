# docker_kafka

kafka 구성 도커 
- Kafka Cluster(Broker 3) + ZooKeeper 1
- 컨슈머 그룹 1 → 그룹 내에 5개의 컨슈머 스레드를 두어 파티션에서 이벤트 메시지 조회하여 처리하도록 구성.
