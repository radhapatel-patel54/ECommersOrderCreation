# ECommersOrderCreation
Microservices,Spring Boot,Spring Cloud, Eureka, Ribbon, Feign Client, Zuul, Sleuth,  Spring Security, Caching, JPA Repositories


order-service
host:localhost
port 8100
get http://localhost:8100/createorder?id=1001&catid=1004


zuul- http://localhost:8765/order-service/createorder?id=1001&catid=1004



product-service
host localhost
post - http://localhost:8110/products
post - http://localhost:8110/category


user-service
host - localhost
port 8105
get http://localhost:8105/users/id/1001


Actuator
http://localhost:<port>/actuator

Eureka
http://localhost:<port>/eureka


