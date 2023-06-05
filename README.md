# Asynchronous-Distributed-Systems-with-KAFKA-and-Spring-Cloud-Stream
Asynchronous Distributed Systems with KAFKA and Spring Cloud Stream
1. Télécharger Kafka
- Démarrer Zookeeper
![image](https://github.com/oumaimabenaboud/Asynchronous-Distributed-Systems-with-KAFKA-and-Spring-Cloud-Stream/assets/120368654/3955e1b5-8d1a-49e2-966e-78196164bba3)

- Démarrer Kafka-server
![image](https://github.com/oumaimabenaboud/Asynchronous-Distributed-Systems-with-KAFKA-and-Spring-Cloud-Stream/assets/120368654/78692a8a-6bf6-48ca-94f1-19625433ddf0)

- Tester avec Kefka-console-producer et kafka-console-consumer
![image](https://github.com/oumaimabenaboud/Asynchronous-Distributed-Systems-with-KAFKA-and-Spring-Cloud-Stream/assets/120368654/d22b6208-36bb-4147-9fa6-2af2bae22ced)

2. Avec Docker (voir https://developer.confluent.io/quickstart/kafka-docker/)
 - Créer le fichier docker-compose.yml
 - Démarrer les conteneurs docker : zookeeper et kafka-broker
 - Tester avec Kafka-console-producer et kafka-console-consumer
3. 
En Utilisant KAFKA et Stpring Cloud Streams, Créer :
- Un Service Producer KAFKA via un Rest Controler
- Un Service Consumer KAFKA
- Un Service Supplier KAFKA
- Un Service de Data Analytics Real Time Stream Processing avec Kaflka Streams
- Une application Web qui permet d'afficher les résultats du Stream Data Analytics en temps réel
