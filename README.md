# GPU-J

Software for real-time monitoring of GPU status and GPU ECC errors.

# Windows 用户
直接下载 **Windows_GPU-J.Setup.0.0.1.exe**  安装即可使用

# Linux用户
## 1️⃣ .deb 安装包
输入命令安装：
```bash
$ sudo dpkg -i Linux_gpuj_0.0.1_amd64.deb
```
然后在桌面环境上找到 **GPU-J** 软件双击点开即可运行
卸载软件：
```bash
$ sudo apt remove gpuj
```

## 2️⃣ .AppImage 便携包
打开终端
输入命令，增加可执行权限：
```bash
$ chmod +x Linux_GPU-J-0.0.1.AppImage
```

输入命令，直接运行：
```bash
$ ./Linux_GPU-J-0.0.1.AppImage
```

# 从源码开始构建

## Project Setup

### Install

```bash
$ npm install
```

### Development

```bash
$ npm run dev
```

### Build

```bash
# For windows
$ npm run build:win

# For macOS
$ npm run build:mac

# For Linux
$ npm run build:linux
```

