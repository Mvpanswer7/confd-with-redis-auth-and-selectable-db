# confd
https://github.com/kelseyhightower/confd
conf:
========
[template]
backend = "redis"
confdir = "/path/to/confd/conf/file"
log-level = "debug"
interval = 10
nodes = [
  "127.0.0.1:6379",
]
client_key = "/auth/password"
#use app_id to select db
app_id = "1"
noop = false
sync-only = false
watch = false
