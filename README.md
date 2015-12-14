# OroRedisConfigBundle

Configuration enhancements for the application, based on the OroPlatform that will enable usage of the Redis for caching

### Requirements
Need to install redis-server.  
In Ubuntu Linux it can be installed via
``` bash
    sudo apt-get install redis-server
```

### Configuration
In parameters.yml need to add redis config section
``` yaml
    redis_dsn: "redis://password@host:port"
```

After this need to remove cache.

Installation on existed application and on clean application - the same.