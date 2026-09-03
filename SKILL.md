---
name: web-inspiration-toolkit
description: 网页视觉设计灵感与实现决策工具包。当任务涉及做网页/落地页/UI 视觉设计（landing page, hero, portfolio）、找设计灵感与情绪板、选动效方案（滚动/hover/粒子/3D 转场）、选组件/图标/Lottie 素材、选字体与排版搭配、或评估某个网页效果能否实现时触发。基于 24 个精选参考站，按"先找气质→再找机制→最后找零件"四步决策法路由到对应资源，并强制授权与性能核查。
---

# Web Inspiration Toolkit

用这套流程把"我喜欢某个网页"变成可落地的设计，而不是收藏截图。

## 四步决策法

1. **先找气质**：确定页面情绪、镜头感、信息密度（整站灵感/Hero/排版案例）。
2. **再找机制**：确定滚动、Hover、粒子、3D、转场的触发方式与交互逻辑；记录"效果名 + 原理 + demo"，不要只截最终画面。
3. **最后找零件**：选组件、图标、Lottie、字体；统一风格（stroke/圆角/视觉重量）、授权与响应式规则。
4. **每屏只设一个视觉主角**：先做一个主效果跑通再叠加；复杂效果叠加不是高级，是吵（警惕"赛博夜总会"）。

核心原则：参考"语言"，不复制"皮肤"——拆出构图/节奏/材质/光线/交互，再为目标项目重做。链接比截图重要，动效必须在网页里看。

## 按任务类型路由

| 任务 | 参考文件 | 首选站点 |
|---|---|---|
| 整站灵感/Hero/版式/情绪板 | references/sites-catalog.md 类别一 | MotionSites、Norrly、Dribbble、Supahero、Landingfolio |
| 动效机制/滚动叙事/3D/粒子 | 类别二 | Codrops、CodePen、Devsnap、OpenProcessing、three.js |
| 可复用 UI 组件/动效组件 | 类别三 | UIverse、21st.dev、React Bits、Magic UI、Animata、Aceternity UI |
| 图标/Lottie/矢量素材 | 类别四 | SVG Repo、LottieFiles |
| 字体选择/配对/排版参考 | 类别五 | FontVS、Fontshare、Google Fonts、Fonts In Use、Font Squirrel、Typewolf |
| 拆解参考页/评估可行性/授权性能核查/难度落地策略 | references/workflow-playbook.md | 全部 |

按项目类型组合路线：
- **沉浸式/艺术页面**：MotionSites·Norrly·Dribbble → Codrops·OpenProcessing·three.js → React Bits·Aceternity·SVG Repo；先建空间与交互，再美化。
- **企业官网/商业落地页**：Landingfolio·Supahero 定结构 → 21st.dev·Magic UI·Animata·UIverse 取组件 → Google Fonts·Fontshare·Typewolf 定字体；信息与转化优先，动效只引导视线。
- **作品集**：Dribbble·Fonts In Use·Codrops 找视觉 → CodePen·React Bits 做实验；网页效果不能抢走作品本身的注意力。

## 红线清单

- **授权核查**：参考案例 ≠ 可复制资产。代码看仓库 License；字体看 Web/商业授权；图标与 Lottie 逐项确认许可；保存来源与许可证记录。
- **性能预算**：粒子/WebGL/大字体文件先估算代价；Google Fonts 部署时自托管。
- **reduced-motion**：所有动效提供 `prefers-reduced-motion` 降级；键盘可操作。
- **移动端降级**：复杂沉浸式效果必须有移动端简化方案；先确认 PC 优先还是兼顾手机。
- **不要堆砌效果**：一屏一个主效果，一次只集成 1–2 个主视觉机制。
- **难度匹配技术栈**：易=挑选/小改；中=需 React/CSS 改造；高=需 Canvas/WebGL 工程化。无构建工具的纯静态项目不要选 React 组件源；把 CodePen 当原型不当生产代码；Dribbble 上"漂亮但像海报"的页面需先做交互可行性评估。
