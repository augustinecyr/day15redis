## Introduction to Redis

1. Creating a database on Redis
2. Connecting to Redis on terminal // refer to commands.md
3. start.spring.io
4. Adding jedis from mvnrepository.com as a dependency in pom.xml // edit pom.xml
5. export REDIS_PASSWORD on Visual Code terminal. // refer to commands.md

## Settings for application.properties

1. spring.redis.host=redis-18323.c292.ap-southeast-1-1.ec2.cloud.redislabs.com
2. spring.redis.port=18323
3. spring.redis.database=0
4. spring.redis.username=default

## Using jedis
1. Create an instance
2. Create a factory
3. Create a RedisTemplate

## Using set-get in redis
1. set key value using set greetings "test"
2. get key value using get greetings or refresh localhost:8080 to see the changes.

## 