# 段永平思维操作系统 · Claude Code Skill

> "买股票就是买公司，买公司就是买公司的未来现金流折现，句号！"

基于段永平（大道）公开言论、著作、方三文对话等 7 个维度的深度调研，提炼出的 Claude Code Skill。激活后，AI 会以段永平的身份和思维方式与你对话——用他的语气、判断框架和表达DNA 分析投资、商业模式和企业管理问题。

## 这个 Skill 能做什么

- **投资顾问**：用段永平视角分析股票、商业模式、估值和投资决策
- **商业思维**：用他的企业经营哲学（本分、消费者导向、Stop Doing List）审视产品和管理
- **角色扮演**：模拟段永平在特定投资场景下的判断和表达，包括他的冷幽默和断言式句式

### 内核提炼

| 维度 | 内容 |
|------|------|
| 核心心智模型 | 6 个（第一性原理还原、反向排除、商业模式优先、能力圈纪律、本分哲学、平常心与长期视角） |
| 决策启发式 | 10 条（先排除再选择、宁可错过不可做错、毛估估即可等） |
| 表达 DNA | 短句、断言式、先结论后解释、自嘲冷幽默、双模式（核心极度确定/边界极度谦虚） |
| 调研来源 | 4 本书 + 方三文对话 SRT 字幕 + 博客归档 + 网络搜索，详见 `references/` |

## 如何安装

### 方法一：手动安装

1. 将本仓库克隆到你的 Claude Code skills 目录：

```bash
git clone https://github.com/<your-username>/duan-yong-ping.git ~/.claude/skills/duanyongping-perspective
```

2. 确认目录结构如下：

```
~/.claude/skills/duanyongping-perspective/
├── SKILL.md          # Skill 主文件（Claude Code 自动识别）
└── references/       # 调研素材和原始资料
```

3. 重启 Claude Code 或开启新会话，Skill 会自动加载。

### 方法二：使用 Claude Code CLI 安装

在 Claude Code 中直接运行：

```
/install-skill https://github.com/<your-username>/duan-yong-ping
```

### 验证安装成功

在 Claude Code 中输入以下任一触发词，如果段永平角色被激活，说明安装成功：

- "用段永平视角"
- "大道怎么看"
- "问问大道"
- "duanyongping perspective"

## 如何使用

### 触发方式

在 Claude Code 对话中使用以下任一表达即可触发：

**直接指名：**
- "用段永平视角"
- "段永平模式"
- "duanyongping perspective"

**别名/昵称：**
- "大道怎么看"
- "问问大道"
- "中国巴菲特"

**场景触发：**
- "帮我用段永平的角度想想"
- "如果段永平会怎么做"
- "用价值投资的角度看看"

### 使用示例

```
你：用段永平视角看看苹果这家公司

段永平：苹果是我最懂的公司。

商业模式很简单——做最好的产品，赚最多的钱。差异化极强，用户粘性极高。库克是比乔布斯更好的CEO，他把乔布斯造的钟运营得非常好。

我买入苹果是因为我看见了那个钟。乔布斯是造钟人，不是报时人。造钟人走了，钟还在走。这就够了。

买不买你自己决定，我只是分享我的思考方式。
```

```
你：大道怎么看加密货币？

段永平：这个我不懂。不懂就不做，这是最安全的。
```

```
你：帮我用段永平的角度分析一下茅台的商业模式

段永平：茅台是好生意。

差异化——别人做不出来。你能做出第二个茅台吗？做不到。这就是护城河。

文化——做好酒的质量至上，这是利润之上的追求。

10年后茅台还在吗？还在。还在赚钱吗？还在。这就够了。

毛估估贵不贵？这个问题你自己判断。我能说的是，茅台的商业模式我看懂了。
```

### 退出角色

输入以下任一表达即可退出角色扮演：

- "退出"
- "切回正常"
- "不用扮演了"
- "exit role"

## 项目结构

```
.
├── SKILL.md                              # Skill 主文件（角色定义、心智模型、表达DNA）
├── README.md                             # 本文件
├── references/
│   ├── research/                         # 调研过程和中间产物
│   │   ├── 01-writings.md               # 著作/博文提炼
│   │   ├── 02-conversations.md          # 访谈/对话提炼
│   │   ├── 03-expression-dna.md         # 表达DNA分析
│   │   ├── 04-external-views.md         # 他者视角
│   │   ├── 05-decisions.md              # 决策记录
│   │   ├── 06-timeline.md               # 时间线
│   │   ├── 07-fangsanwen-conversation.md # 方三文对话提炼
│   │   └── quality-validation.md        # 质量校验
│   └── sources/                          # 原始资料
│       ├── books/                        # 书籍（PDF/EPUB）
│       └── transcripts/                  # 字幕文件
└── scripts/                              # 辅助脚本
```

## 免责声明

- 本 Skill 基于段永平公开言论和投资记录推断，**非本人观点**
- 角色扮演中的投资分析仅供学习参考，**不构成任何投资建议**
- 段永平本人与本项目无关

## 致谢

- 本 Skill 由 [女娲 · Skill 造人术](https://github.com/alchaincyf/nuwa-skill) 生成
- 创建者：[花叔](https://x.com/AlchainHust)

## License

MIT
