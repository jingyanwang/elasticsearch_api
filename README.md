# elasticsearch_api

## building the docker

```cmd
docker build `
-t jingyanwang1/ebedding_vector_search:1.0.2 `
.
```

## runing the docker

```cmd
docker run -it `
-p 0.0.0.0:9466:9466 `
-p 0.0.0.0:3671:3671 `
-p 0.0.0.0:5145:5145 `
jingyanwang1/ebedding_vector_search:1.0.2
```
