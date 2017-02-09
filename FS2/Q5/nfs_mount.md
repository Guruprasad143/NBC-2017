```
login as: root
root@10.10.10.36's password:
Last login: Thu Feb  9 12:55:54 2017 from c18n2.netwebdel.com
[root@fs2client01 ~]# mount 10.10.10.242:/storage/disk2/nfs /mnt
mount.nfs: /mnt is busy or already mounted
[root@fs2client01 ~]# df -h
Filesystem                       Size  Used Avail Use% Mounted on
/dev/sda2                         99G  3.7G   90G   4% /
devtmpfs                         2.0G     0  2.0G   0% /dev
tmpfs                            2.0G     0  2.0G   0% /dev/shm
tmpfs                            2.0G   17M  2.0G   1% /run
tmpfs                            2.0G     0  2.0G   0% /sys/fs/cgroup
/dev/sda1                        976M  115M  794M  13% /boot
10.10.10.242:/storage/disk2/nfs   20G   32M   20G   1% /mnt
tmpfs                            396M     0  396M   0% /run/user/0
[root@fs2client01 ~]#


```