---
sidebar_position: 1
sidebar_label: 准备工作
title: 准备工作
---

## 开发准备

### 供电

**aicore-bm1684x 核心板支持 12V 输入，而整机fogwise bm168m支持20V输入。**

### 存储

系统镜像存储在板载的emmc中。

### 网络连接

aicore-bm1684x有两个有以太网口，可以通过以太网接入网络

### 调试串口
使用usb type-a转type-c数据线插入整机的debug口，TTL电平，波特率 115200，8 比特数据，1 比特停止位，无奇偶校验，无硬件流控。
debug口可在[Fogwise BM168M硬件信息下的硬件接口说明](../../bm168m/hardware-design/hardware-interface.md)找到位置示意图


## 常见问题

## 注意事项

关机时建议使用 sudo poweroff 命令，尽量避免直接断电，以免文件系统损坏。

## 参考文档
