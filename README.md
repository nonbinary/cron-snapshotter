# cron-snapshotter
Simple cronjob script to regurarly make snapshots of a btrfs subvolume

This script is intended to be put into a /etc/cron.weekly (or other /etc/cron directory).
It currently assumes you have a /etc/fstab entry for the root of your btrfs filesystem.
TODO: find a good system to regurarly remove old automatic snapshots.
