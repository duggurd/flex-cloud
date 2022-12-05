# Flex cloud
The private cloud. INdependence and power wherever the wind takes you.

Born from the wish of creating a highly portable and powerful plattform that could fulfill my needs wherever I go. Addidionally exploring the possible uses for older and underutilized/unused hardware in my daily workflow and developer needs.

Cloud shouldn't belong to the few...


In progress:
- Exploring existing software
- Exploring possibility to build own cloud fabric software


## The ideal solution
Container-based cloud fabric for extreme flexibility. Remove a node when pc is needed for something else, or add nodes continuosly.

![flex_cloud](flex_cloud.png)

Deploying VMs or ideally containers on the cloud fabric.

### Requirements
- Storage
- Azure functions/AWS lambda like service
- Webserver hosting
- DB in the cloud
- V-Net support
- Flexibility (adding removing nodes/hosts)
- Lightweight (old smartphones)
- Apache Spark

## Complete solutions
Out of the box complete solutions. On-prem cloud software. Fully functioning out of the box.

### Apache CloudStack
[Website](https://cloudstack.apache.org/) | [GitHub](https://github.com/apache/cloudstack)

"Apache CloudStack is an open source Infrastructure-as-a-Service platform that manages and orchestrates pools of storage, network, and computer resources to build a public or private IaaS compute cloud."

Minimal setup with one machine running *CloudStack Management Server* and another machine as the *cloud infrastructure*.

Easy management through web-interface.

Hosts as smallest level of grain, running guest VMs.


[Cloudstack CaaS](https://www.shapeblue.com/cloudstack-container-service/)

## SealOS
[SealOS](https://github.com/labring/sealos)

OS based on kubernetes. "..only be cloud OS drivers, cloud OS kernel and distributed applications." 

OCI compatible distributed applications (PostgreSQL, MySQL, Redis, etc.).

use Dockerfiles to build distributed applications images(!).

## Partial solutions
Building the cloud from individual services. Instead of building services on top of a singular cloud fabric, hosting individual cluster/distributed services across machines.



### Different software fulfilling individual needs
Using distributed software/clustering software for all the different needs. Meaning no same level abstarction across all machines.

### OHPC
[GitHub](https://github.com/openhpc/ohpc)

### Kubernetes

## DIY
If all else fails I am committed to trying to build a semi functional cloud fabric service from scratch. Most likely in Rust. 
