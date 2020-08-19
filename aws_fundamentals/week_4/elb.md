# Amazon EC2 Elastic Load Balancing Notes

Elastic Load Balancing (ELB) automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, and IP addresses. It can handle the varying load of your application traffic in a single Availability Zone or across multiple Availability Zones.

ELB offers three types of load balancers that all feature the high availability, automatic scaling, and robust security that are necessary to make your applications fault-tolerant.

An Application Load Balancer operates at the request level (Layer 7), routing traffic to targets--such as EC2 instances, microservices and containers--within Amazon VPC, based on the content of the request. It's ideal for the advanced load balancing of Hypertext Transfer Protocol (HTTP) and Secure HTTP (HTTPS) traffic.

A Network Load Balancer operates at the connection level (Layer 4), routing connections to targets--such as Amazon EC2 instances, microservices, and containers--within Amazon VPC, based on IP protocol data. It's ideal for load-balancing Transmission Control Protocol (TCP) traffic.

The Classic Load Balancer provides basic load balancing across multiple Amazon EC2 instances, and it operates at both the request level and the connection level.