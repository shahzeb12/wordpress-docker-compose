# WordPress Docker Compose

## Overview

A WordPress application deployed using Docker Compose with
separate WordPress and MySQL containers.

## Architecture

WordPress
    ↓
Docker Network
    ↓
MySQL

## Docker Concepts

- Docker Compose
- Multi-container applications
- Container networking
- Service discovery
- Persistent volumes
- Environment variables
- Container dependencies

## How to Run

docker compose up -d

Open:

http://localhost:8080

## How to Stop

docker compose down

## Persistent Data

WordPress files:
wordpress_data

MySQL data:
db_data