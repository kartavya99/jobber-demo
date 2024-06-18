## Review Microservice

- The review microservice is responsible for creating and managing sellers and buyers reviews.
- In this service, events are only `published` to other microservices.
- Server side errors from the review microservice is sent to `elasticsearch` and can be viewed on `kibana`.
- Review service uses these tools as the main tools
  - `Your shared library`
  - `NodeJS`
  - `Express`
  - `Typescript`
  - `Rabbitmq`
  - `Elasticsearch`
  - `Postgresql database`
  - `NodeJS pg`
  - `Json web token`
  - `SocketIO`
- There are other packages that are used.
- You can update the version of `NodeJS` used inside the `Dockerfile` and `Dockerfile.dev`.

## JENKINS

<img src = "./jenkins.png" width ="400">

## LOCAL SERVER

<img src = "./local.png" width ="400">
