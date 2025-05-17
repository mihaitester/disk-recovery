# Idea
After using external HDD to store data, from `Windows` and trying to view the data in `Ubuntu`, got `NTFS` partition corrupted, due to using `sudo mount -f /dev/... /mnt/...`. 
The problem is actually caused by the `NTFS-3G` implementation on `Ubuntu`. 
1. So the idea is to recover files and folders from partitions that were not properly finalized and closed before mounting. If the data is lost then that is a huge problem.
2. The second point is to understand why this keeps happening and try to actually fix `NTFS-3G`, or potentially create or find different package to view data.