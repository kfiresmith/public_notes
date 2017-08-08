###A Safer Way to FSCK LVM-Based Partitions

**Create a snapshot, fsck the snapshot, merge the snapshot, if sane to do so

```
lvcreate -L##G -s -n name-snap /dev/someVG/someLV

fsck -a -C /dev/someVG/someLV-snapshot

lvconvert --merge /dev/someVG/someLV-snapshot
```
