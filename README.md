# ELK-docker

利用Docker compose部署ELK

## TODO

- [] 启动
- [] 用户
- [] 集群

## ELK: ElasticSearch + LogStash + Kibana

### ElasticSearch: 分布式搜索引擎，搜索+分析+数据存储

api端口: `9200`

获取集群健康度： `https://ip:9200/_health_report`

### LogStash: 日志搜集分析过滤

配置项:

1. pipeline
2. filebeat

### Kibana: Web界面

web端口: `5601`

## 出现的问题

1. es _health_report为red, 原因：磁盘空间不够
