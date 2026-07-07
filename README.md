# DB Stack

A set of popular database systems organized into a single `docker compose` stack for development and testing.

## Requirements

* Docker Desktop or Docker with docker compose v2
* Bash

## Prerequisite

```bash
# Create the Shared Network
docker network create my-shared-network
```

## Installation
 
* Clone or download this repository on your local computer
* configure `.env` as needed 
* Run the `docker compose up` or `docker compose up -d`.

```bash
git clone https://github.com/sinobash/db-stack.git
cd db-stack
cp .env.example .env
# Modify .env.example as needed
docker compose up -d
```