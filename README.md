# publisher

Reflection:
    a. The number of data that will be sent to the message broker is 5 datas.
    b. It means the AMQP service of publisher will be running in the same address as subscriber

    docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.13-management

RabbitMQ Screen:
![alt text](image.png)

