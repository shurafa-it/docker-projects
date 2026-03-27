# Docker Compose Applications

A collection of Docker Compose configurations to deploy popular web applications with their databases.

## Applications

| App | Port | Database |
|---|---|---|
| WordPress | 9091 | MySQL |
| PrestaShop | 9090 | MySQL |
| Joomla | 8080 | MySQL |
| Drupal | 8080 | PostgreSQL |

## Features
- Persistent volumes for data and files
- Custom Docker networks for service isolation
- Environment variables for secure configuration
- `depends_on` to manage service startup order

## How to Run

Each app has its own folder. Navigate to the folder and run:
docker-compose up -d

To stop:
docker-compose down
