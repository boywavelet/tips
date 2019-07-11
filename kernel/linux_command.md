# linux

## get page size
getconf PAGE\_SIZE  
getconf -a  ; show all info  
FILESIZEBITS   LEVEL1\_ICACHE\_SIZE  

## create ram disk
mkdir -p /mnt/ram   
mount -t tmpfs tmpfs /mnt/ram -o size=8192M  

## edit the last command
fc   

## exit terminal and leave all processes running
disown -a && exit   

## redo last command but as root
sudo !!  

## open an editor to run a command
ctrl+x+e   


