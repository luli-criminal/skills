# WorkBuddy Skills

个人收集的 WorkBuddy / Agent Skills。每个技能是一个独立目录，内含一份 `SKILL.md`（YAML frontmatter + 正文说明）。

## 技能列表

| 技能 | 用途 |
|---|---|
| [`person-public-record-trace`](skills/person-public-record-trace/SKILL.md) | 用公开渠道溯源具体人物的学历、毕业院校、毕业时间、就业去向、任职轨迹。核心是先锁定唯一身份、再穷尽定向检索，最后诚实区分「查不到」与「不存在」 |

## 目录结构

```
.
├── README.md
└── skills/
    └── <skill-name>/
        └── SKILL.md
```

## 安装方式

把某个技能目录复制到本地技能目录即可：

```bash
# 用户级（对所有项目生效）
cp -r skills/person-public-record-trace ~/.workbuddy/skills/

# 项目级（仅对当前工作区生效）
cp -r skills/person-public-record-trace <project>/.workbuddy/skills/
```

## 免责声明

技能正文包含的检索方法、来源判断规则和案例说明，仅用于**公开信息的检索方法学习**。文中涉及的具体人物信息均来自公开渠道，仅供说明检索路径之用，不构成对任何个人的评价或结论。若用于背调、招聘核实等正式用途，公开检索只能定性、不能定论，正式结论须以对方提供的学历/学位/任职证明或官方渠道为准。
