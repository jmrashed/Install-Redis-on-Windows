# Install-Redis-on-Windows
Doenload `Redis-x64-3.0.504.msi` and install for redis server


# How to use 


# Redis-cli Commands

## Connection
- `redis-cli` - Connect to the Redis server.
- `AUTH password` - Authenticate to the server.
- `QUIT` - Close the connection.

## Key Commands
- `SET key value` - Set the value of a key.
- `GET key` - Get the value of a key.
- `DEL key [key ...]` - Delete one or more keys.
- `EXISTS key` - Check if a key exists.
- `KEYS pattern` - Find all keys matching the given pattern.
- `TTL key` - Get the time to live for a key.

## String Commands
- `APPEND key value` - Append a value to a key.
- `STRLEN key` - Get the length of the value stored in a key.

## List Commands
- `LPUSH key value [value ...]` - Prepend one or multiple values to a list.
- `RPUSH key value [value ...]` - Append one or multiple values to a list.
- `LPOP key` - Remove and get the first element in a list.
- `RPOP key` - Remove and get the last element in a list.
- `LRANGE key start stop` - Get a range of elements from a list.

## Set Commands
- `SADD key member [member ...]` - Add one or more members to a set.
- `SMEMBERS key` - Get all members of a set.
- `SISMEMBER key member` - Determine if a given value is a member of a set.
- `SREM key member [member ...]` - Remove one or more members from a set.

## Hash Commands
- `HSET key field value` - Set the value of a field in a hash.
- `HGET key field` - Get the value of a field from a hash.
- `HGETALL key` - Get all fields and values from a hash.
- `HDEL key field [field ...]` - Delete one or more fields from a hash.

## Pub/Sub Commands
- `SUBSCRIBE channel [channel ...]` - Subscribe to channels.
- `UNSUBSCRIBE [channel ...]` - Unsubscribe from channels.
- `PUBLISH channel message` - Publish a message to a channel.

## Server Commands
- `INFO` - Get information and statistics about the server.
- `PING` - Ping the server.
- `FLUSHDB` - Remove all keys from the current database.

# End of Redis-cli Commands
