# deploy configs for courseGPT project

## Quick guide

### Create env file
simply copy the `.env-example` to a new file named `.env`.
Then you can set your configs in this new `.env` file.

### Nginx configuration
You can define your routes in `.nginx/donf.d/default.conf`.

### Docker compose configuration:
You can customize your configs in `docker-compose.yml`.

### Run
```shell
    docker compose up --build
```
