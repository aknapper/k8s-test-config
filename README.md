# k8s-test-config

Simple k8s config for a setup of a web application and database using MongoDB and Mongo Express.

`mongo.yaml` defines the MongoDB deployment and asssociated service.
`mongo-express.yaml` defines the Mongo Express deployment and associated service.

## High-Level Architecture
MongoDB(pod) <-> MongoDB(internal service) <-> Mongo Express(pod) <-> Mongo Express(external service) <- Exernal requests
