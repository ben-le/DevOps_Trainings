### Disk Management

Disk management in Linux involves various tasks related to managing storage devices and partitions, optimizing disk usage, and ensuring data integrity and performance. Here are the key aspects of disk management:

#### 1. Partitioning

Partitioning is the process of dividing a physical disk into multiple logical sections called partitions. Each partition behaves like a separate disk with its own filesystem and mount point. Common partitioning tools include `fdisk`, `parted`, and `gparted`.

**Basic Partitioning Commands:**
- `fdisk /dev/sdx`: Start `fdisk` for the specified disk.
- `p`: Print the partition table.
- `n`: Create a new partition.
- `d`: Delete a partition.
- `w`: Write changes to disk.

#### 2. Formatting Filesystems

Once a partition is created, it needs to be formatted with a filesystem before use. Popular filesystems in Linux include `ext4`, `XFS`, and `Btrfs`. Formatting prepares the partition to store files and directories.

**Formatting Commands:**
- `mkfs.ext4 /dev/sdx1`: Format partition as `ext4`.
- `mkfs.xfs /dev/sdx1`: Format partition as `XFS`.
- `mkfs.btrfs /dev/sdx1`: Format partition as `Btrfs`.

#### 3. Mounting Filesystems

Mounting makes the filesystem accessible to the operating system by associating it with a directory (mount point) in the filesystem hierarchy. This allows users and applications to read from and write to the filesystem.

**Mounting Commands:**
- `mount /dev/sdx1 /mnt`: Mount partition to `/mnt`.
- `umount /mnt`: Unmount partition from `/mnt`.

#### 4. Managing Logical Volumes (LVM)

LVM provides a flexible and efficient way to manage disk space by allowing volumes to span multiple physical disks. It includes logical volumes (LVs), volume groups (VGs), and physical volumes (PVs).

**LVM Commands:**
- `pvcreate /dev/sdx1`: Create a physical volume.
- `vgcreate vgname /dev/sdx1`: Create a volume group.
- `lvcreate -L 10G -n lvname vgname`: Create a logical volume.

#### 5. Monitoring Disk Usage

Monitoring disk usage helps ensure adequate space is available and identifies potential issues such as low disk space or excessive usage.

**Monitoring Commands:**
- `df -h`: Display disk space usage.
- `du -h`: Estimate file space usage.

#### 6. RAID (Redundant Array of Independent Disks)

RAID combines multiple disks into a single logical unit for data redundancy, performance improvement, or both. Common RAID levels include RAID 0, RAID 1, RAID 5, and RAID 10.

**RAID Commands:**
- `mdadm --create /dev/md0 --level=1 --raid-devices=2 /dev/sdx1 /dev/sdx2`: Create a RAID 1 array.

#### 7. Disk Maintenance and Troubleshooting

Regular maintenance includes tasks like checking disk health, repairing filesystems, and optimizing disk performance. Troubleshooting involves identifying and resolving disk-related issues such as disk errors or corrupted data.

**Maintenance and Troubleshooting Commands:**
- `smartctl -a /dev/sdx`: Check disk health with SMART.
- `fsck /dev/sdx1`: Check and repair filesystem.

Disk management is essential for maintaining system stability, ensuring data availability, and optimizing storage resources in Linux environments.
