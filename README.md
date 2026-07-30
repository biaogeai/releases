# Releases

软件分发仓库，存放各软件的更新配置和客服信息。

## 软件列表

### Smart助手
- 最新版本：2.0.0
- 更新日志：见 `smart-assistant/update.json`

## 结构说明

```
releases/
├── smart-assistant/
│   └── update.json        # 版本信息、下载链接、更新日志
├── another-tool/
│   └── update.json        # 其他软件的更新配置
└── README.md
```

## 使用方式

各软件通过读取对应的 `update.json` 文件来检查更新。
