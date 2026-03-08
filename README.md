# OpenClaw Skills

OpenClaw 技能仓库 - 精选 AI Agent 技能集合

## 📦 技能来源

- **ClawHub 备份**：`skills/` 目录下的技能来自 https://clawhub.com
- **社区精选**：根目录下的技能来自社区贡献和精选

## 🎨 新增技能（2026-03-08）

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
学习这个技能：https://github.com/moxunjinmu/openclaw-skills/tree/main/video-generation
```

### 方式 2：手动安装

```bash
# 克隆仓库
git clone https://github.com/moxunjinmu/openclaw-skills.git

# 复制需要的技能
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
- 社区精选技能：MIT License（除非另有说明）

---

**最后更新**：2026-03-08  
**维护者**：莫循团队
