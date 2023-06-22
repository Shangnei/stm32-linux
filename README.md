# stm32-linux
## 这是一个在linux 环境下使用的stm32f103c8的固件库
## 基于官方的3.5版本
# 使用前环境准备
>arm-none-eabi  编译工具链

>st-link        下载工具
>>命令是   $ st-flash write firmware.bin 0x8000000  具体查看doc/man里面的手册
# 使用
>进入build文件夹  $ make
