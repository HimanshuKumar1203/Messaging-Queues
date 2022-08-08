# Messaging-Queues

Sometimes we need to do asynchronous processing eg. to send sms, email, process orders or pass information between services. This type of background processing is simply not a task that traditional RDBMS is best suited to solve. With a message queue, we can efficiently support a significantly higher volume of concurrent messages, messages are pushed in real-time instead of periodically polled, messages are automatically cleaned up after being received and we don’t need to worry about any deadlocks or race conditions.
In short, Message Queues are systems that let you have fault-tolerant, distributed, decoupled, service oriented etc, etc. architecture.

# Basic message - Queues
In modern cloud architecture, applications are decoupled into smaller, independent building blocks that are easier to develop, deploy and maintain. Message queues provide communication and coordination for these distributed applications. Message queues can significantly simplify coding of decoupled  applications, while improving performance, reliability and scalability.used Message queues provide communication and coordination for these distributed applications. Message queues can significantly simplify coding of decoupled applications, while improving performance, reliability and scalability. You 
can also combine message queues with Pub/Sub messaging in a fanout design pattern.

# Why message queues are used ?
Message queues provide communication and coordination for these distributed applications. Message queues can significantly simplify coding of decoupled applications, while improving performance, reliability and scalability. You can also combine message queues with Pub/Sub messaging in a fanout design pattern. 
Image result for why message queues are used Message Queue is a reliable asynchronous messaging service that conforms to the JMS 1.1 specification. In addition, to provide for the needs of large-scale enterprise deployments, Message Queue provides a host of features that exceed JMS specification requirements.
### There are several real life use cases of Message Queues. Below are some points to use Messaging-Queues.
* DECOUPLING
* SCALABILITY
* PERSISTENCE
* TRAFFIC SPIKES
* MONITORING
* ASYNCHRONOUS COMMUNICATION
* BATCH PROCESS 
* ORDERING 
* DELIVERY
* DATA FLOW

#   What are popular tools of Messages-Queue ?
Kafka, RabbitMQ, Amazon SQS, Celery, and ActiveMQ are the most popular tools in the category Message Queue. High-throughput is the primary reason developers pick Kafka over its competitors, while "It's fast and it works with good metrics/monitoring" is the reason why RabbitMQ was chosen.

### Some of the Top Message Queue Software
* MuleSoft Anypoint Platform.
* IBM MQ.
* Apache Kafka.
* Apache Qpid.
* Azure Scheduler.
* IBM Cloud Pak for Integration.
* RabbitMQ.
* Azure Queue Storage.

# What is Enterprise Message Bus ?
### What are message buses?
A Message Bus is a combination of a common data model, a common command set, and a messaging infrastructure to allow different systems to communicate through a shared set of interfaces.

## Reference
* https://aws.amazon.com/message-queue/
* https://medium.com/@ranjeetvimal/message-queues-10-reasons-to-use-message-queuing-1923277a2e7f
