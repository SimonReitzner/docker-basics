# MongoDB

Documentation of the environment variables

| Environment Variable | Required | Default |
|----------------------|:--------:|:-------:|
| COMPOSE_PROJECT_NAME | &cross; | _foldername_ |
| CONTAINER_NAME | &cross; | `mongodb` |
| PORT | &cross; | `27017` |
| MONGO_INITDB_ROOT_USERNAME | &check; | - |
| MONGO_INITDB_ROOT_PASSWORD | &check; | - |
| MONGO_CONFIG_FILE_PATH | &cross; | `./mongod.conf` |