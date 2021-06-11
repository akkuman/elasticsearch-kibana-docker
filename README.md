# ElasticSearch-Kibana-DockerCompose

## How to use

```
git clone https://github.com/akkuman/elasticsearch-kibana-docker.git
cd elasticsearch-kibana-docker

# Reference: https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html#_configuration_files_must_be_readable_by_the_elasticsearch_user
mkdir data
chmod g+rwx data
chgrp 0 data

docker-compose up -d
```