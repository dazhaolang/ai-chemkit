# ChemAgent 交互式安装演示

## 🎯 安装体验对比

### SuperClaude_Framework 风格的友好安装

我们的新安装程序提供了类似 SuperClaude_Framework 的用户体验：

```bash
$ python chemagent_install.py
```

将显示：

```
================================================== ChemAgent Installation ==================================================

╭─ 🚀 Getting Started ─────────────────────────────────────────────────────────────────────────────╮
│                                                                                                   │
│ Welcome to ChemAgent! 🧪                                                                         │
│                                                                                                   │
│ ChemAgent is a chemistry enhancement package for AI coding assistants,                           │
│ inspired by SuperClaude_Framework.                                                               │
│                                                                                                   │
│ This installer will help you set up ChemAgent for:                                              │
│ • Claude Code (Cursor) - Chemistry commands and sub-agents                                       │
│ • Gemini CLI - Chemistry tools and workflows                                                     │
│ • Custom configurations - Tailored to your needs                                                 │
│                                                                                                   │
╰───────────────────────────────────────────────────────────────────────────────────────────────────╯

Select Installation Mode:

┏━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃ # ┃ Mode                      ┃ Description                                            ┃
┡━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┩
│ 1 │ ✨ Quick Install          │ Full installation with all features (recommended)      │
│ 2 │ 🎯 Interactive Install    │ Choose specific components to install                  │
│ 3 │ 🚀 Minimal Install        │ Core features only, lightweight                        │
│ 4 │ 🔧 Developer Mode         │ Full features + development tools                      │
└───┴───────────────────────────┴────────────────────────────────────────────────────────┘

Choose installation mode [1-4] (1): 
```

## 📋 功能对比

| 功能 | 原始安装脚本 | 新交互式安装 | 说明 |
|------|------------|-------------|------|
| 用户界面 | 命令行参数 | 交互式菜单 | 更友好的选择方式 |
| 安装模式 | 单一模式 | 4种模式 | 满足不同用户需求 |
| 视觉效果 | 基础文本 | Rich UI | 彩色输出、表格、进度条 |
| 组件选择 | 全部安装 | 可选组件 | 灵活定制 |
| 错误处理 | 基础 | 友好提示 | 更好的错误恢复 |

## 🎨 交互式安装流程

### 1. 模式选择
- **Quick Install**: 一键安装所有功能
- **Interactive**: 逐步选择组件
- **Minimal**: 最小化安装
- **Developer**: 开发者工具包

### 2. 平台检测
```
✅ Detected platforms: Claude Code (Cursor), Gemini CLI
```

### 3. 组件选择（交互模式）
```
Select features to install:
Press Enter to select all

Install Chemistry commands (cc-analyze, cc-synthesize, etc.)? [Y/n]: y
Install Expert roles (@chemist, @drug-designer, etc.)? [Y/n]: y
Install Chemistry tools (RDKit, patent search, etc.)? [Y/n]: y
Install Pre-built workflows (drug discovery, materials)? [Y/n]: y
Install Example projects and templates? [Y/n]: y
```

### 4. 安装进度
```
⠋ Installing ChemAgent core...
⠋ Installing for claude-code...
⠋ Installing chemistry tools...
```

### 5. 完成消息
```
════════════════════════════════════ Installation Complete! ════════════════════════════════════

╭─────────────────────────────────────────────────────────────────────────────────────────────╮
│                                                                                             │
│ ✨ ChemAgent Successfully Installed!                                                       │
│                                                                                             │
│ Claude Code (Cursor) is ready!                                                             │
│ Gemini CLI is configured!                                                                  │
│                                                                                             │
│ 🚀 Quick Start:                                                                            │
│ 1. Open Cursor and try: cc-analyze aspirin                                                │
│ 2. Run: gemini "analyze caffeine molecule"                                                 │
│ 3. Create custom commands in .claude/commands/                                             │
│ 4. Define new roles in .claude/roles/                                                      │
│                                                                                             │
│ 📚 Resources:                                                                              │
│ • Documentation: https://chemagent.ai/docs                                                 │
│ • Examples: Run chemagent examples                                                         │
│ • Help: Use cc-help in your AI assistant                                                  │
│                                                                                             │
│ 💡 Tips:                                                                                   │
│ • Install additional tools: chemagent install --tools                                      │
│ • Update ChemAgent: chemagent update                                                       │
│ • Join community: https://github.com/chemagent                                             │
│                                                                                             │
│ Happy Chemistry! 🧪✨                                                                      │
│                                                                                             │
╰─────────────────────────────────────────────────────────────────────────────────────────────╯
```

## 🛠️ 其他命令演示

### 查看状态
```bash
$ chemagent status

🔍 ChemAgent Installation Status

✅ ChemAgent 0.1.0 is installed
✅ Claude Code (Cursor) integration found
✅ 10 commands available
✅ 6 roles available

Run 'chemagent install' to fix any issues.
```

### 安装示例
```bash
$ chemagent examples

📚 Installing ChemAgent Examples...

✅ Examples installed in chemagent_examples

Try copying these to:
  • .claude/commands/ for commands
  • .claude/roles/ for roles
```

## 🎯 设计理念

1. **用户友好**: 清晰的选项和说明
2. **视觉吸引**: 使用 emoji 和格式化输出
3. **灵活选择**: 多种安装模式
4. **错误友好**: 优雅的错误处理
5. **快速上手**: 安装后立即提供使用示例

这种安装体验让用户感觉专业且易用，大大降低了使用门槛！
