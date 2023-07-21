# Install Tomcat 9 on Debian 12

## Install prerequisites
```
sudo apt install libeclipse-jdt-core-java
sudo apt install openjdk-17-jdk
sudo apt install rsyslog
```

## Get Debian packages
```
wget https://deb.debian.org/debian/pool/main/t/tomcat9/libtomcat9-java_9.0.70-2_all.deb
wget https://deb.debian.org/debian/pool/main/t/tomcat9/tomcat9-common_9.0.70-1_all.deb
wget https://deb.debian.org/debian/pool/main/t/tomcat9/tomcat9_9.0.70-1_all.deb
```

## Install Debian packages
```
sudo dpkg -i libtomcat9-java_9.0.70-2_all.deb
sudo dpkg -i tomcat9-common_9.0.70-1_all.deb
sudo dpkg -i tomcat9_9.0.70-1_all.deb
```
