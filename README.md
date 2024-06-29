# rideBookingApp
1. Location service: It connects to a redis server and update live driver location and also fetches nearby driver to a coordinate. Also, instead of redis clients can use mongodb for storing live locations and fetching nearby drivers.

2. Entity Service: This stores all the models used across microservices.

3. Booking service: Manages everything regarding ride booking.

4. Socket Service: Uses Stomp based sockets to communicate to clients and microservices.

5. ReviewService: Manage review crud.

6. Eureka service discovery.

7. Auth service: JWT token based auth.

Additional features
1. Kafka for async service communication.
2. Retrofit for async api calls.
3. Proper dto and repository structures.
4. Spring boot, spring data jpa, spring socket, spring redis, spring kafka, Scheduler etc used.
5. DB migrations using flyway.
