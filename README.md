# v2ray.fun 
术业有专攻，一部分人一辈子都不会搞懂这些网络，但是他们仍然有权利自由地访问互联网，懂技术的人不一定可以通过技术改变世界。

欢迎加入[telegram讨论群](https://t.me/vimchina)，欢迎你的任何建议，需求以及求助。

<!-- vim-markdown-toc GFM -->

[toc]

<!-- vim-markdown-toc -->

# V2ray.fun

V2ray控制脚本，向导式更改端口，加密方式，传输协议，享受 V2ray 的乐趣~


## 功能

- 一键 启动 / 停止 / 重启 V2ray 服务端
- 自动随机生成 UUID
- 自助修改端口
- 快速查看服务器连接信息
- 一键下载客户端配置文件和**二维码**（通过 sz rz ，xshell，secureCRT 还有 [macOS 的 iTerm2](https://github.com/tracyone/v2ray.fun/wiki/MAC使用RZ、SZ远程上传下载文件都支持) 都支持）
- 自由更改**传输配置**：
  - 常规 TCP
  - HTTP 头部伪装
  - WebSocket 流量
  - 常规 mKCP 流量
  - mKCP 伪装 FaceTime 通话流量
  - mKCP 伪装 BT 下载流量
  - mKCP 伪装 微信视频通话流量

**WebSocket 不包括 Nginx 分流，请自行安装 Nginx 来分流。**

## 安装命令

```bash
bash -c "$(curl -fsSL https://git.io/vpOeN)"
```

## 升级命令
```bash
bash -c "$(curl -fsSL https://git.io/vpOex)"
```

## 卸载命令
```bash
bash -c "$(curl -fsSL https://git.io/vpOep)"
```


## 截图

![1](1.png)

![2](2.png)

![3](3.png)

![4](4.png)

## 系统要求

- Debian 7 
- **Debian 8（推荐）**
- Ubuntu 14 
- Ubuntu 16 
- CentOS 7

## 特别说明

也可以先查看下本仓库的[wiki](https://github.com/tracyone/v2ray.fun/wiki)

本程序遵循 [GPLv3](http://gnu.org/licenses/gpl-3.0.zh-cn.html) 协议发布，请 Fork 保留源项目地址，谢谢！

V2ray : https://v2ray.com

原作者: [雨落无声](https://github.com/YLWS-4617)

# Buy me a coffee

![donation](https://cloud.githubusercontent.com/assets/4246425/24827592/553bc732-1c7f-11e7-8207-284cccbc2e5c.jpg)
