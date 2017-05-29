## The good


## RBD
### #1 Distributed Storage for OpenStack

Note: refer to OpenStack User Survey


### Glance/Cinder/Nova integration

Note: Explain how Glance, Cinder and Nova interact around Ceph RBD
with snapshots and clones, how this saves space, and what performance
benefits it has.


### Mirrored volumes

Note: Explain how RBD mirroring works, and how it ties in with Cinder
volume mirroring.


### cinder-backup

Note: Explain how we can use RBD for both incremental and full
backups, thanks to RBD `cinder-backup` integration.


## radosgw
### Drop-in workalike for OpenStack Swift


Added benefit:
### Swift/S3 mixed access


## Performance
### Throughput

Note: Explain how Ceph does a very good job on optimizing for
throughput.
