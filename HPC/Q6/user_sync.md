```
guru@c14m ~]$ scp -r .ssh 10.10.10.88:/home/guru/
config                                        100%   32     0.0KB/s   00:00
known_hosts                                   100%  346     0.3KB/s   00:00
id_rsa.pub                                    100%  391     0.4KB/s   00:00
id_rsa                                        100% 1679     1.6KB/s   00:00
authorized_keys                               100%  391     0.4KB/s   00:00
[guru@c14m ~]$ ssh guru@10.10.10.88
Last failed login: Fri Feb 10 08:55:57 IST 2017 from c14m on ssh:notty
There were 11 failed login attempts since the last successful login.
[guru@c14n1 ~]$
```