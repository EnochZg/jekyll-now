---
layout: post
title: VirtualBox共享文件夹（Linux console）
---

### 增强功能安装
- 在`VirtualBox`菜单`设备`点击`安装增强功能...`

```bash
sudo mount /dev/cdrom/ /mnt/
sudo apt-get install build-essential module-assistant
sudo /mnt/VBoxLinuxAdditions.run
```

### 共享文件夹

```bash
sudo mount -t vboxsf html /var/www/html/
```