login as: root
root@10.10.10.36's password:
Last login: Thu Feb  9 13:03:40 2017 from c18n2.netwebdel.com
[root@fs2client01 ~]# is
iscsiadm                  isdv4-serial-inputattach  iso-read
iscsid                    isodebug                  isosize
iscsi-iname               isodump                   isovfy
iscsistart                isoinfo
iscsiuio                  iso-info
[root@fs2client01 ~]# is
iscsiadm                  isdv4-serial-inputattach  iso-read
iscsid                    isodebug                  isosize
iscsi-iname               isodump                   isovfy
iscsistart                isoinfo
iscsiuio                  iso-info
[root@fs2client01 ~]# iscsiadm -m discovery -t st -p 10.10.10.242
iscsiadm: No portals found
[root@fs2client01 ~]# iscsiadm -m node -l  -p 10.10.10.242
iscsiadm: No records found
[root@fs2client01 ~]#

