# STC51 两层最小系统板

这是我学习 51 单片机、原理图设计和两层 PCB 布局布线时完成的练习项目。

> 项目参考了 B 站课程；原理图、PCB 布局布线和文件整理由我完成。
> 当前版本为学习设计版本，尚未完成实物打样与功能验证。

## 功能

- USB-C 5V 供电
- STC89C51/52 单片机最小系统
- 晶振和复位电路
- 串口下载接口
- 两个按键
- 两个 LED
- P0 口上拉电阻
- I/O 扩展排针

## 设计文件

- [完整嘉立创EDA工程](hardware/source/)
- [BOM 物料清单](hardware/bom/)
- [Gerber 制板文件](hardware/gerber/)
- [原理图与 PCB 图片](docs/)

## PCB 预览

![原理图](docs/schematic.png)

![PCB 顶层](docs/pcb-top.png)

![PCB 底层](docs/pcb-bottom.png)

## 当前状态

- [x] 原理图设计
- [x] PCB 布局与布线
- [x] ERC/DRC 检查
- [x] 导出 Gerber 和 BOM
- [ ] PCB 打样
- [ ] 焊接与功能验证

## 已知问题与后续计划

- 当前尚未打样；实际功能仍需验证。
- USB-C 接口仅用于供电，不用于 USB 数据传输。
- 后续将完成 LED、按键和串口通信测试程序，并进行打样验证。
-详细学习和调试记录见：[learning-notes.md](docs/learning-notes.md)

## 参考来源

- B 站课程名称：【教程】零基础入门PCB设计-国一学长带你学嘉立创EDA专业版 全程保姆级教学 中文字幕（大师篇已更新）
- 视频链接：https://www.bilibili.com/video/BV1At421h7Ui/?spm_id_from=333.337.search-card.all.click&vd_source=c7618707386c69fa0df5d9c3ac5db7d7