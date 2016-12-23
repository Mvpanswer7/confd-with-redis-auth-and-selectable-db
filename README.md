# confd
https://github.com/kelseyhightower/confd
conf:
========
[template]
backend = "redis" \<br>
confdir = "/path/to/confd/conf/file"\<br>
\<br>
log-level = "debug" \<br>
interval = 10 \<br>
nodes = [ \<br>
  "127.0.0.1:6379", \<br>
] \<br>
client_key = "/auth/password" \<br>
use app_id to select db \<br>
app_id = "1" \<br>
noop = false \<br>
sync-only = false \<br>
watch = false \<br>
