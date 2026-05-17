# doggy-growth-plan-landing

这是 **Doggy Growth Plan / GG Bond** 的在线演示仓库。

## 链接

- 在线演示：https://kndhjk.github.io/doggy-growth-plan-landing/
- 仓库地址：https://github.com/kndhjk/doggy-growth-plan-landing
- 关联项目仓库：https://github.com/UOA-CS732-S1-2026/group-project-gg-bond
- 在线产品 demo：http://4.155.227.179/

## 这个仓库是干什么的

这个仓库承载的是 **CS732 小组项目 Doggy Growth Plan** 的一套**双语在线演示页**。

它现在已经不是最早那种简单 landing page，而是被重构成了一套更适合 seminar / presentation 使用的在线 slide deck，支持：

- 中英文切换
- 分页式演示
- 按成员分段组织内容
- 图片 / mockup / SVG 视觉说明
- 轻量动效
- 二维码入口
- 手机和桌面端都能正常浏览

## 当前演示结构

当前版本按 GG Bond 小组成员分工组织，整体流程如下：

- Opening
- Project overview
- Huanhuan Li
- Xingyan Zhou
- Ming Zhao
- Xiang Zhang
- Kejun Xu
- Jiayi Lyu
- GitHub / collaboration
- Closing / Q&A

当前总页数为：
- **16 页**

## 当前版本特点

### 1. 六人分页面
每位成员都有自己对应的演示页，而不是把所有人压缩到一个总览页里。

### 2. 双语演示
页面内容支持中英文即时切换，适合不同 audience 场景。

### 3. 更适合答辩 / seminar
整个页面已经按“在线答辩稿”的思路重构，不只是展示链接，而是直接拿来讲。

### 4. 加入视觉增强
当前版本已经加入：

- 自定义 SVG 结构图
- 产品风格 mockup
- 轻量动画（float / glow / shimmer）
- 更强的视觉层级

### 5. Ming Zhao 部分强化
Ming Zhao 的部分被专门增强成更突出的一段，用来体现：

- 系统整合
- 架构连接能力
- 社区 / matchmaking / chat / achievement 这类跨模块整合能力

## 主要文件

- `index.html`：主演示文件
- `assets/slides/*.svg`：演示里使用的自定义 SVG 图

## 实现方式

这套演示刻意做成了：

- **单 HTML 主文件**
- 配少量静态资源
- 直接托管在 GitHub Pages 上

这样做的好处是：

- 改动快
- 推送快
- 部署简单
- seminar 前临时改内容很方便
- 不依赖主项目运行环境

## 页面里现在包含什么

当前 `index.html` 里主要包含：

- 顶部导航
- slide jump 下拉
- 中英文字段切换（`data-cn` / `data-en`）
- 底部分页控制
- 轻量 CSS 动效
- speaker 分页结构
- 各种说明图和 mockup

## 如果后面还要继续改

后续最常见的修改入口：

### 改讲稿内容
直接编辑：
- `index.html`

### 换图 / 加图
直接放到：
- `assets/slides/`

### 改页面跳转标题
修改脚本里的：
- `labels` 数组

### 调整 speaker 分组或导航结构
修改：
- 顶部 nav 的 `data-target`
- 对应 slide 顺序

## 部署方式

这个仓库默认用于 **GitHub Pages**。

推送到默认分支后，页面会发布到：
- https://kndhjk.github.io/doggy-growth-plan-landing/

## 当前状态

这个仓库目前正在作为 GG Bond / Doggy Growth Plan 的 seminar 在线演示面使用。
