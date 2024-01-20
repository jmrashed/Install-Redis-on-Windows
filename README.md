# Install-Redis-on-Windows
Doenload `Redis-x64-3.0.504.msi` and install for redis server


# How to use 

# Redis-cli Command Examples

## Connection
- `redis-cli` - Connect to the Redis server.
- `AUTH password` - Authenticate to the server.
- `QUIT` - Close the connection.

## Key Commands
- `SET key value` - Set the value of a key.
  Example: `SET mykey "Hello"`

- `GET key` - Get the value of a key.
  Example: `GET mykey`

- `DEL key [key ...]` - Delete one or more keys.
  Example: `DEL mykey`

- `EXISTS key` - Check if a key exists.
  Example: `EXISTS mykey`

- `KEYS pattern` - Find all keys matching the given pattern.
  Example: `KEYS my*`

- `TTL key` - Get the time to live for a key.
  Example: `TTL mykey`

## String Commands
- `APPEND key value` - Append a value to a key.
  Example: `APPEND mykey " World"`

- `STRLEN key` - Get the length of the value stored in a key.
  Example: `STRLEN mykey`

## List Commands
- `LPUSH key value [value ...]` - Prepend one or multiple values to a list.
  Example: `LPUSH mylist "value1" "value2"`

- `RPUSH key value [value ...]` - Append one or multiple values to a list.
  Example: `RPUSH mylist "value3" "value4"`

- `LPOP key` - Remove and get the first element in a list.
  Example: `LPOP mylist`

- `RPOP key` - Remove and get the last element in a list.
  Example: `RPOP mylist`

- `LRANGE key start stop` - Get a range of elements from a list.
  Example: `LRANGE mylist 0 -1`

## Set Commands
- `SADD key member [member ...]` - Add one or more members to a set.
  Example: `SADD myset "member1" "member2"`

- `SMEMBERS key` - Get all members of a set.
  Example: `SMEMBERS myset`

- `SISMEMBER key member` - Determine if a given value is a member of a set.
  Example: `SISMEMBER myset "member1"`

- `SREM key member [member ...]` - Remove one or more members from a set.
  Example: `SREM myset "member1"`

## Hash Commands
- `HSET key field value` - Set the value of a field in a hash.
  Example: `HSET myhash field1 "value1"`

- `HGET key field` - Get the value of a field from a hash.
  Example: `HGET myhash field1`

- `HGETALL key` - Get all fields and values from a hash.
  Example: `HGETALL myhash`

- `HDEL key field [field ...]` - Delete one or more fields from a hash.
  Example: `HDEL myhash field1`

## Pub/Sub Commands
- `SUBSCRIBE channel [channel ...]` - Subscribe to channels.
  Example: `SUBSCRIBE mychannel`

- `UNSUBSCRIBE [channel ...]` - Unsubscribe from channels.
  Example: `UNSUBSCRIBE mychannel`

- `PUBLISH channel message` - Publish a message to a channel.
  Example: `PUBLISH mychannel "Hello subscribers!"`

## Server Commands
- `INFO` - Get information and statistics about the server.
  Example: `INFO`

- `PING` - Ping the server.
  Example: `PING`

- `FLUSHDB` - Remove all keys from the current database.
  Example: `FLUSHDB`

# End of Redis-cli Command Examples
