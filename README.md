# Learn Linux Capabilities

```
getcap /usr/bin/ping

```


```
# Find id
ps -ef | grep /usr/sbin/sshd | grep -v grep

getpcaps <ID>

```

## In Kubernetes

```
image: nginx
...
securityContext:
  capabilities:
    add: ["SYS_TIME"]
    drop: ["CHOWN"]
```

