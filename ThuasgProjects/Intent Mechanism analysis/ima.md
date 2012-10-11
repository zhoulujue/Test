# 对Intent通讯机制的初步学习和分析

---
## 0. Before we get started, 写在前面
分析Intent的通讯其实是为了分析Android平台IPC机制。
进程间的通讯-IPC(Inter-process Communication)可以利用传统的类UNIX的机制，例如文件系统(filesystem)，本地Sockets(本地Sockets)