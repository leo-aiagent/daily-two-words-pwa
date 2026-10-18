# 每天两个词 · v1.3.0

家庭英语静态 PWA，React + TypeScript + Vite + IndexedDB。正式安装地址：https://leo-aiagent.github.io/daily-two-words-pwa/

本机口语识别：首次在口语关下载约 40 MB 英文包，此后无需联网语音服务；声音留在设备上。识别匹配正确后继续 A–Z 拼写，两个词均完成后孩子自行打卡。无需账号、PIN、云数据库或持续运行的业务后台。

本仓库仅包含编译后的公开静态文件、词库、音频和开源识别资源，不包含家庭学习记录。手机之间不会自动同步，请自行导出 JSON 备份。

Vosk / 模型 Apache-2.0，许可在 asr/LICENSE.txt、asr/NOTICE.txt；识别词表 CC-BY-SA-4.0，来源与完整署名在 asr/recognition-vocabulary.json 和 asr/wordfreq-NOTICE.txt。语音合成音频为 Kokoro-82M af_heart，Apache-2.0。

GitHub Pages 从 main 根目录直接提供文件。已有用户通过 App 更新提示更新，保留同一域名和路径以保持本机数据。请勿清除网站数据来更新。
