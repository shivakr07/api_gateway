other microservices
1. FlightandSearch : [https://github.com/shivakr07/FlightsandSearchService]
2. BookingService : [https://github.com/shivakr07/AirTicketBookingService]
3. ReminderService : [https://github.com/shivakr07/ReminderService]
4. AuthService : [https://github.com/shivakr07/Auth_Service]
<span style = "color : Blue"> An API Gateway acts as a mediator between client applications and backend services in microservices architecture. It is a software layer that functions as a single endpoint for various APIs performing tasks such as request composition, routing, and protocol translation. The API gateway controls requests and responses by managing the traffic of APIs while enforcing security policies.</span>

FRONTEND  - MIDDLE-END  -  BACKEND

- We need an intermediate layer between the client side and the microservices
- Using this middle end, when client sends request we will able to make decision that which microservice should actually respond to this request
- We can do message validation, response transformation, rate limiting
- We try to preapare an API Gateway that acts as this middle end

/*
- reverse proxy
- leave the microservices for which it is intended to do  or provides it's services
"
*/
