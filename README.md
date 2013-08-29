BroadcomCM kernel auto-maker menu
=================================

Quick Summary:
 * This script is used to build a kernel for all the BroadcomCM devices using a common source. Due to all the devices have a common source and different modules, this script will identify each of the device you select and build a working zImage for each. This menu will also include an option to pack the ramdisk automaticly before zImage is done.
 * Our kernel are included on GPL License, so this Menu will be also open sourced and everyone can contribute to help us.
 * This script should be with Kernel, Ramdisk folder. Inside Kernel folder common and modules_device and Ramdisk files inside Ramdisk folder

TO-DO List
 * Be able to start the script
 * Be able to select your defconfig on the Menu.
 * Automaticly make a 'make clean' to ensure a good zImage will be built
 * Create an option to go through menuconfig and save your changes.
 * Be able to rename modules_device to modules and make sure build of zImage does not fail.
 * When zImage is done, be able to copy into the ramdisk section
 * Start the script were ramdiskk will be packed or not.
 * Ensure everything is working

Credits (alfabetical):
 * Bieltv.3
 * Lopicl.00
 * Spacecaker
