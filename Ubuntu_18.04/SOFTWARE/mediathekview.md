# MediathekView

## Install

* Download `tar.gz` from https://mediathekview.de/download/
* Move unpacked folder to
* Install Java8 (see [Java.md](Java.md))

## Run

```bash
java -Xms128M -Xmx1G -jar /opt/MediathekView/MediathekView.jar 
```

## Errors

```bash
. Portable Mode: false
Exception in thread "main" java.lang.NoClassDefFoundError: javafx/concurrent/Task
```

* Ensure, you use Java 8!

```bash
/opt/java/jre1.8.0_212/bin/java -Xms128M -Xmx1G -jar MediathekView.jar
```

## Sources

* http://ubuntuhandbook.org/index.php/2017/04/install-the-latest-keepass2-2-35-in-ubuntu-16-04-16-10-14-04/


