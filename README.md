# CameraNextMod

About CameraNextMod
===================

CameraNextMod was originally designed/developed by @abhi08638. However due to less time, he abandoned the project.
FireHound team has updated the app from v1 to v7 including 3 different icons designed by @Yeti12. The Camera app offers best UI/UX
along with features like Denoise, Slow-MO, Raw Support, HDR+. HFR, Panorama, Video stabilisation etc.  

Adding Support in your ROM
==========================

To build your ROM with CameraNextMod included in system, follow the steps:
--------------------------------------------------------------------------

1) Cloning the repo
-------------------

    git clone https://github.com/FireHound/android_packages_apps_CameraNextMod.git -b o packages/apps/CameraNextMod

2) Adding the package name
-----------------------

    nano vendor/$ROM_NAME/config/common.mk

    PRODUCT_PACKAGES += \
    CameraNextMod 

3) Start building
-----------------
