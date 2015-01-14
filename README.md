SOURCE KERNEL EVERCOSS A7S*
===========================


Setting Toolchain
_________________
export PATH=~/Your_Toolchain_PATH/
for example :

/alps/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.6/bin
or
export CROSS_COMPILE="/home/dadi/android/toolchain/arm-eabi-linaro-4.6.2/bin/arm-eabi-"


Kernel
______
cd <kernel directory>

Build Command :

TARGET_PRODUCT=wiko MTK_ROOT_CUSTOM=../mediatek/custom/ MTK_PATH_SOURCE=../mediatek/kernel/ MTK_PATH_PLATFORM=../mediatek/platform/mt6572/kernel/ make
