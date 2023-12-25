https://developer.confluent.io/courses/kafka-connect/self-managed-connect-hands-on/?utm_medium=sem&utm_source=google&utm_campaign=ch.sem_br.nonbrand_tp.prs_tgt.dsa_mt.dsa_rgn.india_lng.eng_dv.all_con.confluent-developer&utm_term=&creative=&device=c&placement=&gad_source=1&gclid=CjwKCAiAvoqsBhB9EiwA9XTWGWVIWrq_6ETL7krswSz_wG03b3O5-u2vxaiebVBzI6m7sNFNT12wBhoCLroQAvD_BwE

https://docs.confluent.io/platform/current/installation/docker/installation.html


/Users/venkataravikumarvemulakonda/Documents/techgaint_workspace/ConfluentKafka/confluent-kafka_docker_infra	[ Confluent Kafka local cluster with docker img ]

/Users/venkataravikumarvemulakonda/Documents/techgaint_workspace/ConfluentKafka/citysales-analytics		[ Spring batch to publish messages to topic ]

/Users/venkataravikumarvemulakonda/Documents/techgaint_workspace/ConfluentKafka/citysales-analytics-streams				[ Stream application ]

/Users/venkataravikumarvemulakonda/Documents/techgaint_workspace/confluent-infra/kafka-apps

/Users/venkataravikumarvemulakonda/Documents/techgaint_workspace/ConfluentKafka/citysales-analytics-kafka-consumer		[ Working, Reads messages from index-by-count ]

/Users/venkataravikumarvemulakonda/Documents/techgaint_workspace/AWS/terraform-projects/tf-aws-rds-postgres

https://hub.docker.com/u/confluentinc/


Producer, Stream Process & consumer apps also working...
Control Center is working, look at @ http://localhost:9021/clusters/
schema-registry:        http://localhost:8081/      #Up and working
connect:                http://localhost:8083/      #Up and working      
ksqldb-server:          http://localhost:8088/      #Up and working
rest-proxy:             http://localhost:8082/      #Up and working

Final output @ consumer ....
2023-12-24 22:17:21.553  INFO 17363 --- [nio-9071-exec-1] c.t.c.analytics.KafkaConsumerController  : ﻿NYA = 2
2023-12-24 22:17:21.553  INFO 17363 --- [nio-9071-exec-1] c.t.c.analytics.KafkaConsumerController  : KA = 2
2023-12-24 22:17:21.553  INFO 17363 --- [nio-9071-exec-1] c.t.c.analytics.KafkaConsumerController  : NYA = 27886
2023-12-24 22:17:21.553  INFO 17363 --- [nio-9071-exec-1] c.t.c.analytics.KafkaConsumerController  : IXIC = 25380
2023-12-24 22:17:21.554  INFO 17363 --- [nio-9071-exec-1] c.t.c.analytics.KafkaConsumerController  : HSI = 17494
2023-12-24 22:17:21.554  INFO 17363 --- [nio-9071-exec-1] c.t.c.analytics.KafkaConsumerController  : 000001.SS = 11926
2023-12-24 22:17:21.554  INFO 17363 --- [nio-9071-exec-1] c.t.c.analytics.KafkaConsumerController  : GSPTSE = 21552
2023-12-24 22:17:21.554  INFO 17363 --- [nio-9071-exec-1] c.t.c.analytics.KafkaConsumerController  : 399001.SZ = 11856
2023-12-24 22:17:21.554  INFO 17363 --- [nio-9071-exec-1] c.t.c.analytics.KafkaConsumerController  : NSEI = 6762
2023-12-24 22:17:21.554  INFO 17363 --- [nio-9071-exec-1] c.t.c.analytics.KafkaConsumerController  : GDAXI = 17212
2023-12-24 22:17:21.554  INFO 17363 --- [nio-9071-exec-1] c.t.c.analytics.KafkaConsumerController  : KS11 = 12362
2023-12-24 22:17:21.554  INFO 17363 --- [nio-9071-exec-1] c.t.c.analytics.KafkaConsumerController  : SSMI = 15660
2023-12-24 22:17:21.554  INFO 17363 --- [nio-9071-exec-1] c.t.c.analytics.KafkaConsumerController  : TWII = 12020
2023-12-24 22:17:21.555  INFO 17363 --- [nio-9071-exec-1] c.t.c.analytics.KafkaConsumerController  : J203.JO = 4774
2023-12-24 22:17:21.555  INFO 17363 --- [nio-9071-exec-1] c.t.c.analytics.KafkaConsumerController  : N225 = 29000
2023-12-24 22:17:21.555  INFO 17363 --- [nio-9071-exec-1] c.t.c.analytics.KafkaConsumerController  : N100 = 11014
2023-12-24 22:17:21.555  INFO 17363 --- [nio-9071-exec-1] c.t.c.analytics.KafkaConsumerController  : NYAA = 10
