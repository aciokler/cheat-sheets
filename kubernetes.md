debuggin mysql deployment
kubectl exec --stdin --tty [mysql-pod-name] -- /bin/bash
mysql -u [user] -p
[enter password]
show databases;
