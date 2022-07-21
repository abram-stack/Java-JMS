# Java-JMS

Distributed System using Java JMS(Java Messaging System)

Architecture of JMS programming: 
JMS uses broker for sending and receiving messages. In this case we are using the Apache Tomcat ActiveMQ broker.

There is two type of sending messages with JMS:
a. Point-To-Point(Using Queue)
b. Publisher and subscribe(Using 

Procedure of simple JMS program:
1. Using ConnectionFactory
2. Create Connection
3. Create Session
4. Create Publisher/Sender
5. Start Connection
6. Send/Receive
7. Close Connection
