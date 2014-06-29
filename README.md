## Java Dockerfile


This repository contains **Dockerfile** of [Java 8](https://jdk8.java.net/) for [Docker](https://www.docker.io/)'s [trusted build](https://index.docker.io/u/ayucat/java/) published to the public [Docker Registry](https://index.docker.io/).


### Dependencies

* [dockerfile/ubuntu](http://dockerfile.github.io/#/ubuntu)


### Installation

1. Install [Docker](https://www.docker.io/).

2. Download [trusted build](https://index.docker.io/u/ayucat/java/) from public [Docker Registry](https://index.docker.io/): `docker pull ayucat/java`

   (alternatively, you can build an image from Dockerfile: `docker build -t="ayucat/java" github.com/ayucat/java`)


### Usage

    docker run -it --rm ayucat/java

#### Run `java`

    docker run -it --rm ayucat/java java

#### Run `javac`

    docker run -it --rm ayucat/java javac
