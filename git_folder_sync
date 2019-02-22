#!/bin/bash
cd /root/synced_folder && git pull origin master
# If something changed
if [ ! -z "$(cd /root/synced_folder && git status --porcelain)" ];
    then
    # Something changed
    cd /root/synced_folder && git add . && git commit -a -m 'auto commit' && git push origin master
    fi
