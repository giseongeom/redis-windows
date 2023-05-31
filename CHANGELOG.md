# ChangeLog


## 2023.05.31
* Add redis 7.0.11 build with TLS support
* When using `--tls` argument, `--cacert` should be used, too
```bash
redis-cli -p $port --verbose --no-auth-warning -a "$secret" --tls --cacert cacert.pem -h $redis_server_IP PING
```


## 2020.09.26

* initial build
* `gcc`, `msys2` used

BACKWARDS INCOMPATIBILITIES / NOTES:
IMPROVEMENTS:
NEW FEATURES:
BUG FIXES: