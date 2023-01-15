# docker-setup

This repository holds some useful and frequently assessed Docker template yaml files for quick reference. 

## Working Technologies Stack

<p align="left"> 
  <a href="https://learn.microsoft.com/en-us/azure/storage/common/storage-use-azurite?tabs=visual-studio" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/f/fa/Microsoft_Azure.svg" alt="azure" width="40" height="40"/> </a> 
  <a href="https://kafka.apache.org/" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Apache_kafka.svg" alt="kafka" width="40" height="40"/> </a> 
  <a href="https://zookeeper.apache.org/" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/7/77/Apache_ZooKeeper_logo.svg" alt="zookeeper" width="40" height="40"/> </a> 
  <a href="https://www.docker.com/" target="_blank"> <img src="https://www.docker.com/wp-content/uploads/2022/03/vertical-logo-monochromatic.png" alt="docker" width="40" height="40"/> </a> 
  <a href="https://www.mongodb.com/atlas/database" target="_blank"> <img src="https://cdn.worldvectorlogo.com/logos/mongodb-icon-1.svg" alt="mongo" width="40" height="40"/> </a>
  <a href="https://redis.io/" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/6/64/Logo-redis.svg" alt="redis" width="40" height="40"/> </a> 
  <a href="https://joeferner.github.io/redis-commander/" target="_blank"> <img src="https://api.mogenius.com/file/id/b4b8746b-8ec2-4c64-b80c-00d41a0c985e" alt="redis-commander" width="40" height="40"/> </a>
</p>

## Dependencies
* [Azurite](https://hub.docker.com/_/microsoft-azure-storage-azurite) - Azurite emulator for local Azure Storage development
* [Apache Kafka](https://kafka.apache.org/) - Streaming platform for high-performance data pipelines, streaming analytics, data integration 
* [Apache Zookeeper](https://zookeeper.apache.org/) - Service for maintaining configuration information and providing distributed synchronization
* [Docker](https://www.docker.com/) - Platform as a service for OS-level virtualization to deliver software in packages
* [MongoDB](https://www.mongodb.com/) - NoSQL database program
* [Redis](https://redis.io/) - In-memory data store used for database, cache, streaming engine, and message broker
* [Redis-Commander](https://joeferner.github.io/redis-commander/)  - A node.js web application used to view, edit, and manage a Redis Database

## Quick Reference Commands

*Start Docker*
```console
docker-compose -f <DOCKER_CONFIG_FILENAME> up -d
```

*Stop Docker*
```console
docker-compose -f <DOCKER_CONFIG_FILENAME> down
```

## Disclaimer

Copyright disclaimer under section 107 of the Copyright Act 1976, 
allowance is made for “fair use” for purposes such as criticism, 
comment, news reporting, teaching, scholarship, education and research.

Fair use is a use permitted by copyright statute that might otherwise 
be infringing.
