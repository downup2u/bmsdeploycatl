# bmsdeploycatl

W01	ecs-d493 Nginx 反向代理 192.168.1.11 121.204.128.149 <---nginx
W02	ecs-40d6 Nginx 反向代理 Slave 192.168.1.12 27.150.186.192 <--test
W03	ecs-f601 NodeJS（Web+App）Master 192.168.1.13 121.204.130.141 <--node
W04	ecs-dc19 NodeJS（Web+App）Slave 192.168.1.14 121.204.131.36 <--kafkadb

W05	ecs-44e1 Kafka/Zookeeper Cluster 192.168.2.11 121.204.132.236	 
W06	ecs-e871 Kafka/Zookeeper Cluster 192.168.2.12 121.204.132.246
W07	ecs-b228 Kafka/Zookeeper Cluster 192.168.2.13 121.204.130.198

D04	ecs-492e MongoDB  Master 192.168.2.17 121.204.134.33
D05	ecs-8906 MongoDB  Slave 192.168.2.18 121.204.133.201	 
D06	ecs-5bed MongoDB  Slave 192.168.2.19 121.204.128.116
