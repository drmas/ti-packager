# Ti-Packager

Appcelerator Titanium hook to build small APK file by separating ARM and X86 versions

## Installation

Still not available yet.

~~~
$ [sudo] npm install -g ti-packager
~~~

## Usage

Then you can use it by simply adding the following line to your tiapp.xml file.

~~~
  <property name="ti.packager.separate" type="bool">true</property>
~~~

Ti-Packager will modify the tiapp.xml to target different archeticture, it will produce [app-name]-ARM.apk and [app-name]-x86.apk

## Licence MIT
