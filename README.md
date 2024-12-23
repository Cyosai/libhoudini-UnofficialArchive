![IMG_3998](https://github.com/user-attachments/assets/d51aa0b8-a80c-4590-9aaf-40aa18827ad5)
# **libhoudini-archive-unofficial**

Work-in-progress archive that will contain all official Intel Houdini library files for:
***"Android KitKat (4.4)"***,
***"Android Lollipop (5.1)"***,
***"Android Marshmallow (6.0)"***,
***"Android Nougat (7.1)"***,
***"Android Oreo (8.1)"***,
***"Android Pie (9.0)"***

**Houdini (libhoudini)** is ARM and ARM64 translation layer for ***Android-x86***. Allows execution of applications for armeabi(arm), armeabi-v7a(arm) and arm64-v8a(arm64) architectures on x86-based devices.

**>[Important note<]:**
**Starting from Android 5, each new released version of libhoudini now has 3 variants:**

**x:** 32-bit x86 implementing 32-bit ARM (x86 arm)

**y:** 64-bit x86 implementing 32-bit ARM (x86_64 arm)

**z:** 64-bit x86 implementing 64-bit ARM (x86_64 arm64)

-------------------------------------

It is possible to use previous libhoudini series on newer ***Android x86*** systems

For example using libhoudini files that were created for ***"Android Oreo (8.1)"*** on ***"Android Pie (9.0)"***

-------------------------------------

**[ I ]**- Installation Method:

Before doing this installation method, system.img should be supercharged (e.g **/system directory should be mounted as read/write**)

By  installing **gearlock** and using **gearlock recovery**, ***Android x86*** system.img can be supercharged
or by using this guide:

https://docs.blissos.org/knowledgebase/troubleshooting/remount-system-as-read-write/
This guide initially was provided for **Bliss OS** - custom ***Android x86*** system.
But also can be used for other ***Android x86*** systems. **Bliss 15.x**
means - ***Android 12 x86***. **Bliss 14.x** - ***Android 11 x86***. **Bliss 11.x** - ***Android 9 x86*** in the provided guide.
