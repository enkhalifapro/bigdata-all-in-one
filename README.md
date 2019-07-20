# big data All-In-One

## All images and configurations are in docker-compose.yml

 Run ```$ docker-compose up -d``` to pull and run the images

you can access the services throug the exposed ports as the following :

| Service Name  | Port Number |
| ------------- | ------------- |
| Hadoop name node  | 50070  |
| Hadoop data node  | 50075  |
| Hive server | 10000 |
| Postgres | 5433 |
| Hue | 8888 |
| Jupyter | 8889 |
| PySpark | 4040 |
| Flink job manager | 8081 |
| Flink task manager | 6122 |

- To list the containers run ```$ docker ps```

- To run commands inside container run ```$ docker exec -it <containerName>```
