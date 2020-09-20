# freenas-backup-nextcloud

##Backup Nextcloud data directories

### Add Nextcloud BR-config and NextcloudBR.sh to the nextcloud /usr directory

Edit NextcloudBR-config

Create a mount point for /mnt/v1/NextcloudBackups to /mnt/NextcloudBackups in the jail

Will create these files in the backupMainDir variable that is a mount point in the jail

nextcloud-datadir.tar.gz

nextcloud-db.sql

nextcloud-filedir.tar.gz
