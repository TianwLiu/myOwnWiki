# Automatically mount network drive on Linux

- **install CIFS**

- **edit fstab**

  - e.g. 

    `//192.168.1.1/nas1 /home/leaf/openwrt cifs  credentials=/home/leaf/.credentials/openwrt,uid=leaf,gid=leaf,vers=1.0 0 0`

