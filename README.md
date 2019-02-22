# git-folder-sync

#### crotab example
```
#Ansible: cron_sync
*/5 * * * * /bin/bash /usr/local/bin/git_folder_sync > /dev/null 2>&1
#Ansible: cron_conflicts
* */1 * * * /bin/bash /usr/local/bin/git_folder_conflicts > /dev/null 2>&1
```
