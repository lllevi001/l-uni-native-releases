# 安卓离线打包工具 Releases

此仓库仅用于公开发布 Windows x64 工具更新安装包、版本说明和 SHA-256 校验文件。应用源码保存在独立的私有仓库中，本仓库不接收功能代码。

## 下载

打开 [最新版本](https://github.com/lllevi001/l-uni-native-releases/releases/latest)，下载 `l-uni-packager_<版本>_x64-setup.exe`。

此安装器用于更新已经安装的离线打包环境。首次使用需要先取得完整离线环境包。安装时选择已有工具目录；本机应用配置、证书、SDK、工具链与缓存保留。更新直接覆盖工具文件，不备份、不回滚。

工具内也可点击「检查更新」，下载校验通过后选择「退出并安装」。

每个 Release 提供：

- Windows x64 更新安装器；
- `SHA256SUMS.txt`：安装器 SHA-256；
- `latest.json`：GitHub 匿名接口限流时使用的备用版本信息。

不在此仓库发布 AppKey、证书私钥、密码、业务配置或完整离线环境。