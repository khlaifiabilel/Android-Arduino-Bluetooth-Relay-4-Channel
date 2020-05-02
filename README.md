<center><a href="https://developer.android.com/studio"><img src="https://www.xda-developers.com/files/2018/06/android-studio-featured-810x298_c.png" title="Android Studio" alt="Android Studio"></a></center>

# Android-Arduino-Automotive

<img alt="GitHub followers" src="https://img.shields.io/github/followers/kalifiabillal?color=yellow&label=kalifiabillal&style=for-the-badge">   <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/kalifiabillal/Android-Arduino-Automotive?style=for-the-badge">   <img alt="Visual Studio App Center (Minimum) OS Version" src="https://img.shields.io/visual-studio-app-center/releases/osver/kalifiabillal/Android-Arduino-Automotive/a87b9e745655355612fff4418953e0c3f7074250?style=for-the-badge">   <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/Kalifiabillal/Android-Arduino-Automotive?color=green&style=for-the-badge">   <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/y/kalifiabillal/Android-Arduino-Automotive?style=for-the-badge">   <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/Kalifiabillal/Android-Arduino-Automotive?color=pink&logo=pink&style=for-the-badge">
# Repository Titles

> How to Install Android Studio on Ubuntu 18.04

> Arduino project

# How to Install Android Studio on Ubuntu 18.04

![Android Studio](https://www.mindinventory.com/blog/wp-content/uploads/2020/03/Android-studio-36-1520x500.png)

Android Studio is a full-featured cross-platform IDE that helps you build applications on every type of Android device. It is based on JetBrains’ IntelliJ IDEA and includes everything you need for Android development.

Android Studio build system is powered by Gradle allowing you to create multiple build variants for different devices from a single project.

This tutorial explains how to install Android Studio on Ubuntu 18.04. The same instructions apply for Ubuntu 16.04 and any Ubuntu-based distribution, including Kubuntu, Linux Mint, and Elementary OS.

***Prerequisites***

You’ll need to be logged in as a user with sudo access to be able to install packages on your Ubuntu system.

***Installing Java OpenJDK***

Android Studio requires OpenJDK version 8 or above to be installed to your system.
We’ll install OpenJDK 8. The installation is pretty simple, start by updating the package index:

***Installing Java OpenJDK***

Android Studio requires OpenJDK version 8 or above to be installed to your system.
We’ll install OpenJDK 8. The installation is pretty simple, start by updating the package index:

```javascript
// Run

sudo apt update

```
Install the OpenJDK 8 package by typing:

```javascript
// Run

sudo apt install openjdk-8-jdk

```
Verify the installation by typing the following command which will print the Java version:

```javascript
// Run

java -version

```

The output should look something like this:

```javascript
// The output

openjdk version "1.8.0_191"
OpenJDK Runtime Environment (build 1.8.0_191-8u191-b12-2ubuntu0.18.04.1-b12)
OpenJDK 64-Bit Server VM (build 25.191-b12, mixed mode)

```
***Installing Android Studio***

At the time of writing this article, the latest stable version of Android Studio is version 3.3.1.0. The easiest way is to install Android Studio on Ubuntu 18.04 is by using the snappy packaging system.

To download and install the Android Studio snap package, open your terminal using the Ctrl+Alt+T keyboard shortcut and type:

```javascript
// run

sudo snap install android-studio --classic

```
Once the installation is complete, you will see the following output:

```javascript
// The output

android-studio 3.3.1.0 from Snapcrafters installed
```
That’s it. Android Studio has been installed on your Ubuntu desktop.

# Arduino project

![Arduino cover](https://scontent.ftun1-1.fna.fbcdn.net/v/t1.0-9/13645146_1429686307057684_8500685619593774449_n.png?_nc_cat=106&_nc_sid=dd9801&_nc_ohc=2S3wf_2HAFMAX84Stun&_nc_ht=scontent.ftun1-1.fna&oh=c67fbb17886d7f4eb1a21e474266c822&oe=5EBF053D)

***Arduino IDE***

The Arduino Integrated Development Environment is a cross-platform application that is written in functions from C and C++. It is used to write and upload programs to Arduino compatible boards, but also, with the help of 3rd party cores, other vendor development boards.

***Which language is used in Arduino IDE?***

The "Arduino language" is simply C++ (and therefore also C). All the standard system librarys are written in C/C++ and the IDE uses the gcc g++ compiler.

![Arduino](https://i.pinimg.com/564x/c6/b4/72/c6b4725ca5fcde572245ced9ade303be.jpg)

# FAQ

- **How do I do *specifically* so and so?**
    - No problem! Just do this.

# Support

Reach out to me at one of the following places!

- Linkedin at <a href="https://www.linkedin.com/in/kalifiabillal/" target="_blank">`Kalifiabillal`</a>
- Twitter at <a href="https://twitter.com/kalifiabillal" target="_blank">`@Kalifiabillal`</a>

# License

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2015 © <a href="https://github.com/KalifiaBillal" target="_blank">Kalifiabillal</a>.
