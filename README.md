# kafka-producer-consumer kafca used for realtime milions of streaming and monitoring , event acces, message pass , log file read , monitoring and analysis operations.#first time Linkedin use this 2011

see you tube vidio [this YouTube tutorial](https://www.youtube.com/watch?v=EiDLKECLcZw).

A kafka producer/consumer proof of concept using node.

![Screen Shot 2021-04-20 at 09 56 47](https://user-images.githubusercontent.com/17026751/115368228-cbcd0000-a1be-11eb-9d17-6ada1ad5ff98.png)

## Prerequisites

* `node`
* `docker`

## Running locally

* `npm install` - installs npm dependencies.
node-rdkafka - https://www.npmjs.com/package/node-rdkafka 
avsc (for serialization & de-serialization) -https://www.npmjs.com/package/avsc

* `./scripts/start-kafka.sh` - starts kafka inside docker container.
* `./scripts/create-topic.sh` - creates kafka topic.
* cmd run to comsumer and produser
* `npm run start:producer` - starts producer.
* `npm run start:consumer` - starts consumer.
