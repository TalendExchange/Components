## <img src='./logo.jpg' width='40' height='40'>tInfobrightOutput

### Overview
A connector to Infobright's fast bulk loader. See http://www.infobright.org/
### Images




#### Release Notes

##### 2.2.2 - 2009-03-27 21:42:08
In order to use this component, you must obtain a copy of the Infobright core library (infobright-core-2.2.2.jar) and copy it into the component directory. infobright-core.2.2.2.jar is distributed under the MIT license.

Note: As of March '09, only the Linux version of ICE supports this connector. Solaris and Windows support are planned in the near future.
##### 2.4 - 2009-05-05 15:44:44
In order to use this component, you must obtain a copy of the Infobright core library (infobright-core-2.4.jar) and copy it into the component directory. infobright-core.2.4.jar is distributed under an MIT-style license.

The connector shows up under Databases -> MySQL in the palette.

Install note: The path to the component is hardcoded for TOS 3.0.4. If you are installing to 3.1.0, you will need to update the install path to the component under the plugins directory.

Note: As of March '09, only the Linux and Solaris versions of Infobright support this connector. Windows support is planned in the near future.

##### 3.1 - 2009-07-10 13:51:52
In order to use this component, you must obtain a copy of the Infobright core library (infobright-core-2.4.1.jar) and copy it into the component directory. infobright-core.2.4.1.jar is distributed under an MIT-style license. It is available from Infobright's Contributed Software page, http://www.infobright.org/Downloads/Contributed-Software/

The connector shows up under Databases -> MySQL in the palette.

Install note: The path to the component is hardcoded for TOS 3.1.3. If you are installing to a different version of Talend, you will need to update the install path to the component under the plugins directory.

Note: As of July '09, only the Linux and Solaris versions of Infobright support this connector. Windows support is planned in the near future.
##### 3.2 - 2009-08-17 15:38:33
In order to use this component, you must obtain a copy of the Infobright core library (infobright-core-2.6.jar) and copy it into the component directory. infobright-core.2.6.jar is distributed under an MIT-style license. It is available from Infobright's Contributed Software page, http://www.infobright.org/Downloads/Contributed-Software/

The connector shows up under Databases -> MySQL in the palette.

Install note: The path to the component is hardcoded for TOS 3.1.3. If you are installing to a different version of Talend, you will need to update the install path to the component under the plugins directory.

Note: As of August '09, only the Linux and Solaris versions of Infobright support this connector. Windows support is planned in the near future.

Changes from Release 3.1:
- Fixed bug related to multi-byte character set support

##### 3.3 - 2009-10-29 19:52:51
In order to use this component, you must obtain a copy of the Infobright core library (infobright-core-2.7.jar) and copy it into the tInfobrightOutput directory.

To use this component under Microsoft Windows, you must be using Infobright 3.2.1 or later. You must also obtain and install infobright_jni.dll into C:\\WINDOWS or an accessible DLL library path. If you are running a 32-bit JVM then rename infobright_jni_32bit.dll to infobright_jni.dll. If you are running a 64-bit JVM then rename infobright_jni_64bit.dll to infobright_jni.dll.

These required libraries are available from Infobright's Contributed Software page, http://www.infobright.org/Downloads/Contributed-Software/, in the "Connector Core Library 2.7" package, under an MIT-style license. 

tInfobrightOutput shows up under Databases -> MySQL in the TOS palette.

Install note: The path to the component is hardcoded for TOS 3.1.3. If you are installing to a different version of Talend, you will need to update the install path to the component under the plugins directory.

Changes from Release 3.2:
- support for Windows (requires Infobright 3.2.1 or later)
- Fix NullPointerException on empty (zero-length) fields
- compatibility with JDK 1.5 and 1.6

Limitations:
- This component currently cannot be used to load data remotely from one server to another. The computer running Talend must be the local host where Infobright is running.

##### 3.4 - 2009-12-03 20:27:00
In order to use this component, you must obtain a copy of the Infobright core library (infobright-core-3.0-remote.jar) and copy it into the tInfobrightOutput directory.

To use this component under Microsoft Windows, you must be using Infobright 3.2.1 or later. You must also obtain and install infobright_jni.dll into C:\\WINDOWS or an accessible DLL library path. If you are running a 32-bit JVM then rename infobright_jni_32bit.dll to infobright_jni.dll. If you are running a 64-bit JVM then rename infobright_jni_64bit.dll to infobright_jni.dll.

These required libraries are available from Infobright's Contributed Software page, http://www.infobright.org/Downloads/Contributed-Software/, in the "Connector Core Library 3.0" package, under an MIT-style license.

tInfobrightOutput shows up under Databases -> MySQL in the TOS palette.

Install note: The path to the component is hardcoded for TOS 3.1.3. If you are installing to a different version of Talend, you will need to update the install path to the component under the plugins directory.

Changes from Release 3.3:
- support for remote load (loading from one server to another)
##### 3.5 - 2010-09-14 21:55:39
Due to licensing considerations, in order to use this component, you must separately obtain a copy of the Infobright core library (infobright-core-3.2.jar) and copy this jar into the tInfobrightOutput directory.

To use this component under Windows, you must be using Infobright 3.2.1 or later. You must also obtain and install infobright_jni.dll into C:\\WINDOWS or an accessible DLL library path. If you are running a 32-bit JVM then rename infobright_jni_32bit.dll to infobright_jni.dll. If you are running a 64-bit JVM then rename infobright_jni_64bit.dll to infobright_jni.dll.

These required components are available from Infobright's Contributed Software page, http://www.infobright.org/Downloads/Contributed-Software/ in the "Connector Core Library 3.2" package, under an MIT-style license.

tInfobrightOutput shows up under Databases -> MySQL in the TOS palette.

New features in this release:
1) Update Infobright core library version to 3.2
2) Fix for debug mode
3) minor bug fixes


##### 3.6 - 2010-10-08 18:51:27
Due to licensing considerations, in order to use this component, you must separately obtain a copy of the Infobright core library (infobright-core-3.3.jar) and copy this jar into the tInfobrightOutput directory.

To use this component under Windows, you must be using Infobright 3.2.1 or later. You must also obtain and install infobright_jni.dll into C:\\WINDOWS or an accessible DLL library path. If you are running a 32-bit JVM then rename infobright_jni_32bit.dll to infobright_jni.dll. If you are running a 64-bit JVM then rename infobright_jni_64bit.dll to infobright_jni.dll.

These required components are available from Infobright's Contributed Software page, http://www.infobright.org/Downloads/Contributed-Software/ in the "Connector Core Library 3.3" package, under an MIT-style license.

tInfobrightOutput shows up under Databases -> MySQL in the TOS palette.

New features in this release:
1) Update Infobright core library version to 3.3
2) Correct checking of string length with multi-byte character set
3) 5-20x remote load performance improvement via use of LOAD DATA LOCAL INFILE (requires IB 3.5.0+ with Talend running on Linux/Unix).

##### 3.7 - 2010-11-08 16:58:15
Due to licensing considerations, in order to use this component, you must separately obtain a copy of the Infobright core library (infobright-core-3.4.jar) and copy this jar into the tInfobrightOutput directory.

To use this component under Windows, you must be using Infobright 3.2.1 or later. You must also obtain and install infobright_jni.dll into C:\\WINDOWS or an accessible DLL library path. If you are running a 32-bit JVM then rename infobright_jni_32bit.dll to infobright_jni.dll. If you are running a 64-bit JVM then rename infobright_jni_64bit.dll to infobright_jni.dll.

These required components are available from Infobright's Contributed Software page, http://www.infobright.org/Downloads/Contributed-Software/ in the "Connector Core Library 3.4" package, under an MIT-style license.

tInfobrightOutput shows up under Databases -> MySQL in the TOS palette.

New features in this release:
1) Update Infobright core library version to 3.4
2) Correct escaping of embedded backslash characters in Community mode

### Compatible
 -  3.0 (obsolete)
 -   3.1 (obsolete)
 -   3.2 (obsolete)
 -   4.0 (obsolete)
 -   4.1 (obsolete)