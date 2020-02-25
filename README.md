# Project XYZ
## About this project
Project XYZ is a personal experimental project built to allow myself to learn different languages that are new to me. The product itself is a project management and CRM tool. We will be using docker containers and microservices architecture, where each service is built using a different tech. The frontend will be built using vue.js. For the sake of simplicity, we will be using 1 container with mysql for all services. This repository specifically will be used as a wrapper around docker-compose and some bash script to pull and setup all components.

## The Containers
So far, the languages chosen for each container/service:

- database: MySQL 8.0
- frontend: Vue.js 2.6.11
- user: Python 3.7 / Django 3.0
- message: RoR 6.0.2.1
- external: Golang 1.13 / Gin
- invoice: Rust 1.41.0 / Rocket
- project: TypeScript 3.8.2 / Nest.js

## Setup Guide and Usage
To setup the project, simply run
    ./xyz cloneall
    ./xyz dockerup
    ./xyz dbcreate
