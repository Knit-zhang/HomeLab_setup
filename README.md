## 前言

最近入手了一台 N6000 机器，试着折腾了下 [AllinOne](#前言 "AllinBoom"), 乘此机会，记录下折腾过程

## 硬件配置

|项目|配置|
|:---|:--:|
|cpu|N6000|
|内存|24GB|
|ssd|512GB nvme|
|hhd|2TB(临时)|

## 软件搭建

主系统使用 [`pve`](https://pve.proxmox.com/) 搭建两个虚拟机+一个lxc
使用lxc容器搭建docker服务器,同时将核显直通给lxc用于jellyfin解码
两台虚拟机一台搭建openwrt,一台搭建truenas scale(体验zfs+k3s)

## 具体折腾后续更新
