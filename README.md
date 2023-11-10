# docker-mongo-cluster

This repository is a template to implement a cluster of 3 mongodb nodes using mongo:4.2.1 image.

How to launch the service
```docker-compose up -d```

How to stop the service
```docker-compose down```

### Infos

You will have 5 containers :
- mongo1: main server
- mongo2: replicate server
- mongo3: replicate server 
- mongo-rs0-setup: this one will configure the replica set 
- mongo-check: this one will check the replica set 