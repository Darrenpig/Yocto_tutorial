# Euler-junior_NXP
![NXP](image/NXP.png)
## openEluer Embedded BSP[雪球计划](https://gitee.com/openeuler/yocto-meta-openeuler/issues/I90DOU#comment-loadder)
#### 介绍

> 旨在对南向BSP的覆盖活动，目的是扩大openEuler对南向bsp的支持范围， “雪球计划”，寓意openEuler将一步步强大，最终成为国内乃至国际顶流嵌入式操作系统

 ### **本小组研究：NXP** 
| SOC型号 | soc厂商 | bsp型号 | 赞助商 | gitee id | 进度 | 完成时间 | 备注 |
|-------|-------|-------|-----|----------|----|------|----|
|i.MX 6ULL|NXP|MYD-Y6ULY2-V2-4E512D-50-I|米尔科技|@DarrenPig,@puai,@wei-app | | | |
|i.MX 8M Plus|NXP|MYD-JX8MPQ-8E2D-160-I|米尔科技|puai | | | |


![NXP板子](image/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202024-02-01%20152323.png)
## 项目要求
### 1.软件能合入master
### 2.基本镜像要能运行                                                                            


## 项目成员：  @puai 、@wei-app  、@DarrenPig 

![项目成员](image/Screenshot%202024-02-04%20185515.png)
## 项目进程：

- 1.30    ✅建立群聊
- 2.1     ✅sig组会议，创建仓库
- 2.4     ✅填写报名表
- 2.22    ✅收到imx8开发板, MYD-JX8MX(@DarrenPig )
- 2.23    ✅都在看文档

##  资料共享：

- [openEuler Embedded在线文档【社区文档】](https://openeuler.gitee.io/yocto-meta-openeuler/master/introduction/index.html)
- [SIG的双周议题](https://etherpad.openeuler.org/p/sig-Yocto-meetings)
- [2.1组会笔记](https://gitee.com/pai_666/euler-junior/tree/master/Files)
- [MYS-6ulx-io产品手册](https://www.myir-tech.com/down/manual/NXP/MYS-6ulx-iot_product_manual.pdf)
- [MYD-JX8MMA7产品介绍](https://www.myir-tech.com/public/files/MYD-JX8MMA7%E4%BA%A7%E5%93%81%E4%BB%8B%E7%BB%8D-V1.0.pdf)
- [imx8产品 手册、引脚定义、GPIO](http://mier.sz2.hostadm.net/upload/files/product/20230915/16947497869753189.pdf)
- [NXP的imx8芯片手册  i.MX 8M Mini Applications Processor Datasheet for Industrial Products](https://www.nxp.com.cn/docs/en/data-sheet/IMX8MMIEC.pdf)
- [【NXP官网】imx8的芯片介绍，详细内容](https://www.nxp.com/products/processors-and-microcontrollers/arm-processors/i-mx-applications-processors/i-mx-8-applications-processors/i-mx-8m-family-armcortex-a53-cortex-m4-audio-voice-video:i.MX8M?lang=en&lang_cd=en&)
- [【NXP官方】datesheet](https://www.nxp.com/docs/en/data-sheet/IMX8MDQLQIEC.pdf)
- [【Sig_B站21年录屏】yocto 技术分享第一期：yocto 构建系统之前世今生](https://www.bilibili.com/video/BV1WT4y1R7sK/?)
- [【学习资料-B站韦山东NXP】基于100ASK_IMX6ULL开发板的lvgl学习+开发教程](http://download.100ask.net/boards/Nxp/100ask_imx6ull_pro/index.html
)
- [【韦东山】韦东山手把手教你嵌入式Linux快速入门到精通 | Linux应用驱动开发基于I.MX6U](https://www.bilibili.com/video/BV1w4411B7a4/?)

![NXP](image/Screenshot%202024-02-23%20233044.png)
#### - [✅✅✅MYD-JX8MX 资源下载【米尔科技官方】(下面已贴)](http://down.myir-tech.com/MYD-JX8MX/)


### 个人进度

#### DarrenPig
- 1.29  ✅ubuntu 的镜像[ubuntu-22.04.3-desktop-amd64] VMware 安装, [shell环境学习](https://blog.csdn.net/cnds123/article/details/107427030)
- 1.30  ✅啃 yocto 的文档，本地部署[~/.bashrc-Linux环境变量](https://zhuanlan.zhihu.com/p/359354934)（Day 1）
- 1.31  ✅bitbake、[vim](https://www.runoob.com/linux/linux-vim.html)、poky（Day 2）
- 2.1   ✅[Yocto部署笔记](https://gitee.com/pai_666/euler-junior/blob/master/Files/1.31Ubuntu%E7%8E%AF%E5%A2%83%E5%8F%98%E9%87%8FShell%E3%80%81vim.pdf)、sig组会（Day 3）
- 2.3   ✅code、❌SSH到Ubuntu环境
- 2.4   ✅[报名表](https://gitee.com/openeuler/yocto-meta-openeuler/issues/I90DOU#comment-loadder)、Yocto文档到构建
- 2.5   ❌继续啃文档，✅在网上冲浪
- ......(春节)
- 2.21  ✅开始 imx8 的移植， 确认具体的开发板寄送地址和型号 ❌继续啃文档 
- 2.22  ✅收到单板，开始啃NXP的[imx 8 mini手册](https://www.nxp.com.cn/docs/en/data-sheet/IMX8MMIEC.pdf)❌ 开箱、找官方的Yocto虚拟机环境
- 2.23  ✅对MYD-JX8MP的快速开始手册（QSG），啃完了，通电、串口通信搞定 ❌
- 2.27  ✅啃完米尔科技给的板子附带的文档
- 2.28  ✅开始用Myr给的环境，构建Yocto

##### ✅目标：本周六`2.3`之前完成 Yocto 部署
##### ✅目标：本周三`2.21`之前完成 imx 8 软件包部署
![输入图片说明](image/imx%208%20%E6%96%87%E6%A1%A3.png)


##### -[🙂]  SSH隧穿VM上的Ubuntu的Shell会不会更方便一些？
##### -[🙂]  蹲2、3月份的南京MeetUP  
##### -[🙂]  WLS2的环境好用，还是VM里好用？
##### -[🙂]  imx资料要看吗？

##### -[👌]  文档是不是直接看官网就好？ 
##### -[👌]  用openSSH连接会不会好一些?
##### -[👌]  docker是啥概念？
##### -[👌]  3月中旬的南京MeetUp我啥时候去呢？


##### -[🫥]  在docker里编译树莓派？
##### -[🫥]  yocto的脚本使用？
##### -[🫥]  怎么拉内核代码？
##### -[🫥]  怎么打patch？


##### -[🫥]  yocto里集成一个第三方软件源码
##### -[🫥]  b站有个韦东山讲nxp的视频_我把链接附上面了

##### -[🙂]  开工了，开工了
##### -[🙂]  开学了，开学了
##### -[🫥]  周五，左右我会搞定本地环境的搭建


###  imx8（MYD-JX8MP）资料己经贴下面了【百度网盘(80G左右)】，部分文档已经上传本仓库和群


#### ✅大家可以在这补充...
![160-I](image/imx8puls.png)
---
#### imx 8 的文件
# MYD-JX8MX 资源下载 Resource Download

## 开发资源 Development Resource

| File      | Download Mirror                                              | Chinese                                                      | English                                                      |
| :-------- | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| MYD-JX8MX | [百度网盘(提取码:ea62)](https://pan.baidu.com/s/1Z5L-CvBNSx-O21GWYYXcKQ) | MYD-JX8MX 开发资源包                                         | MYD-JX8MX Development Package                                |
|           |                                                              | [MYC-JX8MX 产品数据手册](http://down.myir-tech.com/MYD-JX8MX/01-Document/User_Manual/Chinese/MYC-JX8MX-Product-Manual-zh-V1.0.pdf) | [MYC-JX8MX Product Manual](http://down.myir-tech.com/MYD-JX8MX/01-Document/User_Manual/English/MYC-JX8MX-Product-Manual-en-V1.0.pdf) |
|           |                                                              | [MYD-JX8MX 产品数据手册](http://down.myir-tech.com/MYD-JX8MX/01-Document/User_Manual/Chinese/MYD-JX8MX-Product-Manual-zh-V1.1.pdf) | [MYD-JX8MX Product Manual](http://down.myir-tech.com/MYD-JX8MX/01-Document/User_Manual/English/MYD-JX8MX-Product-Manual-en-V1.1.pdf) |
|           |                                                              | [MYD-JX8MX Linux开发手册](http://down.myir-tech.com/MYD-JX8MX/01-Document/User_Manual/Chinese/MYD-JX8MX-Software-Manual-zh-V1.2.pdf) | [MYD-JX8MX Linux Develop Guide](http://down.myir-tech.com/MYD-JX8MX/01-Document/User_Manual/English/MYD-JX8MX-Software-Manual-en-V1.2.pdf) |

## 开发文档 Development Document

| File          | Download Mirror                                              | Chinese                                  | English                                                      |
| :------------ | :----------------------------------------------------------- | :--------------------------------------- | :----------------------------------------------------------- |
| MYD-JX8MX文档 | [01-Document.zip](http://down.myir-tech.com/MYD-JX8MX/01-Document.zip) | MYD-JX8MX开发板和MYC-JX8MX核心板开发文档 | The MYD-JX8MX carrier board and MYC-JX8MX SoM development document |

## 应用笔记 Application Note【估计也是我们的任务】

| File | Download Mirror | Chinese | English |
| :--- | :-------------- | :------ | :------ |
|      |                 |         |         |
|      |                 |         |         |

### 系统镜像 System Binary Image 【这是我们的任务】

构建流程图
![构建说明](image/640%20(1).jfif)


---
## 最近活动：2.29
# 2.29SIG例会记录——>年后第一场

# 一、MICA

实时操作系统，多底座。统一接口的共享内存。
![MICA](image/My_Photor_1709207921475.jpg)

## 使用的方式：

#### MICA的相关的
![MIca](image/My_Photor_1709207957022.jpg)
sourse SDK
![sourse SDK](image/My_Photor_1709207992660.jpg)
cmake -S
![cd](image/My_Photor_1709208049542.jpg)
cd 

从QEMU角度选

SSH QEMU

### ifconfig eth0

ls

gs
![文档MICA](image/My_Photor_1709208092662.jpg)

文档MICA，使用QEMU部署、RTOS部署等

定义了一个函数
![定义了一个函数](image/My_Photor_1709208092662.jpg)
---

# 二、近期环节
![近期环节](image/My_Photor_1709208192579.jpg)
isula完善和问题修复：
（1）支持极简容器镜像，引入openeuler-container-os及资料
（2）1xc版本回退（修复启动问题），嵌入式保留isula极简运行时1xc，暂不升级runc，否则将会引入go语言，较为厚重2、MICA框架重构：
混合部署统一命令管理，为后续虚拟化底座做管理准备
3、重构和BSP完善： （1） 重构meta-hisilicon，兼容openeuler-image镜像 （2）支持hieulerpi（ss928/sd3403）：正式合入master，伙伴正在完善各项配套，3月底将在南京meetup正式发布 （3） 支持hi3093：支持直接在openeuler-image集成海思BSP生成emc部署镜像，同时支持不集成BSP驱动的镜像（可后续通过海思解决方案工程进一步打包）
![输入图片说明](image/My_Photor_1709208257418.jpg)
1.   新增登录打印： openEuler Embedded字符终端LOGO打印
2.   其他优化重构： openeuler_source重构，优化了构建使用ogeneuler_source列表时的构建空间占用openeuler-image配方重构，更加方便的配置镜像 不用手动配置OPENEULER_SRC_URI_REMOVE，当配方对应的仓库在manifest中存在时，会自动移除外部http、https、git源
3.   当前待修复关键问题： master编译器升级后，已知存在strip失败问题，导致镜像增大，近期即将修复其他问题见记录ISSUE

---
![发言：雪球计划签到](image/My_Photor_1709208222815.jpg)
#### 发言：雪球计划签到(只有我们到了)

NXP的看过之后，这些文件是在19年开发myd-jxmx_4.19.35时用到的文件。

---




# 三、要求项目跟进【周末我来看看】

### SDK资料\熟悉、了解、板子的内核迁移

NXP、大部分都在Linux_openEuler里有驱动

## 按设备树驱动移植

### 切换内核、驱动移植、验证、Debug

### Yocto引入BSP层，按树莓派、瑞星微，引入官方的层，代码欧拉化

## 驱动、引进  注意NXP里 的软件层

### 官方的资料的文档......欧拉的文档要相应的跟进

提交欧拉的板块、最小系统的拉起、官方地方特定工程

内核参考、如果内核成熟可以简略

##### 5月15日截至

---


### 社区的issue
![输入图片说明](image/My_Photor_1709208342271.jpg)
外部工具链 改为Poky localcast 文件

`TCMODE` = （外部构建）

Yocto 的`OPENEULER_PREBULIT_TOOLS_ENABLE` ="  "

原生的gcc 的cross

###### 关掉上述两个之后，就用Poky原件GCC 的方法

Qmake的进度，已经可以在构建SDK

![输入图片说明](image/My_Photor_1709208296574.jpg)

## [fork 主仓参考 提交PR上去]，NXP我们的进度，参考树莓派文档风格

---


2.1SIG组会
有关摘要：
......

###  **雪球计划 南向bsp**  支持范围（bsp-都有环境 —→ yocto）
Soc支持， **[米尔科技](https://www.myir-tech.com%2Fproduct%2Findex.asp%3Fanclassid%3D100)** 赞助：选择硬件板子 —→ issues统计Gitee ID
- → 可以传递）
-  **雪球计划 → 预计持续到5月** 
## 项目要求：
### - 合入  master  主线 —→ 代码
### - 基本镜像可以运行 —→ 硬件

- [ ] 版本，内核（不一定统一的要求下）—→ 先满足上述两个要求。

---
#维护信息

## 维护日志：2.1  @DarrenPig Readme、两份笔记(vim环境变量、2.1组会笔记)
## 维护日志：2.4  @DarrenPig Readme 报名信息
## 维护日志: 2.21 @DarrenPig Readme 开发板寄送信息，开工计划
## 维护日志: 2.22 @DarrenPig Readme 开发板开箱，更新imx8寄送收单上的文档
## 维护日志: 2.23 @DarrenPig Readme 开发板 韦山东imx6_NXP相关内容链接 3份PDF上传File
## 维护日志: 2.28 @DarrenPig Readme 个人进度、上传了IMX6、IMX8的文件到仓库里
## 维护日志: 3.3  @DarrenPig Readme 2.29年后例会的一些记录，关于要求和项目跟进之类的
✅ ✅ ❌

---

## P.S.:好玩的文档
社区文档（sphinx）怎么编译

```
sudo apt-get install python3-sphinx
pip3 install sphinx_rtd_theme sphinx_multiversion sphinx_tabs -i https://pypi.tuna.tsinghua.edu.cn/simple
```
装上sphinx环境，去拉社区文档仓（docs），就可以make html，生成文档了
> 1.30 @puai 社区文档的用法

## 24.03这个版本我们贡献扎实点，未来6年都这个版本！
> 1.30 @puai 大体进展是24.03开始

  @DarrenPig 记得3月中旬报名去南邮——MeetUp（imx8我尽量给点力）
> 2.21 @puai  @DarrenPig要开始做imx8了（imx6 被抢了）

###  @wei-app 看一下 NXP 的 单板附带的质量链接 
> 2.22 @DarrenPig 你要的贴上去了——资料共享那

###  今天研究一天，我明天在家也研究，下周一我们让李**给我们说说，看方向偏没有
> 2.23 @puai 这两天任务

### 今天维护一下Readme，现在openEuler Embedded 都是5.10版本了
> 2.27 @puai明天我们定个会。

###  [fork 主仓参考 提交PR上去]，NXP我们的进度，参考树莓派文档风格
> 2.29 @DarrenPig 组会要求我们，在主仓跟进一下进度的doc,划分了四步
