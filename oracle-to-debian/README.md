

#### 几个情况需要重装系统

- 我的 VPS 装了一堆东西，很乱，想还原
-  我的 VPS 之前东西和现在要装的东西冲突了。无法进行安装了
-  我的 VPS 被人侵入当矿机了，机器满负荷运载
-  想尝试 bbr 其他版本，ARM 目前还是会失联
-  更纯净更稳定

#### 最关键是甲骨文云你删机不一定能开出新机！所以重装系统很重要！

- 甲骨文云 ARM 或者 AMD 架构，Ubuntu 系统
- 几分钟内 dd 成 debian 或者 ubuntu
- 群友分享的，他经常用。我也成功重装了！

#### 一键脚本

```sh
bash <(wget --no-check-certificate -qO- 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh') -d 10 -v 64 -a -firmware -p 12345
```

#### 系统参数

- **-d 10** 【7、8、9、10】Debia
- **-u 20.04** 【14.04、16.04、18.04、20.04】Ubuntu

#### 密码参数，可以改成别的

- -p 12345
- 刚开始，都是自动的等

#### 重装后 3 分钟 VPS 自动重启
