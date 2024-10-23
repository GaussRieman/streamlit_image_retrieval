## install standalone 
### Download the configuration file
```
$ wget https://github.com/milvus-io/milvus/releases/download/v2.4.13-hotfix/milvus-standalone-docker-compose.yml -O docker-compose.yml
```
### Start Milvus
```
$ sudo docker-compose up -d

Creating milvus-etcd  ... done
Creating milvus-minio ... done
Creating milvus-standalone ... done
```