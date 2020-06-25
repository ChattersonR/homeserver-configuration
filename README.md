Installs:
docker-ce
docker-compose
samba

Prereqs:
mkdir /mnt/storage

Files:
docker-compose@.service -> /etc/systemd/system/
docker-compose.yml -> /opt/docker-compose.yml
smb.conf -> /etc/samba/smb.conf
