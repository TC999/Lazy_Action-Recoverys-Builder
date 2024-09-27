# 懒全自动 rec 编译器 | TWRP / PBRP / OFRP / SHRP |
通过 Github Actions 编译您的第一个自定义 rec - 带有 ldcheck 设置。

## 如何使用
1. 复制此仓库。

2. 前往 `Action` 标签 > `All workflows` > 选择您需要的构建 (`TWRP 或 PBRP 或 OFRP 或 SHRP`) > `Run workflow`，然后从每个下拉列表中选择所需信息：
 - 清单分支 (*12.1, *11.0, *10.0, *9.0, *8.1, *7.1, *6.0 等)
 - 设备树 (您的设备树仓库链接)
 - 设备树分支 (您的设备树仓库分支)
 - 构建目标 (boot, reecovery, vendorboot)
 - LDCHECK (您目标二进制文件的路径，例如 `system/bin/qseecomd`)
   - 如果您正在手动/本地构建，并且您想使用 ldcheck 来检查依赖项，请访问 [THIS](https://github.com/TeamWin/android_device_qcom_twrp-common/tree/android-11#using-ldcheck-to-find-dependencies) 这个指南。

## 感谢/致谢
 - [CaptainThrowback](https://github.com/CaptainThrowback) 
 - [azwhikaru](https://github.com/azwhikaru) 
 - [cd-Crypton](https://github.com/cd-Crypton) 
 - [that1](https://github.com/that1) 
 - [carlodandan](https://github.com/carlodandan) 
 - 以及我在每个仓库和脚本中使用的所有贡献者。
