# proj297-LoongArch-porting---NXOS-kernel
# 开源操作系统的LoongArch移植-NXOS内核

## 项目描述
NXOS是一个开源操作系统内核，由BookOS操作系统社区开发。本项目需要参赛选手将NXOS移植到由龙芯自主研发的LoongArch架构上运行，最终实现运行用户态shell程序，并加载执行交互命令。

## 预期目标
- 阅读理解目标系统和LoongArch架构特性，实现LoongArch架构支持。
- 搭建LoongArch交叉编译环境，编译目标系统，并在QEMU模拟器上完成功能调试，形成移植和测试文档。

## 特征
- NXOS是一个支持多核，多进程，多线程，虚拟内存管理，文件系统，网络的操作系统，可以学习一个基础操作系统的实现。
- NXOS支持用户态驱动和服务，可以作为微内核，将文件系统，驱动等模块化独立组件运行在用户态。
- NXOS支持虚拟化扩展，将NXOS作为一个Type-I型的虚拟机管理器运行，可以在上面运行linux这类客户机操作系统。
- NXOS拥有自己的编程API，类似于Win32 API。
- NXOS由BookOS社区维护，有社区文档以及比赛交流群，可以为学生答疑。
- 支持各种硬件
  - 基于目前量产的处理器和开发板：
    - D1/D1s哪吒开发板（基于平头哥C906 RV64 CPU）
    - K210开发板（基于K210处理器 RV64 CPU）
    - SiFive Unmatch开发板（基于U740/U540 RV64 CPU）
    - 树莓派4B开发板（基于AARCH64处理器）
  - 基于QEMU模拟器的处理器：
    - QEMU X86模拟器
    - QEMU RISCV64模拟器
    - QEMU AARCH64模拟器

## 参考资料
- xv6/ucore for loongarch
- 关于LoongArch架构的工具链及文档：https://github.com/loongson
- QEMU模拟环境，可以在PC上模拟运行LoongArch架构的操作系统：https://github.com/yangxiaojuan-loongson/qemu/blob/tcg-dev/target/loongarch/README
- BookOS开源代码：https://gitee.com/BookOS/BookOS
- NXOS开源代码：https://gitee.com/BookOS/nxos

## 赛题分类
内核移植

## 参赛要求
- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
- 允许学生参加大赛的多个不同题目，最终自己选择一个题目参与评奖
- 请遵循“2024全国大学生操作系统比赛”的章程和技术方案要求

## 难度
高等

## License
Apache 2.0 License

## 所属赛道
2024全国大学生操作系统比赛的“OS功能挑战”赛道

## 项目导师

- 姓名：胡自成
- 单位：BookOS开源社区
- github ID： https://github.com/hzcx998
- Gitee ID： https://github.com/hzc1998
- email： 2323168280@qq.com
