# Helicopter maintenance service

<img width="1332" alt="Снимок экрана 2024-07-15 в 11 54 37" src="https://github.com/user-attachments/assets/402f1e0e-fc32-4110-8a8b-291574278846">

My first project is based on microservice architecture.
The Gateway microservice uses the Refit wrapper library on top of HttpClient.
PostgreSQL is used as databases. To work with the database, use the Entity Framework Core.
RabbitMQ is used as a message broker. Inside the services, the Mass Transit library is used to interact with the broker.
