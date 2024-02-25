# Linux Problem and fix
## Another app is currently holding the yum lock
```
cd ~
cat /var/run/yum.pid (get the pid)
ps aux | grep yum
kill -9 <your pid>
```
