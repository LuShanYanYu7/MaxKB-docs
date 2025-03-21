## mkctl 命令

!!! Abstract ""

    MG 离线安装包默认内置了命令行运维工具 mkctl，通过执行 `mkctl help`，可以查看相关的命令说明。

!!! Abstract ""

    **说明**：

    - 1.5.0 之前版本请使用 kbctl 命令。
    - 通过在线安装、1Panel方式安装，并没有内置 mkctl 命令。

    ```
    Usage:
    mkctl [COMMAND] [ARGS...]
    mkctl --help

    Commands:
    status              查看 MG 服务运行状态
    start               启动 MG 服务
    stop                停止 MG 服务
    restart             重启 MG 服务
    reload              重新加载 MG 服务
    uninstall           卸载 MG 服务
    upgrade             升级 MG 服务
    version             查看 MG 版本信息
    clean-images        清理 MG 旧版本的相关镜像
    ```
