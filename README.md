## Node.js w/ Bower & Grunt Dockerfile


This repository contains **Dockerfile** of [Node.js](http://nodejs.org/) w/ [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/) for [Docker](https://www.docker.io/)'s [trusted build](https://index.docker.io/u/dockerfile/nodejs-bower-grunt/) published to the public [Docker Registry](https://index.docker.io/).


### Dependencies

* [dockerfile/nodejs](http://dockerfile.github.io/#/nodejs)


### Installation

1. Install [Docker](https://www.docker.io/).

2. Download [trusted build](https://index.docker.io/u/dockerfile/nodejs-bower-grunt/) from public [Docker Registry](https://index.docker.io/): `docker pull dockerfile/nodejs-bower-grunt`

   (alternatively, you can build an image from Dockerfile: `docker build -t="dockerfile/nodejs-bower-grunt" github.com/dockerfile/nodejs-bower-grunt`)


### Usage

    docker run -it --rm dockerfile/nodejs-bower-grunt

#### Run `node`

    docker run -it --rm dockerfile/nodejs-bower-grunt node

#### Run `npm`

    docker run -it --rm dockerfile/nodejs-bower-grunt npm

#### Run `bower`

    docker run -it --rm dockerfile/nodejs-bower-grunt bower

#### Run `grunt`

    docker run -it --rm dockerfile/nodejs-bower-grunt grunt