# SP_DEVKIT_ZYNQ7010-20

## Change list version 1.3
 - 把EMMC替换为SD+电平转换，即使这个SD并不能用于启动，但是使用SD卡成本仍然更低
 - 修改了PL电平为1.8V 3.3V可调
 - 更新了KiCAD版本为8.06

## 感谢Spray0的开源工作

## 🤖ZYNQ7010-20 开源开发板 核心板
* 基于xilinx公司ZYNQ7000系列低端入门型号7010、7020，旨在为开发者提供经济的入门开发工具🌱
* ⚠️请阅读PCB工程须知系列pdf文件
  - 📄[pcb须知1-工程声明.pdf](https://github.com/Spray0/SP_DEVKIT_ZYNQ7010-20/blob/main/%E3%80%90%E9%87%8D%E8%A6%81%E3%80%91pcb%E9%A1%BB%E7%9F%A51-%E5%B7%A5%E7%A8%8B%E5%A3%B0%E6%98%8E.pdf) 👈
  - 📄[pcb须知2-基本功能测试.pdf](https://github.com/Spray0/SP_DEVKIT_ZYNQ7010-20/blob/main/%E3%80%90%E9%87%8D%E8%A6%81%E3%80%91pcb%E9%A1%BB%E7%9F%A52-%E5%9F%BA%E6%9C%AC%E5%8A%9F%E8%83%BD%E6%B5%8B%E8%AF%95.pdf) 👈

## 📁文件说明
#### ⭐核心板工程文件：[*ZYNQ7000_10_20_core_v1.0_20221204_LE.zip*](https://github.com/Spray0/SP_DEVKIT_ZYNQ7010-20/blob/main/ZYNQ7000_10_20_core_v1.0_20221204_LE.zip)
<img src=".\image\zynq_01.JPG" height = "300" alt="brd1" />  <img src=".\image\zynq_02.JPG" height = "300" alt="brd2" />

> 绿色阻焊，6层嘉立创免费工艺，JLC06161H-3313

#### 🐵测试用底板工程文件A：[*ZYNQ7000_MINIMB_A_blink.zip*](https://github.com/Spray0/SP_DEVKIT_ZYNQ7010-20/blob/main/ZYNQ7000_MINIMB_A_blink.zip)
* 此底板工程不推荐使用，功能有限，作者点灯验证使用🐸
* 1x PS-GbE
* 1X 2bit boot mode switch
* 1x Reset button
* 1x PS-UART2USB
* 1x ZYNQ JTAG connector
* 1x USB
* 1x HDMI-A
* 1x 40p 扩展差分IO连接器
<img src=".\image\zynq_minimb_a.JPG" height = "350" alt="brd" />

> 绿色阻焊，4层嘉立创免费工艺

#### 🐢测试用底板工程文件B：[*ZYNQ7000_MINIMB_blink.zip*](https://github.com/Spray0/SP_DEVKIT_ZYNQ7010-20/blob/main/ZYNQ7000_MINIMB_blink.zip)
* 此底板工程不推荐使用，功能有限，作者点灯验证使用🐸
* 1x PS-GbE
* 1X 2bit boot mode switch
* 1x Reset button
* 1x PS-UART2USB
* 1x ZYNQ JTAG connector
<img src=".\image\zynq_minimb.JPG" height = "280" alt="brd" />

> 绿色阻焊，2层嘉立创免费工艺

#### 🐟测试用软件 📁[software](https://github.com/Spray0/SP_DEVKIT_ZYNQ7010-20/tree/main/software)
- 🆚Vivado&sdk(2018.3) zynq_blink工程：[zynq_blink.zip](https://github.com/Spray0/SP_DEVKIT_ZYNQ7010-20/blob/main/software/zynq_blink.zip)
- 🐧PetaLinux 固件（SD启动）：[petalinux_image_sd](https://github.com/Spray0/SP_DEVKIT_ZYNQ7010-20/tree/main/software/petalinux_image_sd)
> 登录用户：root 密码: passwd
