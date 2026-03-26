# 基于 STM32 和 AD9851 的 DDS 信号源硬件设计

## 项目简介
- 输出频率：0-70MHz，步进 1Hz
- 主控芯片：STM32F103C8T6
- DDS 芯片：AD9851
- PCB：四层板（信号-地-电源-信号）

## 项目状态
✅ 原理图设计完成  
<img width="1659" height="1164" alt="image" src="https://github.com/user-attachments/assets/58793086-ad56-4f8a-94b3-948b6afecad7" />

✅ PCB 布局规划完成  
<img width="1536" height="1097" alt="image" src="https://github.com/user-attachments/assets/119b761b-6fd0-4047-a3fa-225f2673a8fc" />

🔄 布线中

## 文件说明
- `/Schematic` - 原理图源文件及 PDF
- `/PCB` - PCB 布局文件
- `/BOM` - 物料清单

## 设计要点
- 30MHz 参考时钟采用包地处理
- 模拟/数字分区供电，单点接地
- 四层板层叠：信号-地-电源-信号

## 博客链接
[[CSDN 技术博客]((https://blog.csdn.net/2501_92470428/article/details/159512470?fromshare=blogdetail&sharetype=blogdetail&sharerId=159512470&sharerefer=PC&sharesource=2501_92470428&sharefrom=from_link))](https://blog.csdn.net/2501_92470428/article/details/159512470?fromshare=blogdetail&sharetype=blogdetail&sharerId=159512470&sharerefer=PC&sharesource=2501_92470428&sharefrom=from_link)
