# 易思心理一轮内测

心理成长产品的首轮内测入口，包含体验官介绍、三款测评和反馈问卷。测评按“看见自己 → 自我探索（原定位测评）→ 能力画像”的顺序排列，保留原站的题目与评分逻辑。

## 访问网址

- [易思心理一轮内测](https://seagull9598.github.io/psych-toolbox/)
- [自我探索（原定位测评）](https://seagull9598.github.io/psych-toolbox/positioning.html)
- [能力画像](https://seagull9598.github.io/psych-toolbox/capability.html)
- [看见自己 · 前测问卷](https://seagull9598.github.io/psych-toolbox/self-awareness.html)

## 使用

先阅读首页的体验官介绍，依次完成三份测评，保存结果并记录各测评用时。每份测评结果页的“返回首页”按钮会回到首页的测评入口区域，最后填写[反馈问卷](https://v.wjx.cn/vm/ehKc2xZ.aspx#)。

选择工具，阅读填写须知，逐题作答后查看结果。结果页支持生成长图，供自行保存。测评仅用于自我探索与成长参考，不构成诊断。

## 文件与维护

- `index.html`：体验官介绍、按顺序排列的测评入口与反馈问卷链接。
- `positioning.html`：自我探索（原定位测评）。
- `capability.html`：能力画像。
- `self-awareness.html`：看见自己前测问卷，16 道题涵盖觉察水平、情绪状态、自我态度与自我认知，供 7 天冥想体验营开始前记录基线状态。
- 定位测评与能力画像共用原站的 `qrcode.jpg` 和长图导出组件 `html2canvas.min.js`。
- 看见自己前测问卷使用原页面内嵌的头像、二维码和原生 SVG/Canvas 长图导出逻辑，无需额外资源。
- GitHub Pages 使用 `main` 分支根目录发布；修改文件后自动重新部署。

无需安装依赖或运行构建命令。网页资源均保存在本仓库中，运行时不依赖 WorkBuddy。

## 数据

答题和结果计算在浏览器中进行，没有增加后台答卷收集、分析跟踪或账号登录。能力画像保留原有 localStorage 结果存储逻辑。定位测评原页面没有跨测评数据写入，本迁移保持该行为。看见自己前测问卷的答案只保存在当前页面内存中，退出后无法再次查看结果，需及时导出保存。

## 来源与第三方组件

- 定位测评：https://2499ae41def74d9ba8973f9dbd72928f.app.workbuddy.link
- 能力画像：https://011128794d924540aeaa721c202a8692.app.workbuddy.link
- 看见自己 · 前测问卷：https://5357f3d54b9f4b9a9da58bf076efa1bb.app.workbuddy.host
- html2canvas 1.4.1：https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js （MIT License，许可声明保留于文件头）。

定位测评与能力画像的两个二维码均从对应原站取得，并核验为相同图片；长图组件采用公开标准发行版补齐。看见自己前测问卷保留所提供原网页的题目、样式、评分逻辑、内嵌二维码与结果导出功能。三份测评均增设结果页返回入口，自我探索的显示名称已统一。

