# brs3

# e-commerce

my microservice architecture base on cloud. i use cloud because of scaling up/single point of failure etc. my application.

i will use http loadbalancer in fornt my application cluser for handle traffic/api/security. 

All client request/authentication/payment/notification wil server through api from cluser.

i use cluser for our container to overcome single point of failure of my pod/containers.

i use kubernetes clusert to bulid e-commerce applicaton,in this cluster i will ensure single point of failure, scalability, fault tolerance,
auto recovery using replicaset, service, ingress controller.

database use clustering for backup & if goes down other will take owership & serve service.

persistance volume will use for storage for pod. 

for CI/CD automation jenkins 
for kubernetes  user access we use RBAC.

service shoud be hosted in multiple cloud region, if one region down other region will serve.
 
i wiil expose service with ngress controller/loadblancer. my cluser have multimaster, if one down master down other will serve.

i wiil use grafana/prometheus for alert & notification. 

System requirements: Kubernetes, cloud sql, cloud storage, cloud memorystore, Http Loadbalancer, ansible, jenkins. 
