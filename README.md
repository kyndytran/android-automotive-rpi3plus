# android-automotive-rpi3plus
This project is based on android RPI3 project from Chinese Engineer (https://github.com/brobwind/pie-device-brobwind-rpi3/)

After steps Apply patch to Android framework (https://github.com/brobwind/pie-device-brobwind-rpi3/blob/master/README.md#apply-patch-to-android-framework), please do the following steps:

1. Clone my patches:

git clone https://github.com/tranchikha/android-automotive-rpi3plus

2. Apply to build Android Automotive:

>> 2.1. cd device/brobwind/rpi3/
 
>> 2.2. git am ../../../android-automotive-rpi3plus/*.patch

3. Continue doing from step Configure build environment to build your android images.
