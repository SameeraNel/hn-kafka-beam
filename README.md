Build the following with Apache Beam using Flink runner (but for the demo you can use DirectRunner).
- Build a Kafka streamer that reads from 1 topic and publish into 2 different topics
- Input topic will have a payload of first name, last name, date of birth.
- Logic: when age is even number, publish to topic: CustomerEVEN, if age is odd number, publish to topic: CustomerODD
- Build using Maven/Gradle and Spring Boot.
 
Bonus points:

- Containerised
- Unit tested
- JDK 17+
