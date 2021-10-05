---
id: UZnRsu5WMjM8LX47cDh07
title: 安装
desc: ''
updated: 1633421939123
created: 1633421392435
---

## 安装

> 以下针对国内用户

导出rust国内镜像源

```shell
echo "export RUSTUP_DIST_SERVER=https://mirrors.sjtug.sjtu.edu.cn/rust-static" >> ~/.bashrc

echo "export RUSTUP_UPDATE_ROOT=https://mirrors.sjtug.sjtu.edu.cn/rust-static/rustup" >> ~/.bashrc
source ~/.bashrc
```

![](/assets/images/2021-10-05-16-13-55.png)

```shell
curl https://sh.rustup.rs -sSf | sh
```

![](/assets/images/2021-10-05-16-15-18.png)

添加到环境变量

source $HOME/.cargo/env

查看.bash_profile

![](/assets/images/2021-10-05-16-17-18.png)

验证是否安装成功

```shell
rustc --version
cargo --version
rustup --version
```
