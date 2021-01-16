# GhostNetwork - Reactions

Reactions is a part of GhostNetwork education project for working with users reactions to publications, comments, photos etc. For example save likes for user photo

## Installation

copy provided docker-compose.yml and customize for your needs

compile images from the sources - `docker-compose build && docker-compose up -d`

### Parameters

| Environment    | Description                  |
|----------------|------------------------------|
| MONGO_ADDRESS  | Address of MongoDb instance  |

## Development

To run dependent environment use

```bash
docker-compose -f dev-compose.yml pull
docker-compose -f dev-compose.yml up --force-recreate
```

