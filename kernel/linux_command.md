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

## show pid of some program
pidof app\_name

## port repost, LISTEN-bind: --->  fork TCP4
socat  -d -d -lf socat.log TCP4-LISTEN:23456,bind=10.0.212.101,reuseaddr,fork TCP4:10.0.220.134:12345

## awk split only partial
echo "one:two:three:four:five:six" | awk '{sub(/:/," ")}1'

