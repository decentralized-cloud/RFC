# Features

## Single/Multiple Clusters

* create and configure the cluster
* generate package to install on edge node and join the cluster
* support many edge clusters

## Cluster Management

* add/Remove/Manage edge cluster
* add/Remove/Manage nodes in existing edge clusters
* add new node dynamically, no fixed cluster size
* hybrid cloud support
* centralized management of all edge cluster

## Application Deployment

* deploying application to edge nodes
* deploying application based on node's physical location
* deploying application based on node's capabilities
* ensure any new node added to the cluster with same conditions gets all previous applications and configuration deployed
* deploy applications on all edge nodes with specific set of conditions

## High Availability

* HA on the master cluster
* HA on edge cluster

## Monitoring/Alerting

* centralized visibility and troubleshooting
* monitoring clusters
* monitoring deployed application status
* nodes to push their metrics to the data centre
* monitoring edge nodes
* node health check
* monitor application memory usage
* monitor application CPU usage
* monitor application storage usage
* alert on node status
* alert deployed application status
* alert when node crashes
* alert when node goes down
* alert application memory usage
* alert application storage usage
* alert node memory usage
* alert node CPU usage
* alert application CPU usage

## Working Off-line

* enable edge node to work off-line after the work is scheduled

## Cluster Federation

* setting up federation between different edge clusters
* setting up federation between edge cluster and existing customer clusters

## Query/Search Dashboard

* query/search nodes based on nodes' physical location
* query/search nodes based on nodes' deployed applications
* query/search nodes based on nodes' capabilities
* query/search nodes based on nodes' real-time metrics

## Client Load Balancing

* load balancing on services deployed on edge nodes

## Bootstrap Cluster and Nodes

* associate edge nodes with unique ID
* associate edge nodes with friendly name
* associate edge nodes with description

## Edge Storage

* provide reliable storage on the edge
* provide mechanism for edge nodes to transfer processed data to the data centre

## Edge Node Maintenance

* rebooting edge node
* upgrading edge node
* apply software patches to edge node


## Security and Access Control

* secrets and security
* centralized configuration of policies
* centralized RBAC and identity management

## Load-Balancing and Networking

* secure and trusted connection between edge nodes in the same cluster
* edge mesh
* service mesh

## Logging and Tracing

* logging and tracing dashboard
* logging and tracing on the master cluster

## configuration

* configuration provider for remote deployed applications
* synchronize configuration across edge nodes for different deployed applications

## Can join different type of the hardware to the cluster

* can join Raspberry Pi

## Demo

* demo script to create multiple clusters
* demo storage capabilities on the edge node
* think of a demo that can show platform capabilities with IoT devices
* demo script to deploy demo application
* demo script to setup the master cluster

## Miscellaneous

* watchdog service to keep edge node running at all time
* nodes to fetch latest settings from local node if content already exists locally to them on a different edge node
* nodes to fetch the container image from local nodes rather than each one goes to the cloud to fetch its own one
