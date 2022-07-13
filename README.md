# kafka-ecosystem-playground

Navigate to the Control Center web interface at http://localhost:9021/ and select your cluster.

docker-compose up -d --build

"value.converter.schemas.enable": "false",

https://docs.confluent.io/platform/current/quickstart/ce-docker-quickstart.html#quickstart

CREATE STREAM USERS_STREAM (registertime BIGINT, userid STRING, regionid STRING, gender STRING) WITH (KAFKA_TOPIC='users-no-schema', KEY_FORMAT='KAFKA', VALUE_FORMAT='JSON');

References

Based in: https://github.com/confluentinc/cp-all-in-one/tree/7.1.1-post/cp-all-in-one
