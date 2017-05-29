## The good


## RBD
### #1 Distributed Storage for OpenStack

Note: refer to OpenStack User Survey


### Glance/Cinder/Nova integration
Snapshots/Clones

Note: Explain how Glance, Cinder and Nova interact around Ceph RBD
with snapshots and clones, how this saves space, and what performance
benefits it has.


### Block storage QoS
VirtIO-SCSI

Note: Explain how we get I/O tuning and TRIM/DISCARD support via
virtio-scsi.


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


## Updates

Note: Explain that updates in Ceph are normally a very smooth affair
(much smoother than OpenStack upgrades, for example). This even
includes the process of completely swapping out an OSD backend.
