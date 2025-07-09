# stonks
 Stock Trading Live App with Kafka


[User Interface (Angular)]
        ⬇ WebSocket

[Backend API (Spring Boot)]
        ⬇ Kafka Producer

[Kafka Broker (Apache Kafka)]
        ⬇ Kafka Consumer

[Trade Processor / DB Writer]


🧪 Features of the App
Users can buy/sell stocks.

Kafka used for:

Sending real-time trade updates.

Broadcasting stock price changes.

Angular frontend listens over WebSocket for live updates.

Spring Boot produces and consumes Kafka messages.

📦 Technologies Used
Frontend: Angular 17 + RxJS + WebSocket

Backend: Spring Boot + KafkaTemplate

Kafka: Apache Kafka (local or Confluent)

DB: MongoDB
