> 本文由 AI 从历史协作对话中自动提炼 · 来源：旧电脑迁移数据包

# GitHub 主页美化

## 目标

把 `Robin-fang611` 的 GitHub 主页从空白状态做成一个有品牌感、能吸引同路人的个人展示页，核心目标优先级：创造个人影响力 > 寻找创业伙伴 > 吸引招聘方。

## 做了什么

### 定位与策略

- **人设定位**：「非技术背景的 AI-native Builder」——不会手写代码、全用 AI 做产品，在 GitHub 上是非常稀缺且有记忆点的标签。
- **语言**：中英双语（Robin 自己的说法是"双鱼"即双语）。
- **设计风格**：方案 B（个人品牌页），不用数据卡片（因为 AI 辅助开发会导致 GitHub 统计数字不好看，反而削弱人设），不用 badge 堆砌。

### 页面结构（三段式叙事）

```
━━━ ① 头部：你是谁 ━━━
一句话人设 + 社交矩阵

━━━ ② 中部：你做了什么 ━━━
3 个项目，每个配一个 Mermaid 流程图，
展示"想法 → AI 辅助 → 产品上线"的完整叙事

━━━ ③ 尾部：来聊聊 ━━━
微信 + 合作邀请
```

### 用到的技巧

| 技巧 | 说明 |
|------|------|
| **Profile README 仓库** | 创建 `用户名/用户名` 仓库，GitHub 会自动将其 README 显示在个人主页顶部 |
| **Mermaid 流程图** | 在 Markdown 中用代码块渲染流程图，展示每个项目的"想法→AI→产品"工作流 |
| **Emoji 社交链接栏** | 用 Emoji + 链接的形式展示全平台社交账号（B站、小红书、抖音、X），不用图标 badge |
| **放弃 Stats 卡片** | 有意识地不放 `github-readme-stats`，因为 AI 辅助开发的 commit/PR/star 数量不高，反而起反作用 |
| **第一人称叙事语气** | 不写技术细节，而是用讲故事的方式介绍每个项目（"遇到了什么问题→怎么用 AI 解决的"） |

### 精选的三个项目

1. **wuhan-food-map**（武汉美食地图）— 有具体用户场景
2. **fde-project-evolution**（FDE 工具包）— 行业向
3. **freightcrew-email-workspace**（货代邮件工作台）— 实际业务

每个项目配一个 Mermaid 工作流图，例如武汉美食地图的流程图逻辑：

```
[大一新生不知道吃什么] → [告诉AI想要美食地图]
→ [Cursor + 高德API] → [50+周边店 + 540+全城店] → [上线分享给同学]
```

## 最终产出

### 涉及信息

| 项目 | 内容 |
|------|------|
| **GitHub 用户名** | `Robin-fang611` |
| **主页地址** | [github.com/Robin-fang611](https://github.com/Robin-fang611) |
| **Profile 仓库** | `Robin-fang611/Robin-fang611` |
| **社交账号** | 小红书、抖音、X (`@Robin126988`)、B站 (UID 1340728968) |
| **微信** | weiyangfang950 |

### 头部文案

```
👋 Hi, I'm Robin / 房

非技术背景的 AI-native Builder · 大学生创业者
Non-tech builder & AI-native creator. I vibe-code everything—not a single line hand-written.
```

### 底部 CTA

微信二维码 + 合作邀请，不用 badge / stats / 技术栈标签。

## 未完成 / 待办

1. **GitHub bio 尚未更新。** 助手建议的文案为：
   ```
   Non-tech AI-native Builder · 大学生创业者 · 用 AI 做产品
   ```
   需要 Robin 手动在 GitHub Settings → Profile 中修改（助手环境无法自动完成此操作）。

2. **效果确认。** 推送后未做最终效果检查，需要 Robin 访问 [github.com/Robin-fang611](https://github.com/Robin-fang611) 查看，如有调整再继续。
