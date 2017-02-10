```
[root@c14n1 apps]#
[root@c14n1 apps]# vim /etc/auto.master
[root@c14n1 apps]# vim /etc/auto.home
[root@c14n1 apps]# vim /etc/auto.apps
[root@c14n1 apps]# service autofs stop
Redirecting to /bin/systemctl stop  autofs.service
[root@c14n1 apps]# cd /nfsroot/
[root@c14n1 nfsroot]# ls
apps
[root@c14n1 nfsroot]# rmdir apps
[root@c14n1 nfsroot]# service autofs start
Redirecting to /bin/systemctl start  autofs.service
[root@c14n1 nfsroot]# cd apps
[root@c14n1 apps]# df -h
Filesystem         Size  Used Avail Use% Mounted on
/dev/sda2           99G  3.7G   90G   4% /
devtmpfs           2.0G     0  2.0G   0% /dev
tmpfs              2.0G     0  2.0G   0% /dev/shm
tmpfs              2.0G   33M  1.9G   2% /run
tmpfs              2.0G     0  2.0G   0% /sys/fs/cgroup
/dev/sda1          976M  115M  794M  13% /boot
tmpfs              396M     0  396M   0% /run/user/0
10.10.10.87:/apps   99G  3.8G   90G   5% /nfsroot/apps


```