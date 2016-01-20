memcached
=========
Installs `memcached` and its config file.

Role Variables
--------------
| Variable | Description | Default value |
|----------|-------------|---------------|
|`memcached_listen`| Address on which the service should listen | `127.0.0.1` |
|`memcached_port` | Port on which the service should listen | `11211` |
|`memcached_max_memory_mb` | Maximum memory the service should use | `64` |
|`memcached_max_connections` | Maximum number of concurrent connections | `1024` |

Dependencies
------------
none

License
-------
BSD
