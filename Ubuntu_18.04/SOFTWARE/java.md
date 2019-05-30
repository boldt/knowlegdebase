# Java

## Install

### Java 8 by Oracle

```bash
sudo add-apt-repository ppa:webupd8team/java
sudo apt-get update
sudo apt-get install oracle-java8-installer
```

### Java 11 by Oracle

```bash
sudo apt install software-properties-common
sudo add-apt-repository ppa:linuxuprising/java
sudo apt update
sudo apt install oracle-java11-installer
```

## Change Java version

```bash
sudo update-alternatives --config java
```

## Verify Java version

```bash
java -version
```

## Automatically accept the Oracle License (e.g., for automated installations)

```bash
echo oracle-java10-installer shared/accepted-oracle-license-v1-1 select true | sudo /usr/bin/debconf-set-selections
echo oracle-java10-installer shared/accepted-oracle-licence-v1-1 boolean true | sudo /usr/bin/debconf-set-selections
```

## JavaFX

* Download Linux SDK from https://gluonhq.com/products/javafx/
* FXPATH=/opt/javafx/lib/

## JAVA_HOME

* https://linuxize.com/post/install-java-on-ubuntu-18-04/#set-the-java-home-environment-variable


# Sources

* https://linuxize.com/post/install-java-on-ubuntu-18-04/
* https://www.linuxuprising.com/2018/04/install-oracle-java-10-in-ubuntu-or.html
* https://linuxconfig.org/how-to-install-java-on-ubuntu-18-04-bionic-beaver-linux
