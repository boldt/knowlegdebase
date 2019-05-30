# MediathekView

sudo apt remove openjdk* openjfx*
https://launchpad.net/~webupd8team/+archive/ubuntu/java



## Install

## Run

```bash
java -Xms128M -Xmx1G -jar /opt/MediathekView/MediathekView.jar 
```

Error:

```bash
. Portable Mode: false
Exception in thread "main" java.lang.NoClassDefFoundError: javafx/concurrent/Task
```

## Install Java 8

sudo apt install openjdk-8-jdk openjfx
/usr/lib/jvm/java-8-openjdk-amd64/jre/bin/java -Xms128M -Xmx1G -jar MediathekView.jar


## Sources

* http://ubuntuhandbook.org/index.php/2017/04/install-the-latest-keepass2-2-35-in-ubuntu-16-04-16-10-14-04/


