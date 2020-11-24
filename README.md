# Linux Shell Scripts

一些 Linux 脚本

```sh
$ tree
├── shell
│   └── kcptun.sh # kcptun 一键安装脚本
|   └── ss-go.sh # shadowsocks 一键安装脚本
```

## Kcptun 一键安装脚本

* 安装命令：

```sh
wget --no-check-certificate https://github.com/ggggxiaolong/shell-scripts/raw/master/shell/kcptun.sh
sh kcptun.sh
```

* 帮助信息

```sh
# sh kcptun.sh help
请使用: kcptun.sh <option>

可使用的参数 <option> 包括:

    install          安装
    uninstall        卸载
    update           检查更新
    manual           自定义 Kcptun 版本安装
    help             查看脚本使用说明
    reconfig <id>    重新配置实例
    show <id>        显示实例详细配置
```

只能安装一个实例，通过systemd配置开机启动
