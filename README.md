# Angular
AngularJS is a high-level language framework used for designing and building web applications, coupled with HTML
Development attemp on porting to Windows 7 platform instead of Android.

AV streaming using exoplayer in Windows

Software Architecture
=================================================================================================
NodeJS, Angular JS, JSON, AJAX data binding for video stream using ABR ( built-in) from EXOPLAYER.
JDK8
Windows 7 64 bit
TCP/IP ( websocket )

1.  Install XAMMP (Windows Apache + MariaDB + PHP 7.3.6 + Perl ), NodeJS v12.4.0

2.  Install Eclipse
Eclipse IDE for Enterprise Java Developers.
Version: 2019-03 (4.11.0)
Build id: 20190314-1200
OS: Windows 7, v.6.1, x86_64 / win32
Java version: 1.8.0_211

3.  Install Tomcat 9 as service and unzip to xampp folder.  Gernerate KeyStore for HTTPS TLS.
keytool -genkey -alias tomcat9 -keyalg RSA -keystore E:\xampp\tomcat\

4.  

5.  E:\Program Files\nodejs>npm install -g @angular/cli
E:\Program Files\nodejs>ng --version

     _                      _                 ____ _     ___
    / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
   / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
  / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
 /_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
                |___/


Angular CLI: 8.1.0
Node: 12.4.0
OS: win32 x64
Angular:
...

Package                      Version
------------------------------------------------------
@angular-devkit/architect    0.801.0
@angular-devkit/core         8.1.0
@angular-devkit/schematics   8.1.0
@schematics/angular          8.1.0
@schematics/update           0.801.0
rxjs                         6.4.0

