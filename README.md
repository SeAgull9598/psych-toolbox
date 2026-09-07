# 心理工具箱

两款独立的在线测评工具：定位测评与能力画像。保留原站的题目、评分逻辑、结果文案和样式，并提供统一入口。

## 访问网址

- [心理工具箱](https://seagull9598.github.io/psych-toolbox/)
- [定位测评](https://seagull9598.github.io/psych-toolbox/positioning.html)
- [能力画像](https://seagull9598.github.io/psych-toolbox/capability.html)

## 使用

选择工具，阅读填写须知，逐题作答后查看结果。结果页支持生成长图，供自行保存。测评仅用于自我探索与成长参考，不构成诊断。

## 文件与维护

- `index.html`：统一入口。
- `positioning.html`：定位测评。
- `capability.html`：能力画像。
- 两个测评共用原站的 `qrcode.jpg` 和长图导出组件 `html2canvas.min.js`。
- GitHub Pages 使用 `main` 分支根目录发布；修改文件后自动重新部署。

无需安装依赖或运行构建命令。网页资源均保存在本仓库中，运行时不依赖 WorkBuddy。

## 数据

答题和结果计算在浏览器中进行，没有增加后台答卷收集、分析跟踪或账号登录。能力画像保留原有 localStorage 结果存储逻辑。定位测评原页面没有跨测评数据写入，本迁移保持该行为。

## 来源与第三方组件

- 定位测评：https://2499ae41def74d9ba8973f9dbd72928f.app.workbuddy.link
- 能力画像：https://011128794d924540aeaa721c202a8692.app.workbuddy.link
- html2canvas 1.4.1：https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js （MIT License，许可声明保留于文件头）。

两个二维码均从对应原站取得，并核验为相同图片。两份测评 HTML 保留原始内容，长图组件采用公开标准发行版补齐。
