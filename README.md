# GPU-J

Software for real-time monitoring of GPU status and GPU ECC errors.


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

1️⃣ .deb 安装包
输入命令安装：sudo dpkg -i Linux_gpuj_0.0.1_amd64.deb
然后在桌面环境上找到“GPU-J”双击点开即可运行
卸载：sudo apt remove gpuj
2️⃣ .AppImage 便携包
打开终端
输入命令，增加可执行权限：chmod +x Linux_GPU-J-0.0.1.AppImage
输入命令，直接运行：./Linux_GPU-J-0.0.1.AppImage
