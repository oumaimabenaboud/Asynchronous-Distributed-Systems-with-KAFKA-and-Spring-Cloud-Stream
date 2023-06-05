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
![Capture d'écran 2023-06-05 163907](https://github.com/oumaimabenaboud/Asynchronous-Distributed-Systems-with-KAFKA-and-Spring-Cloud-Stream/assets/120368654/1e6f5a13-403a-4652-b408-52db910c8bfd)

 - Démarrer les conteneurs docker : zookeeper et kafka-broker
![Capture d'écran 2023-06-05 165018](https://github.com/oumaimabenaboud/Asynchronous-Distributed-Systems-with-KAFKA-and-Spring-Cloud-Stream/assets/120368654/fe124f33-ec6b-453d-ae20-860919987a46)

 - Tester avec Kafka-console-producer et kafka-console-consumer
![Capture d'écran 2023-06-05 165401](https://github.com/oumaimabenaboud/Asynchronous-Distributed-Systems-with-KAFKA-and-Spring-Cloud-Stream/assets/120368654/74218a26-5205-45b3-bf92-2b680d936ad3)

3. En Utilisant KAFKA et Stpring Cloud Streams, Créer :
- Un Service Producer KAFKA via un Rest Controler
![Capture d'écran 2023-06-05 165727](https://github.com/oumaimabenaboud/Asynchronous-Distributed-Systems-with-KAFKA-and-Spring-Cloud-Stream/assets/120368654/0f1fc502-4551-4d74-b468-705ce219a721)

- Un Service Consumer KAFKA
![Capture d'écran 2023-06-05 165801](https://github.com/oumaimabenaboud/Asynchronous-Distributed-Systems-with-KAFKA-and-Spring-Cloud-Stream/assets/120368654/cb052d93-6a3f-4621-ab2d-8c5f1a892732)

- Un Service Supplier KAFKA
![Capture d'écran 2023-06-05 165836](https://github.com/oumaimabenaboud/Asynchronous-Distributed-Systems-with-KAFKA-and-Spring-Cloud-Stream/assets/120368654/db8005f5-b993-4590-8bf0-800b40ff0cc4)

- Un Service de Data Analytics Real Time Stream Processing avec Kaflka Streams
![Capture d'écran 2023-06-05 165924](https://github.com/oumaimabenaboud/Asynchronous-Distributed-Systems-with-KAFKA-and-Spring-Cloud-Stream/assets/120368654/16a9e9b5-d521-49f0-99f3-4e173968303b)

- Une application Web qui permet d'afficher les résultats du Stream Data Analytics en temps réel
![Capture d'écran 2023-06-05 194851](https://github.com/oumaimabenaboud/Asynchronous-Distributed-Systems-with-KAFKA-and-Spring-Cloud-Stream/assets/120368654/205d898e-5c13-4102-9ce1-c12852dea665)
