# wanna-eat-BE
<img src="https://github.com/user-attachments/assets/5c731bcd-fc7f-4a87-a489-2f3c99b9712a" width="600">


## About
This project is implementation of spring boot webflux.

## Prerequisites
* JDK 17
* SpringBoot 2.7.5 with WebFlux(Reactive)
* Gradle 7.5.1
* Lombok
* R2DBC with PostgreSQL
  
## Why Spring Webflux?

* Spring MVC uses a thread-per-request model, which can block threads during heavy I/O
* WebFlux, built on an event-loop (Reactor Netty), handles more requests with fewer threads—ideal for high traffic or I/O-heavy APIs.

## Why R2DBC?

* JDBC blocks threads by holding DB connections until SQL execution completes.
* R2DBC enables non-blocking, asynchronous communication with the database, allowing high concurrency even under heavy load.

