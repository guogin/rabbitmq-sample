# RabbitMQ Sample

## Set up the RabbitMQ Broker
Run the command
```shell
$ docker run -d --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3-management
```

## Run the Application

## Visit RabbitMQ Admin Page
Visit http://localhost:15672

The user/password is guest/guest