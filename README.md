# DB Stack
A set of popular database systems organized into a single `docker compose` stack for development and testing.

## Requirements

* Docker Desktop or Docker with docker compose v2
* Bash

## Installation
 
* Clone or download this repository on your local computer
* configure .env as needed 
* Run the `docker compose up` or `docker compose up -d`.

```shell
git clone https://github.com/sinobash/db-stack.git
cd db-stack
cp .env.example .env
// modify .env.example as needed
docker compose up -d
```