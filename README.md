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