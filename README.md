# go-hello-world
Example web app which can be deployed either via [buildpack](https://docs.cloudfoundry.org/buildpacks/) or
as a [Docker](https://docs.cloudfoundry.org/devguide/deploy-apps/push-docker.html) container

# endpoints

| Endpoint | Description |
|----------|-------------|
| `GET /`      | Prints `"Hello! You've required: {path}"` |
| `GET /dump'  | Dumps the HTTP request to the screen |
| `GET /api/test/:host/:port | Tests connectivity to host:port |


# license
License is MIT
 
