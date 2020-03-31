> This project is a study case of microservices comunication in a ecommerce context. This ecommerce sell's Tickets for events. The **code** of microservices projects are *distributed* on another repositories, cited in this text.

# tickets-ecommerce

Source code links:

- [Authentication microservice](https://github.com/PgPedroGabriel/auth-microservice)
- [Events Tickets microservice](https://github.com/PgPedroGabriel/events-tickets-microservice)
- [Order microservice](https://github.com/PgPedroGabriel/order-microservice)
- [Payment microservice](https://github.com/PgPedroGabriel/payment-worker-microservice)

### Tecnologies used to develop this project

- [x] Nodejs
- [x] Yarn
- [x] Docker
- [x] Postgres
- [x] RabbitMQ

### Pending implementations for all microservices

- [ ] Use a alarm notification when errors occur
- [ ] Docker structure for Google Cloud Platform - Cloud Build for first pipeline of CI
- [ ] Use containers to deploy on Kubernets cluster on GCP


### Sales microservices Context

![bounded context](/images/ddd1.png "Bounded context")

### Sales microservices Context Map

![context map](/images/ddd2.png "context map")

### Sales microservies Context Architecture

*Todo*