# Overview

CushionCouch is part 2 of 2 for the CushionDB backend. It is setup as a Docker image and is deployed along with the [CushionServer](https://github.com/CushionDB/CushionServer) Docker image using Docker Compose. These two backend components are desgined to work with [CushionClient](https://github.com/CushionDB/CushionClient).

CushionCouch uses CouchDB as its base image. It applies a custom `.ini` configuration file to create the pre-configured CouchDB instance required to work with CushionDB.

# Getting Started

## Install

The CushionCouch container is built and run on your server automatically once you have cloned [CushionDocker](https://github.com/CushionDB/CushionDocker) and go through the setup steps.

## Setup

From inside the [CushionDocker](https://github.com/CushionDB/CushionDocker) directory, you will run `cushion-backend-init`, which will prompt you to input information that will be used for various configurations.

<p align="center"><img src="https://cushiondb.github.io/img/cushion-backend-init.gif"></p>

# The Team

[Avshar Kirksall](https://avshrk.github.io/
) *Software Engineer* Brooklyn, NY

[Jaron Truman](https://jtruman88.github.io/
) *Software Engineer* Las Vegas, NV

[Daniel Rote](https://drote.github.io/
) *Software Engineer* Seattle, WA
