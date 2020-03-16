# Welcome to Sonatype Hacking Workshop - DevOps Days Jakarta!
##### Follow the instruction below.

## Windows
1. Install OpenJDK 1.8
   * Download this file: https://download.java.net/openjdk/jdk8u41/ri/openjdk-8u41-b04-windows-i586-14_jan_2020.zip
   * Unzip the downloaded file to folder of your choice, e.g., `C:\`
   * Set the path to `bin\` to `PATH` environment variable, e.g., `C:\java-se-8u41-ri\bin\`
   * Set the path to the installation folder to `JAVA_HOME` environment variable, e.g., `C:\java-se-8u41-ri\`

	   ###### Note:
	   > If download link doesn't work anymore, find the download link in https://jdk.java.net/java-se-ri/8-MR3

1. Download and install maven

## Linux
1. Install OpenJDK 1.8
	##### Method 1 (Easier)

   * Using apt-get: `sudo apt-get install openjdk-8-jdk`
   * Using yum: `su -c "yum install java-1.8.0-openjdk-devel"`
    
	##### Method 2
   * Download this file: https://download.java.net/openjdk/jdk8u41/ri/openjdk-8u41-b04-linux-x64-14_jan_2020.tar.gz
   * Run `tar xvf openjdk-*.tar.gz` to untar the downloaded file to folder of your choice, e.g., `/opt/`
   * Set the path to `bin/` to `PATH` environment variable, e.g., `/opt/java-se-8u41-ri/bin/`
   * Set the path to the installation folder to `JAVA_HOME` environment variable, e.g., `/opt/java-se-8u41-ri/`

1. Install OpenJDK 1.8
   * [Windows & Linux Installers](https://jdk.java.net/java-se-ri/8-MR3)
   * [Linux command line (apt-get/yum)](https://openjdk.java.net/install/) (sudo apt update first before installing)
   * [Mac](https://installvirtual.com/install-openjdk-8-on-mac-using-brew-adoptopenjdk/)
   * Make sure you are installing JDK 1.8, not the JRE.
   * Set environment variable in Windows: [https://www.architectryan.com/2018/08/31/how-to-change-environment-variables-on-windows-10/]
   * Set `JAVA_HOME` to the directory where JDK is installed, without the bin/ folder.
	
	###### Check the installation
	> Type `java -version` in command line. It should return `version "1.8.XXXXX"`
   

1. Install Maven : https://maven.apache.org/download.cgi

1. Install Python: https://www.python.org/downloads/

1. Download this code: https://github.com/roger-lau/jakarta-workshop

> Download using the `Clone or download` button on the top right corner. Do not use `git clone` command.

##### Great! You are done now. Reach out to others around you if you see them struggling. 

[Start now->](https://github.com/roger-lau/jakarta-workshop/blob/master/docs/index.md)