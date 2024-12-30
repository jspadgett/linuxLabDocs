Nfs notes 

#packages needed 
##nfs-kernel-server
##nfs-common

# important paths
## /etc/exports
### write lines as /path/to/share ip.of.host.or.network(rw,sync,no_subtree_check)
### view man page for extra options

# steps 
##install server
##configure /etc/exports
##run exportfs -a 
## restart nfs-kernel-server.server

# mount steps 
##mount -t nfs ip.of.server:/path/to/share /path/to/mount 

#fstab example
##example.hostname.com:/srv /opt/example nfs rsize=8192,wsize=8192,timeo=14,intr
#systemctl controls
##nfs-kernel-server



