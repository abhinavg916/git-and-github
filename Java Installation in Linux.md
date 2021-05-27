# Java Installation (using tar) in Ubuntu
## Steps:
* Select path and folder name according to yourself
```
sudo apt-get update
sudo apt-get upgrade
tar -xzvf jdk-13.0.1_linux-x64_bin.tar.gz
sudo mv jdk-13.0.1 /usr/lib/jvm
sudo update-alternatives --install /usr/bin/java java /usr/lib/jvm/jdk-13.0.1/bin/java 1
sudo update-alternatives --config java
sudo update-alternatives --install /usr/bin/jar jar /usr/lib/jvm/jdk-13.0.1/bin/jar 1
sudo update-alternatives --install /usr/bin/javac javac /usr/lib/jvm/jdk-13.0.1/bin/javac 1
sudo update-alternatives --set jar /usr/lib/jvm/jdk-13.0.1/bin/jar
sudo update-alternatives --set javac /usr/lib/jvm/jdk-13.0.1/bin/javac
java -version
sudo nano /etc/profile.d/jdk13.0.1.sh
sudo nano /etc/profile.d/jdk13.0.1.sh
export J2SDKDIR=/usr/lib/jvm/java-13.0.1
export J2REDIR=/usr/lib/jvm/java-13.0.1
export PATH=$PATH:/usr/lib/jvm/java-13.0.1/bin:/usr/lib/jvm/java-13.0.1/db/bin
export JAVA_HOME=/usr/lib/jvm/java-13.0.1
export DERBY_HOME=/usr/lib/jvm/java-13.0.1/db
source /etc/profile.d/jdk13.0.1.sh
java -version
```
