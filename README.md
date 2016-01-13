# Web Engineering 2015-2016 / Microservices
## The two microservices are running and registered

[Log of accounts(port 2222)](./logs/acc.log?raw=true)

[Log of web](./logs/web.log?raw=true)


## The service registration service has the two microservices registered

[Log of registration](./logs/reg.log?raw=true)

![](./screenshot/2-2-microservicios.png?raw=true)

## A second account microservice is running in the port 4444 and it is registered

[Log of accounts(port 4444)](./logs/acc2.log?raw=true)

## A brief report describing what happens when you kill the microservice with port 2222. Can the web service provide information about the accounts? Why?

When we kill the microservice at port 2222, the register detect, unregister the service and replace with the new accounts microservice.
