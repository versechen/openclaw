# install

### 源码安装

[index.md](install/index.md "mention")

前提：

```shellscript
pnpm setup

```

配置：

\~/.openclaw/openclaw.json

```json
 "models": {
    "providers": {
      "myclaude": {
        "baseUrl": "https://yxai.anthropic.edu.pl",
        "apiKey": "sk-6rkFchh2wXKRvp9XbCEoTtWdh7MCU3V9O67oKOvSMD7pzVRV",
        "models": [
          {
            "id": "claude-opus-4-6",
            "name": "Claude Opus 4.6",
            "api": "anthropic-messages"
          }
        ]
      }
    }
  },
  "agents": {
    "defaults": {
      "model": {
        "primary": "myclaude/claude-opus-4-6"
      }
    }
```
