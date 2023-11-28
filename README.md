# WP Docker

## Introduction

This is a lightweight, minimal setup that has Composer and WP_CLI support.

### Prerequisite
You only need Docker and docker compose plugin or older version of docker-compose utility.

### Start

```shell
docker compose up
```

### Run Composer & WP_CLI
```shell
docker compose run --rm composer composer <command>
```

In similar manner, run WP_CLI container:
```shell
docker compose run --rm wp_cli wp <command>
```

visit local site on http://localhost:8888
