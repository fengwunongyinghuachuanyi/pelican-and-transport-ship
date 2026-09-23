# 鹈鹕骑车与运输船

这是 [riba2534/claude-opus-5-5-demo](https://github.com/riba2534/claude-opus-5-5-demo) 的 GitHub fork，仅保留其中两个 3D 网页游戏的源码。游戏及原始项目说明由上游作者提供；此仓库保留 fork 来源，不将上游作品声明为本人原创。

| 游戏 | 源码 | 原作者在线体验 |
| --- | --- | --- |
| 鹈鹕骑自行车 | [pelican-bike/](https://github.com/fengwunongyinghuachuanyi/pelican-and-transport-ship/tree/main/pelican-bike) | [打开游戏](https://claude-opus-5-5.riba2534.cn/) |
| 穿越火线·运输船 | [cf-transport-ship/](https://github.com/fengwunongyinghuachuanyi/pelican-and-transport-ship/tree/main/cf-transport-ship) | [打开游戏](https://claude-opus-5-5-cf-transport-ship.pages.dev/) |

## 本地运行

两个目录是独立工程。分别进入目录，安装依赖并构建：

```bash
cd pelican-bike # 或 cf-transport-ship
npm install
npm run build
```

构建结果在对应目录的 `dist/index.html`，用浏览器打开即可体验。源码依赖 Three.js 和 esbuild；构建后的 HTML 内联脚本和样式。

## 来源与权利

上游项目：[riba2534/claude-opus-5-5-demo](https://github.com/riba2534/claude-opus-5-5-demo)。上游 README 记载了两个游戏的生成过程和原始提示词。本 fork 未验证这些过程陈述。上游仓库目前未提供独立的 LICENSE 文件；公开可见不等于授予任意再分发或商用许可。《穿越火线》相关名称与知识产权归各自权利人，本项目并非官方游戏。

此仓库保存源码，不代表上面的原作者在线体验地址由本账号托管。
