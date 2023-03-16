# DockSearch

### About this project

To use Elasticsearch, customers will need to install a cluster on a physical server that meets certain specifications. We recommend a minimum of 32GB of RAM for optimal performance. 

The preferred approach is to install **Elasticsearch using Docker containers**. The basic architecture consists of one **master node with 1GB of RAM**, **two data nodes with 15GB of RAM each**, and one **monitoring node with 1GB of RAM.** 

This setup provides a reliable and scalable solution for managing Elasticsearch data and monitoring its performance.

### Project link

https://toanmx.notion.site/f5073b6d9382418783d6905e4d3fb3e5?v=def3cce483c2458f8dc9116be66110a3


### Todods

1. Setup Elasticsearch
    - Set up 4 nodes: one master-eligible node and two data nodes, one monitoring node
    - Specify the node specifications, including CPU, RAM, and storage capacity
    - Specify the operating system and Elasticsearch versions
    - Specify the backup frequency (e.g. daily) and retention policy
    - Consider disaster recovery mechanisms and testing procedures
    - Document the setup, configuration, testing, and monitoring procedures
2. Elasticsearch Cluster Monitoring
    - Setup Kibana and Metricbeat for the monitoring dashboard
    - Set up alerts for high CPU usage and other important metrics
