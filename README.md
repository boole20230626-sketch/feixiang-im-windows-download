# 飞享 IM Windows 下载页

本公开仓库用于飞享 IM Windows ZIP 的 HTTPS 下载页和 Release 资产分发。

- 不包含客户端源码
- 不包含证书、密钥、后端凭据或账号资料
- 当前包：0.1.0 P11 20260714-33750f3d
- 当前包连接飞享服务环境，生产配置门禁仍由客户端仓库记录
- 当前 Windows 包未代码签名，下载页必须保留未知发布者和 SmartScreen 风险提示
- 最新包包含 `install.cmd`、`uninstall.cmd` 和安装说明；安装器会关闭旧进程并替换旧快捷方式；ZIP/EXE/DLL 不提交到本仓库，只通过 GitHub Release 资产分发

