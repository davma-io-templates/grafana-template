# Deploy Grafana Loki with Docker Compose
You can install Grafana Loki and Promtail with Docker or Docker Compose if you are evaluating, testing, or developing.

The configuration acquired with these installation instructions run Loki as a single binary.

## Prerequisites 

[Docker](https://docs.docker.com/install)

[Docker Compose](https://docs.docker.com/compose/install)


## 1.Deploy

Run the following commands in your command line:

````
git clone https://github.com/davma-io-templates/grafana-template.git
````
````
cd grafana-template/docker-compose
````
````
docker-compose -f docker-compose.yaml up
````