## Infrastruttura Kafka + Zookeper

Questo progetto contiene il file yaml per docker compose per la creazione dell'infrastruttura Kafka (singola istanza) + Zookeper (singola istanza)

### Esecuzione

Per avviare l'infrastruttura è sufficiente lanciare il comando

`docker-compose -f Kafka/zk-single-kafka-single.yml up`

### Versioni immagini docker

Zookeeper: 3.4.9
Apache Kafka: 5.5.1
