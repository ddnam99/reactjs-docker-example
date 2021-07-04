# reactjs-docker-example

## Requirements:

1. docker
2. docker-compose
3. npm or yarn (optional)
## Development

1. **Start project:** `yarn docker:dev` or `docker-compose -f docker/docker-compose.dev.yml up`
2. **Run command in container:**

- Step 1: run `yarn docker-bash:dev` or `docker exec -it reactjs-docker-example sh`
- Step 2: run your command

- _example:_ install ant design to project. First run `yarn docker-bash:dev` to access bash command, later run `yarn add antd` to install antd package to project

## Production

Run `yarn docker-build:prod` or `docker-compose -f docker/docker-compose.prod.yml build` to build docker image production
