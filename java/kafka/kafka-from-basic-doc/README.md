
# Instructions
This is the recomendation get-started from the Confluent documentation
Create a collection of containers that perform all types of services that can be started with kafka

The command line below executes the do=wload of the docker-compose.yaml  file.


`
curl --silent --output docker-compose.yml \
  https://raw.githubusercontent.com/confluentinc/cp-all-in-one/6.1.1-post/cp-all-in-one/docker-compose.yml

docker-compose up -d
`
