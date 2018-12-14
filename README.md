# dockerMongo

Install Mongo On Docker

sudo docker run --name some-mongo -d mongo --smallfiles


sudo docker run -it --link some-mongo:mongo --rm mongo mongo --host mongo test
