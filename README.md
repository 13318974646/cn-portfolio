# 付晨希 · 个人作品集

机械设计制造及其自动化 · 结构设计与整机建模

**在线预览**：[https://YOUR-USERNAME.github.io/YOUR-REPO/](https://cn-portfolio-13318974646.netlify.app/)

---

## 这是什么

一个单页作品集，用暗场视觉语言串起四个项目：预制构件机器人、智能菠萝采收机器人、可拆卸多单元磁吸式扫地机器人，以及独立开发的非遗亲子体验小程序。

整站就是**一个 `index.html`**——CSS、JS、图片（base64 内联）全部打包在里面。没有外部依赖、没有构建步骤、不需要服务器，双击就能打开。

## 页面结构

| # | 区块 | 内容 |
|---|------|------|
| 01 | Hero | 姓名与三维背景影像，鼠标擦洗可拖动画面 |
| 02 | Statement | 中英双语自述 |
| 03 | Metrics | 项目 / 论文 / 竞赛数量 |
| 04 | Works | 四个项目：产品渲染、三视图、剖视图、小程序截图 |
| 05 | Awards | 17 项竞赛成绩（内部滚动浏览） |
| 06 | Toolkit | 技能栈 |
| 07 | Contact | 联系方式 |

## 交互

- 首屏背景影像随鼠标横向擦洗，入场字符解码
- 作品区图片分三种呈现：产品渲染去底浮空、工程图纸带标题栏、小程序截图横向拖拽画廊
- **图纸卡可点击放大**，三视图的标注在版面里偏小，点开看全图（支持 ESC 关闭）
- 全站平滑滚动、滚动入场动画，`prefers-reduced-motion` 下自动关闭

## 技术栈

- React 18 + TypeScript
- Vite 5 + `vite-plugin-singlefile`（单文件构建）
- Tailwind CSS 3
- Framer Motion（入场与滚动联动）
- Lenis（平滑滚动）

## 本地打开

双击 `index.html` 即可，不需要起服务器。

## 部署到 GitHub Pages

1. 仓库 **Settings → Pages**
2. **Source** 选 `Deploy from a branch`
3. **Branch** 选 `main`，目录选 `/ (root)`
4. 保存后等 1 分钟左右，访问 `https://YOUR-USERNAME.github.io/YOUR-REPO/`

## 关于图片

- 三视图与剖视图由 SolidWorks 导出，成品图统一压到纸色底（`#F2F0F6`）以适配暗色版面，保留标注与剖切关系
- 所有图片已转 WebP 并内联为 base64，整站无需额外请求任何资源

## 联系方式

- 邮箱：2169490740@qq.com
- 电话：13318974646
- 城市：珠海
