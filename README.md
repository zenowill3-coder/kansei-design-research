# 感性体验研究助手（Kansei Design Research Skill）

面向任意产品品类的感性设计研究技能：通过感性目标拆解、Attitude/Emotion/Sensation 三层关键词筛选、功能配置比较、设计方案比较、结构化评价与单方案迭代，挖掘用户真实需求并输出感性设计策略可视化报告。

## 安装方式

### 方式一：对话中直接安装（推荐）

在豆包工作的对话输入框中直接发送（把下方链接替换为本仓库实际地址）：

```text
新建技能 安装：https://github.com/<你的用户名>/kansei-design-research
```

系统会自动完成导入和安装，随后按技能流程开始对话即可。

### 方式二：从链接导入

打开豆包 PC 客户端「插件·技能·伙伴」→ 技能页面 → 右上角「+ 添加 / 上传技能」→ 选择「从链接导入」，粘贴本仓库 URL：

```text
https://github.com/<你的用户名>/kansei-design-research
```

### 方式三：克隆后本地安装（兜底）

```bash
git clone https://github.com/<你的用户名>/kansei-design-research.git
```

然后在豆包 PC 客户端「上传技能」窗口中，把包含 `SKILL.md` 的文件夹拖入即可。

## 仓库结构

```text
kansei-design-research/
├── SKILL.md                         技能元数据与核心流程指令
├── references/
│   ├── image-generation-spec.md     生图规范（版式、配色、字体、提示词模板）
│   ├── vocabulary-attitude.md       Attitude 态度层感性词汇库
│   ├── vocabulary-emotion.md        Emotion 情绪层感性词汇库
│   └── vocabulary-sensation.md      Sensation 感知层感性词汇库
├── LICENSE                          使用许可条款
└── README.md                        本文件
```

## 使用须知

- 技能调用图像生成时，消耗的是**使用者本人账号**的图像生成额度；免费账号每日有免费次数，用完当日暂停、次日重置，完整研究流程建议搭配订阅使用。
- 本仓库的使用受 `LICENSE` 条款约束：允许个人安装与使用，禁止商业性使用、修改演绎与未经授权的再分发。
