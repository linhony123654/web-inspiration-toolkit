# Web Inspiration Toolkit

一个网页视觉设计灵感与实现决策工具包（Agent/Codex Skill）：基于 24 个精选参考站，按"先找气质 → 再找机制 → 最后找零件"的四步决策法，把"我喜欢某个网页"变成可落地的设计，并强制授权与性能核查。

## 安装（作为 Codex / Agent Skill）

### 方式一：git clone 到 skills 目录

```bash
git clone https://github.com/linhony123654/web-inspiration-toolkit.git ~/.codex/skills/web-inspiration-toolkit
```

（将 `~/.codex/skills` 替换为你实际使用的 skills 目录即可。）

### 方式二：curl 下载 tar.gz 解压

```bash
curl -L https://github.com/linhony123654/web-inspiration-toolkit/archive/refs/heads/main.tar.gz -o web-inspiration-toolkit.tar.gz
mkdir -p ~/.codex/skills/web-inspiration-toolkit
tar -xzf web-inspiration-toolkit.tar.gz --strip-components=1 -C ~/.codex/skills/web-inspiration-toolkit
```

## 目录结构

```
web-inspiration-toolkit/
├── SKILL.md                        # Skill 入口：四步决策法、任务路由表、红线清单
└── references/
    ├── sites-catalog.md            # 24 个参考网站目录（按五大类别、上手难度标注）
    └── workflow-playbook.md        # 方法论手册：五层拆解法、可行性评估、授权与性能核查清单
```

- `SKILL.md`：技能主文件，含触发条件描述与按任务类型的资源路由。
- `references/sites-catalog.md`：整站灵感 / 创意动效 / UI 组件 / 图标与 Lottie / 字体排版五类参考站的用途与使用要点。
- `references/workflow-playbook.md`：从拆解参考页到上线前核查的完整工作流程。

## License

使用其中引用的第三方资源前，请自行核对各站点与素材的许可条款。
