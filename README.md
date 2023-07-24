# RabbitMQ Go 101 - Hello World

## Overview
This is a simple Go project that demonstrates the basic usage of RabbitMQ, a message-broker software that allows applications to communicate with each other through a messaging queue. The project consists of two files: `send.go` responsible for sending a message to the queue, and `receive.go` responsible for receiving and processing the message.

## What is RabbitMQ?
RabbitMQ is an open-source message-broker software that facilitates message queuing between different applications. It allows decoupling of sender and receiver, ensuring seamless communication and scalability. RabbitMQ is widely used for building distributed systems and microservices architectures due to its reliability, flexibility, and support for multiple messaging protocols.

## How to Run the Project
1. **Install RabbitMQ:** Before running the project, ensure you have RabbitMQ installed on your system. You can download and install it from the official website: https://www.rabbitmq.com/download.html

2. **Install Dependencies:** The project uses the `rabbit/amqp` Go package for interacting with RabbitMQ. To install the dependencies, run the following command in your project directory:

    ```
    github.com/rabbitmq/amqp091-go
    ```

3. **Sending a Message:** To send a message to the queue, run the `send.go` file:

    ```
    go run send.go
    ```

   The message will be sent to the RabbitMQ queue.

4. **Receiving a Message:** To receive and process the message from the queue, run the `receive.go` file:

    ```
    go run receive.go
    ```

   The application will listen to the queue and process any messages received.

## Conclusion
Congratulations! You have successfully run a basic RabbitMQ Go project that demonstrates sending and receiving messages using a message queue. This simple example lays the foundation for more complex applications that leverage RabbitMQ for asynchronous communication between components.

Feel free to explore RabbitMQ's extensive documentation and advanced features to build robust distributed systems with Go.

Happy coding! 🚀
