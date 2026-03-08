# OpenClaw Skills

OpenClaw 技能仓库 - 精选 AI Agent 技能集合

## 📦 技能来源

- **ClawHub 备份**：`skills/` 目录下的技能来自 https://clawhub.com（3900+ 技能）
- **wulaosiji 社区技能**：`wulaosiji-skills/` 目录下的技能来自 https://github.com/wulaosiji/skills（49 个精选技能）
- **快速访问**：根目录下的技能是从 wulaosiji-skills 中精选的常用技能

## 🎯 wulaosiji-skills 技能集（49个）

完整技能列表请查看 [wulaosiji-skills/](wulaosiji-skills/) 目录，包含：

### 🔵 飞书生态（15个）
- feishu-doc-orchestrator, feishu-wiki-orchestrator, feishu-chat-extractor, feishu-chat-monitor, feishu-pdf-downloader, feishu-doc-perm, feishu-voice-sender, feishu-video-sender, feishu-card-parser, feishu-group-welcome, feishu-message-recall, feishu-doc-converter, feishu-doc-creator, feishu-doc, feishu-bitable-field

### 🎨 内容生成（10个）
- video-generation, zhuoran-selfie, zhuoran-video-selfie, qizhuo-selfie, clawra-selfie, clawra-video-selfie, baoyu-slide-deck, long-form-writer, infographic-generator, md-to-wechat

### 📊 数据处理（8个）
- document-hub, pdf, image-ocr, content-extractor, wechat-article-fetcher, twitter-scraper, rss-feed, logic-validator

### 🛠️ 开发工具（5个）
- gh-cli, remotion-best-practices, calendar, find-skills, smart-shopping

### 🔗 外部集成（6个）
- bright-data, amap-navigator, media_hub, whisper-stt, voice-clone, rss-feed

### 🤖 AI Agent（5个）
- security-hardening, skill-security-audit, secure-key-manager, security-drill, logic-validator

## 🎨 快速访问（根目录精选）

### 媒体生成与处理

| 技能 | 说明 | 来源 |
|------|------|------|
| [video-generation](video-generation/) | 视频生成和超分（WaveSpeed AI） | wulaosiji/skills |
| [infographic-generator](infographic-generator/) | 信息大图生成（坐标蓝图风格） | wulaosiji/skills |
| [baoyu-slide-deck](baoyu-slide-deck/) | 幻灯片自动生成 | wulaosiji/skills |

### 音频处理

| 技能 | 说明 | 来源 |
|------|------|------|
| [voice-clone](voice-clone/) | 声音克隆和语音生成 | wulaosiji/skills |
| [whisper-stt](whisper-stt/) | 本地语音转文字 | wulaosiji/skills |
| [media_hub](media_hub/) | 音视频处理中心 | wulaosiji/skills |

### 图像处理

| 技能 | 说明 | 来源 |
|------|------|------|
| [image-ocr](image-ocr/) | 图片文字识别 | wulaosiji/skills |

## 🚀 使用方式

### 方式 1：直接告诉 OpenClaw

```
学习这个技能：https://github.com/moxunjinmu/openclaw-skills/tree/main/wulaosiji-skills/video-generation
```

或使用快速访问：
```
学习这个技能：https://github.com/moxunjinmu/openclaw-skills/tree/main/video-generation
```

### 方式 2：手动安装

```bash
# 克隆仓库
git clone https://github.com/moxunjinmu/openclaw-skills.git

# 复制需要的技能（从 wulaosiji-skills 目录）
cp -r openclaw-skills/wulaosiji-skills/video-generation ~/.agents/skills/

# 或使用快速访问
cp -r openclaw-skills/video-generation ~/.agents/skills/

# 验证安装
ls ~/.agents/skills/video-generation/
```

## 📚 技能详情

每个技能目录包含：
- `SKILL.md`：技能说明文档
- `scripts/`：可执行脚本（可选）
- `templates/`：模板文件（可选）

## 🤝 贡献

欢迎提交 PR 添加新技能或改进现有技能。

## 📄 许可证

- ClawHub 备份技能：遵循原始许可证
- wulaosiji-skills：MIT License（来源：https://github.com/wulaosiji/skills）
- 快速访问技能：MIT License

---

**最后更新**：2026-03-08  
**维护者**：莫循团队  
**技能总数**：3900+ (ClawHub) + 49 (wulaosiji-skills)
