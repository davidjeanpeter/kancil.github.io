
---
title: Rclone, commands used
feed: show
date: 11-02-2014
format: list

---
# Common RClone Commands
Well, common for me...

### Dropbox >  Local
```
rclone copy remote:folder /destination/folder  --tpslimit 12 --tpslimit-burst 0 --transfers=2 -vv  --log-file=folder-copy.txt

rclone sync remote:folder /destination/folder  --tpslimit 12 --tpslimit-burst 0 --transfers=2 -vv  --log-file=folder-sync.txt

rclone check remote:folder /destination/folder  --tpslimit 12 --tpslimit-burst 0 --transfers=2 -vv  --log-file=folder-check.txt --one-way
```
## Google Drive > Local


## One Drive > Local 


## Local > Glacier 