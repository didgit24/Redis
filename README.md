# Redis
redis project

## Important Notes
Used to that we don't access SQL DB frequently, to save time.

To connect - Redis cloud console

SET-GET commands

Design - Figuring out queiries first.

Hash commands - HSET hashname key, value, key, value. HGET hashname key. HGETALL hashname. HEXISTS hashname key. DEL hashname. HDEL hashname key. HINCRBY. HINCRBYFLOAT.HSTRLEN. HSKEYS hashname, HVALS hashname.

serialize() and deserialize() function to format data in and out of Redis.

SADD key value - Adds a string to set

SMEMBERS key - Get all value from set

SUNION key1 key2 key3 - Get all values from all the keys and create a new set.

SINTER key1 key2 key3 - Get only the element common in all the sets and create a new set.

SDIFF key1 key2 key3 - Get only uncommon in all the set and create a new set.

SUNIONSTORE, SINTERSTORE, SDIFFSTORE key - Stores the results in the key.

SISMEMBER - Returns 1 or 0 if value is present in set.

SMISMEMBER - Check multiple values.

SADD - Add an element in set.

SREM - Remove an element from set.

SSCAN key cursorid COUNT number - Scan through all the elements in set.

