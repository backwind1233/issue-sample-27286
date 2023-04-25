# issue-sample-27286
# good
```

spring:
  cloud:
    azure:
      cosmos:
        endpoint: ${input_endpoint}
        database: ${input_database}
        key: ${input_key}
        client:
          logging:
            level: headers
            allowed-header-names: User-Agent

logging:
  level:
    root: debug
```
