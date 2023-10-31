ORDER MANAGEMENT API
Order management api is an appilcation which will do create, update and retrieve orders.
Here i consider this application as large scale application, so i followed CQRS(Command Query Responsibility Segregation) design pattern. ordermanagemetdesign

Prerequisites
JDK 8 and above
Intellij or STS
Axon Server
Apache Kafka
Mongo DB
What is Axon Server
Axon Server is zero configuration message router and an event store. It serves two purposes

it routes messages (commands, queries, and events) between distributed components (microservices) in a location transparent way.
it stores events allowing distributed applications to have a single source of truth.
To Run

AxonServer-4.5.12>java -jar axonserver.jar
We can see Axon Server dashboard on port number http://localhost:8024 axonscreenshot

What is Kafka
Apache Kafka is an open-source distributed event streaming platform.

To Run Kafka in local system

bin\windows>zookeeper-server-start.bat D:\tools\kafka\config\zookeeper.properties
bin\windows>kafka-server-start.bat D:\tools\kafka\config\server.proper
