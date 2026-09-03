# 24 个参考网站目录

按上手难度标注：🟢 易=挑选或小改 ｜ 🟡 中=需要 React/CSS 改造 ｜ 🔴 高=需 Canvas/WebGL 工程化

## 类别一：整站灵感与排版（先决定"页面像什么、信息怎么走"）

| 网站 | URL | 最适合找 | 难度 | 使用要点 |
|---|---|---|---|---|
| MotionSites | motionsites.com | 电影感首屏、动态整站、滚动叙事、AI 建站提示词 | 🟢 | 先看整体气质与镜头节奏，再拆成布局/动效/素材/技术四层，不照抄完整 Prompt（会员制） |
| Norrly | norrly.com | 真实网站滚动录像、截图、配色、字体、可复制的 vibe-coding 提示词 | 🟢 | 做第一轮情绪板：先挑"感觉像什么"，再改成自己的结构（免费入口 + Pro） |
| Dribbble | dribbble.com | 网页、UI、品牌、插画、动效概念图与高完成度视觉提案 | 🟢 | 看构图与视觉语言，不默认可直接实现；"漂亮但像海报"的页面需另做交互可行性评估 |
| Supahero | supahero.co | 网站 Hero 首屏：标题、主视觉、CTA、首屏比例 | 🟢 | 先锁定首屏构图，再去组件库找可实现的标题、按钮、背景和滚动进入方式 |
| Landingfolio | landingfolio.com | 整页案例、页面分区、行业分类、组件与模板，尤其适合企业官网 | 🟢 | 优先参考信息层级和转化路径；艺术型页面不宜照搬其商业节奏 |

## 类别二：创意动效与实验（寻找机制、原理和可运行原型）

| 网站 | URL | 最适合找 | 难度 | 使用要点 |
|---|---|---|---|---|
| Codrops Creative Hub | tympanus.net/codrops | GSAP、Three.js、WebGL、滚动叙事、页面转场、字体与图片实验 | 🔴 | 优先找"效果名 + 原理 + demo"，不要只截最终画面；复杂案例需评估性能与移动端降级 |
| CodePen Trending | codepen.io/trending | CSS、Canvas、SVG、JS、Three.js 实时小实验，适合局部动效 | 🟡 | 先确认依赖、许可证、作者说明和浏览器兼容；把 Pen 当原型，不当生产代码 |
| Devsnap CSS Animations | devsnap.me/css-animations | 按钮、加载、文字、卡片、Hover 等 CSS 动画合集 | 🟢 | 适合快速找"一个小动作"；复杂沉浸式场景仍应回到 GSAP/Canvas/WebGL |
| OpenProcessing / Particles | openprocessing.org | p5.js、粒子、噪声、流场、生成艺术、交互视觉 | 🔴 | 记录作者、链接、关键参数与性能；移植前改成模块化、可暂停、可降级的版本 |
| three.js | threejs.org | 3D 场景、模型、相机、材质、粒子、后处理与沉浸式空间 | 🔴 | 它是实现工具不是素材站；先明确场景目标，再决定模型、Shader、粒子和后处理 |

## 类别三：可复用 UI 与组件（从局部效果快速落到真实项目）

| 网站 | URL | 最适合找 | 难度 | 使用要点 |
|---|---|---|---|---|
| UIverse | uiverse.io | 按钮、输入框、开关、加载器、卡片等可复制的 CSS/Tailwind 元素 | 🟢 | 适合设置页和小交互；复制前检查作者许可、可访问性、焦点状态和暗色模式 |
| 21st.dev | 21st.dev | Hero、Shader、背景、卡片、3D、导航、营销区块及可投喂 AI 的 Prompt | 🟡 | 适合"看中一个组件就交给 AI 装进项目"；需统一依赖、主题变量和响应式规则（免费入口+付费） |
| React Bits | reactbits.dev | 动态背景、文字动画、光标、卡片、粒子与视觉编辑工具 | 🟡 | 适合小屋和作品集；一次只选 1–2 个主效果，叠太多会变"赛博夜总会" |
| Magic UI | magicui.design | React/Tailwind/Motion 动画组件、背景、光束、边框、文字与营销区块 | 🟡 | 适合 AI/科技官网和设置页；艺术型页面使用时要降低商业模板感 |
| Animata | animata.design | Hero、文字、图片、列表、滚动、预加载、背景、卡片与微交互（开源） | 🟡 | 适合补页面细节；先看 reduced-motion 与键盘交互，再做视觉改造 |
| Aceternity UI | aceternity.com | Parallax、Globe、Canvas、发光、3D 卡片、Bento、Hero 与暗色科技效果 | 🟡 | 适合宇宙、AI、巨构感页面；谨防统一套用后出现强烈"模板站"痕迹 |

## 类别四：图标与动画素材（补齐轻量视觉资产）

| 网站 | URL | 最适合找 | 难度 | 使用要点 |
|---|---|---|---|---|
| SVG Repo | svgrepo.com | 图标、符号、简单插画与可编辑 SVG | 🟢 | 每个素材单独确认许可证；统一 stroke、圆角、视图框和视觉重量后再进项目 |
| LottieFiles | lottiefiles.com | Lottie/dotLottie 动画、加载、反馈、图标、角色与交互状态 | 🟢 | 优先小面积 UI 动画，不拿它硬撑全屏电影感；确认授权、循环缝隙、颜色可改性和文件体积 |

## 类别五：字体与排版（建立标题、正文、标注和多语言秩序）

| 网站 | URL | 最适合找 | 难度 | 使用要点 |
|---|---|---|---|---|
| FontVS：17款免费打字机字体 | 中文文章/字体索引（PDF 未给出明确 URL，按标题检索） | 复古、墨迹、档案、打字机与 Zine 气质的字体 | 🟢 | 把文章当审美入口；最终仍需回到字体来源核对网页嵌入和商业授权 |
| Fontshare | fontshare.com | 品牌感较强的展示体、正文体和成套家族，适合作品集与官网 | 🟢 | 先测试真实标题和正文，不只看字母样张；中文项目需另配 CJK 字体 |
| Google Fonts | fonts.google.com | 网页嵌入、语言筛选、变量字体与稳定通用字体方案 | 🟢 | 作为可靠底盘；为国内访问和隐私稳定性，部署时建议自托管字体文件 |
| Fonts In Use | fontsinuse.com | 某款字体在海报、品牌、书籍、网页、音乐与包装里的真实用法 | 🟢 | 学"怎么用字体"而不是下载字体；重点观察字号、字距、对比和搭配 |
| Font Squirrel | fontsquirrel.com | 可商用免费字体筛选、Webfont Generator 与字体识别工具 | 🟢 | 即便标注商用也要查看每款字体的具体许可；避免只下载不保存授权来源 |
| Typewolf | typewolf.com | 网页字体趋势、真实网站用字、字体推荐与搭配方向 | 🟢 | 解决"这个页面为什么显得高级"；参考比例、层级和搭配，不只抄字体名 |
