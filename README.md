# Apache Kafka

kafka 구조도
- Kafka Cluster(Broker 3) + ZooKeeper 1
- 컨슈머 그룹 1 → 그룹 내에 5개의 컨슈머 스레드를 두어 파티션에서 이벤트 메시지 조회하여 처리하도록 구성.
  
<img width="919" alt="스크린샷 2023-06-09 오후 4 17 51" src="https://github.com/BookermanProject/docker_kafka/assets/68779402/4de3f666-54dd-4c7f-a638-2b9905cc3b96">
