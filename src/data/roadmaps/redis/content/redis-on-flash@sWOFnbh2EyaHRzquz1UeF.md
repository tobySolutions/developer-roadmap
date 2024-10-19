# Redis on Flash

Redis on Flash is a feature of Redis Enterprise that allows users to extend the memory capacity of their Redis instances by utilizing SSDs (Solid State Drives) alongside traditional RAM. This enables organizations to store larger datasets at a lower cost while maintaining the high performance that Redis is known for.  In this configuration, frequently accessed data remains in RAM for fast access, while less frequently used data can be stored on Flash storage. Redis on Flash intelligently manages the data placement between memory and Flash, ensuring that performance is optimized by leveraging the speed of in-memory operations while still allowing for the efficient storage of larger datasets. This capability is particularly beneficial for use cases involving large-scale applications, such as caching, real-time analytics, and high-throughput data processing, as it allows organizations to handle big data workloads without the need for extensive investments in additional RAM.

Learn more from the following resources:

- [@official@Redis on Flash](https://redis.io/blog/redis-on-flash-now-3-7x-faster/)
- [@official@Redis on Flash Data Sheet](https://media.trustradius.com/product-downloadables/1V/DT/TCXS6PSOA64L.pdf)