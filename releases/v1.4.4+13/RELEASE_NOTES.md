# 修仙问道 1.4.4+13

Android、iOS、macOS、Windows 统一版本 **1.4.4+13**。

## 本次更新

- 适配新仙界服务器，支持验证并延续原账号登录状态。
- 减少仙市、药园、宗门等页面的重复自动读取，降低长时间在线时的数据传输。
- 洞府首页复用近期宗门简介，修为变化不再反复拉取完整宗门资料；离开首页后停止简介读取。
- 改善网络连接复用，减少频繁重新建立连接带来的等待。
- 药材生长倒计时持续更新，成熟到点及时核对；购买、播种、领奖和手动刷新仍立即同步。
- 钱包同步不再重复刷新整个页面，输入价格或数量时保持焦点与文字。
- 迁服时保留原待确认操作编号，重新核对身份后继续处理，避免重复提交。

## 下载与安装

| 设备 | 安装文件 | 要求与说明 |
| --- | --- | --- |
| Android | `xiuxian-wendao-1.4.4+13-android-arm64.apk` | Android 7.0+、ARM64；沿用原签名，可覆盖更新 |
| iPhone / iPad | `xiuxian-wendao-1.4.4+13-ios-unsigned.ipa` | iOS 15+；安装前需重新签名 |
| Mac | `xiuxian-wendao-1.4.4+13-macos-universal.dmg` | macOS 12+；Intel / Apple Silicon 通用，另提供同版本 ZIP |
| Windows | `xiuxian-wendao-1.4.4+13-windows-x64-portable.zip` | Windows 10 1809+ / Windows 11、x64；完整解压后运行 |

Mac 先退出旧版，再将新版拖入“应用程序”覆盖安装；当前未公证。Windows 完整解压便携包后运行 `xiuxian_wendao.exe`，保留全部 DLL 和 data 目录；当前未配置代码签名。

更新前请退出旧版。使用原修仙账号登录，云端角色与进度由仙界保存；服务迁移期间请等待新仙界开放。`SHA256SUMS.txt` 可用于核对安装包完整性。
