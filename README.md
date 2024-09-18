# Helicopter maintenance service
Intermediate maintenance is more often performed at a maintenance centre due to the more specialised level of tools, equipment and training required. This is an educational backend solution on ASP.NET Core is designed specifically for such a company.

####  Scheme of microservices:
<img width="1332" alt="Снимок экрана 2024-07-15 в 11 54 37" src="https://github.com/user-attachments/assets/402f1e0e-fc32-4110-8a8b-291574278846">

#### Description:
My first project is based on microservice architecture.
All microservices, with the exception of Gateway, are written in the spirit of clien architecture.

The Gateway microservice uses the Refit wrapper library on top of HttpClient.
PostgreSQL is used as databases. To work with the database, use the Entity Framework Core.
RabbitMQ is used as a message broker. Inside the services, the MassTransit library is used to interact with the broker.

Gateway — https://github.com/nikitaberezhko/Gateway
Order — https://github.com/nikitaberezhko/Order
Tracking — https://github.com/nikitaberezhko/Tracking
Identity — https://github.com/nikitaberezhko/Identity

