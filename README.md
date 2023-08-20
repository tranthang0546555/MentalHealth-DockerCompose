# Mental health - [docker-compose]

## Tree

- mental-health-backend [https://github.com/tranthang0546555/mental-health-backend]

  - Dockerfile
  - package.json
  - package.lock
  - ...

- mental-health-frontend [https://github.com/tranthang0546555/mental-health-frontend]
  - Dockerfile
  - package.json
  - package.lock
  - ...
- compose.yaml
- README.md

## Run

Install docker and docker-compose

Options: <-d>, <-f> is optional

```bash
# run container
  docker compose up <-d>

# shell
  docker compose exec [container-id] sh

# logs
  docker compose logs [container-id] <-f>

# stop and remove container
  docker compose down <-d>
```
