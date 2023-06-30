## LOAD BALANCER IN NODEJS

### Testing the creation of load balancing servers in Node.js using  <b>Cluster Module </b>

- A single NodeJS server is not flexible for handling a very large amount of traffic.  But in order to share traffic to your all application server, a load balancer is required.

- A load balancer acts as the traffic cop sitting in front of your application servers and routing client requests across all servers capable of fulfilling those requests in a manner that maximizes speed and capacity utilization and ensures that no one server is overworked, which could degrade performance.

NodeJS has a built-in module called <b>Cluster Module </b> to take the advantage of a multi-core system. Using this module you can launch NodeJS instances to each core of your system

-To see the performance, we have used <b> autocannon tools</b> to test our server. The Autocannon package has already been installed globally on the machine.
