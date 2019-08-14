# JDB

## debug start
jdb -connect com.sun.jdi.ProcessAttach:pid=   
-Xdebug -Xrunjdwp:transport=dt_socket,address=12345,server=y,suspend=n   

## show configs
java -XX:+PrintFlagsFinal <GC options> -version   

## show heap 
jmap -heap <pid>   

