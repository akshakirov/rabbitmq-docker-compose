# Rabbitmq 4 dockerized

## single
Here is an example of single server RabbitMQ

Uncomment volumes ```docker-compose.yml``` if you need to use a definitions, for example you need to create VirtualHosts  and users

Example of definitios is also available in ```conf``` folder.

## cluster
Here is example of cluster rabbit-n1.domain.com  

You should change ```rabbit-n1``` to ```n2``` on second node, ```n3``` on third node 

if you need to have more nodes, add them to rabbitmq.conf

You can put all nodes in your application or use haproxy which runs on separate VM for example with name rabbit.domain.com


