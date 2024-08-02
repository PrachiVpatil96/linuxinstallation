#installling the softwares on linux instances using tar
**Instaling Openjdk from tar file**

#steps:
1.Ensure you have installed ubuntu in your system
2.Now download the openjdk-17 tar file
refer here [openjdk:17.0.1](https://download.java.net/java/GA/jdk17.0.1/2a2082e5a09d4267845be086888add4f/12/GPL/openjdk-17.0.1_linux-x64_bin.tar.gz)
3.Extract the tar file by following command: - tar xvzf openjdk-17.0.1_linux-x64_bin.tar.gz
4.Now install openjdk-17 on your system as follows
sudo apt update
sudo apt install openjdk-17-jdk -y
5.Once you have installed ,then you can check it by using
java -version
