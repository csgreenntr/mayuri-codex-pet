# 嘟嘟噜～真由理独立桌宠 v2.0.0

安装并开启 dsh-mayuri-pet 即可使用，无需安装或开启 dsh-pet。独立插件自带桌面窗口、播放、右键菜单和 DSH 任务状态联动。

[下载完整 ZIP](https://github.com/csgreenntr/mayuri-codex-pet/releases/download/dsh-v2.0.0/mayuri-dsh-independent-v2.0.0.zip) · [下载 TGZ](https://github.com/csgreenntr/mayuri-codex-pet/releases/download/dsh-v2.0.0/dsh-mayuri-pet-2.0.0.tgz) · [校验值](https://github.com/csgreenntr/mayuri-codex-pet/releases/download/dsh-v2.0.0/SHA256SUMS-dsh-v2.0.0.txt)

## 安装

在 DSH 插件页从本地文件安装 dsh-mayuri-pet-2.0.0.tgz，启用真由理。原 dsh-pet 可以保持关闭。首次缺少 Electron 时会下载运行时。

## 功能

- 24 个透明动画；15 个待机动作随机选择，动作结束站定 4～8 秒。
- 左键打招呼，连续点击还有跳跃、比心等动作；右键手动选动作、查看余额、对话、重载；大小在 DSH 的真由理设置页调整。
- 跟随 DSH 任务思考、工作、等待、完成。
- 真由理配置、记忆、窗口缓存与原插件隔离，可同时使用两者。

## 升级与配置

首次启动从旧版真由理配置（包括停用配置）复制现有设置，保留大小、位置和自定义动作池。独立配置为 $DSH_HOME/dsh-mayuri-pet/main-config.jsonc；后续不会重新覆盖。旧版设置保留，已识别的旧形象配置从原引擎发现目录收回以防重复显示。原插件自己的主配置不会更改。

独立命令：/mayuri、/mayuri-chat、/mayuri-balance。

余额支持范围保持原状，workbuddy-global 暂不支持。

这是在 DSH 中独立启用的插件；关闭 DSH 后也会退出。角色和第三方代码说明见 NOTICE.md 和 THIRD-PARTY-LICENSES.md。

已在 Windows DSH Desktop 0.2.1-rc.2 验证。其他版本尚未实测。完整代码与素材见发行版 TGZ。
