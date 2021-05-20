## Java For Android


Open JDK

Root: No Root & Root

Only support: arm + arm64 + x86_64


## How to install

Root: Install using Magisk

Import the zip file into the Magisk Module

No Root: Termux Run command

```
curl -#L https://github.com/kakathic/Tool-JDK/releases/download/Termux/install.sh -o "$HOME/install.sh" && bash install.sh
```
Or
```
pkg install wget && wget https://github.com/kakathic/Tool-JDK/releases/download/Termux/install.sh && bash install.sh
```

## Download

Root: [Link JDK](https://github.com/kakathic/Tool-JDK/releases/download/JDK16/Tool-JDK.zip)

No Root: Termux Run command

```
curl -#L https://github.com/kakathic/Tool-JDK/releases/download/Termux/install.sh -o "$HOME/install.sh" && bash install.sh
```
Or
```
pkg install wget && wget https://github.com/kakathic/Tool-JDK/releases/download/Termux/install.sh && bash install.sh
```

## NEW

Root:

New: In order for java to be used at recovery, use the following command

jdk_recovery

Use the jdk_recovery command before using the java command

New: feature allows upgrading by typing

su -c jdk_update /path/jdk_jre.tar.gz

It will automatically update to java jdk or jre

It will replace the current version.

No Root:

Used: upjdk /path/java_jdk_hostpot_linux.tar.xz

Used: xu xoa

Delete java termux

Used: xu [command]

Fake root


## How to use the command


For example:

Root: su -c java

Termux: java

Result:

```
Usage: java [-options] class [args...]
           (to execute a class)
   or  java [-options] -jar jarfile [args...]
           (to execute a jar file)
...
...
...
       show splash screen with specified image
See http://www.oracle.com/technetwork/java/javase/documentation/index.html for more details.
```


## End

This product is not mine. I just tweaked a few things.

Open JDK: [AdoptOpenJDK](https://adoptopenjdk.net)

Emulator to run java: [libc.so.6](https://packages.debian.org/search?searchon=contents&keywords=libc.so.6) | [libz.so.1](https://packages.debian.org/search?searchon=contents&keywords=libz.so.1)

Available emulators: [Lib, lib64](https://github.com/kakathic/Tool-JDK/tree/main/lib)
