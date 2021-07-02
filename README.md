# Apache Tika

The Apache Tika™ toolkit detects and extracts metadata and text from over a thousand different file types (such as PPT, XLS, and PDF). All of these file types can be parsed through a single interface, making Tika useful for search engine indexing, content analysis, translation, and much more. 

https://tika.apache.org/

## Requirements

You will need a fairly recent version of [Docker](https://docs.docker.com/installation/).

We will use the following Docker images:

* Apache Tika: [apache/tika](https://hub.docker.com/r/apache/tika)

## Configuration

Copy ``.env.example`` file to ``.env``

Optional. Edit the `.env` file and update the listen port. Default is `9998`.

## Setup

Starting Apache Tika related containers/services:

```
docker-compose up -d --build
```

Exposed ports:

* LISTEN_PORT - 9998

## Links

* https://tika.apache.org/
* https://docs.docker.com/installation/
* https://hub.docker.com/r/apache/tika
