# Streams

A Redis stream is a data structure that acts like an append-only log but can also implement multiple operations to overcome limits seen in typical append-only logs. These include random access in O(1) time and complex consumption strategies, such as consumer groups.