# derecho

DBSWA assignment: TODO API with UI. Nginx upstream mapping of todo-api to /api and todo-ui to /. Application start at port 7800

## CLI Commands

```bash
# build todo-api
$ cd todo-api && docker build -t todo-api .

# build todo-ui
$ cd todo-ui && docker build -t todo-ui .

# start container at the root directory; application running on port 7800
$ cd derecho && docker compose up --build

# stop running container
$ docker compose down

``````