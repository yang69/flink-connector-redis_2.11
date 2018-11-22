# Flink Connector Redis

forked from org.apache.bahir:flink-connector-redis_2.11:1.0

test on JDK8, flink 1.4.2

```
<dependency>
  <groupId>com.github.yang69</groupId>
  <artifactId>flink-connector-redis_2.11</artifactId>
  <version>1.0</version>
</dependency>
```

# Change Log | 更改日志

1.0 add support for SETEX, as a result, you will need to implement getSecondsFromData(), which returns the expire seconds for the key.

1.0 增加了对 SETEX 的支持，需要实现 getSecondsFromData() 方法，该方法返回期望设置的过期时间（单位为秒）