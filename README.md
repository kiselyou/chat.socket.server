###### Socket.io helpful links
- https://socket.io
- https://socket.io/docs/server-api/
- https://socket.io/docs/emit-cheatsheet/
- https://socket.io/docs/rooms-and-namespaces/

###### Redis, PUB/SUB helpful links
- https://redis.io/topics/quickstart
- https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-redis-on-ubuntu-16-04
- https://redis.io/topics/rediscli
- https://redis.io/topics/pubsub
- https://github.com/NodeRedis/node_redis
- https://github.com/socketio/socket.io-redis
- https://github.com/socketio/socket.io-emitter

##### Redis commands
1. Connect to redis
    ``` redis-cli -r 1 -h localhost -p 6379```
2. Subscribe to chanel by pattern
    ```psubscribe '*'```
3. Monitor events
    ```redis-cli monitor```
4. Subscribe to chanel
    ```SUBSCRIBE chanel1```
5. Publish message to chanel
    ```PUBLISH chanel1```
6. Change DB
    ```select 2```
7. Count keys
    ```dbsize```