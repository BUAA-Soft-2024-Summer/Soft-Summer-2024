# 插件开发指引

> 北京航空航天大学 2024 年夏季学期《程序设计实践》插件开发指引

---

## 插件开发

现在很多软件都支持插件，比如大家熟悉的 Visual Studio Code，各种 IDE，以及笔记软件 Obsidian 等。插件的存在使得软件的功能更加灵活，从而满足不同用户个性化的需求。

不同软件有着自己不同的插件生态，插件的开发方式也不尽相同。例如，JetBrains IDE 使用 Java 开发，从而它的插件也用 Java 开发。Visual Studio Code 这类应用基于 Electron，从而插件也使用 JavaScript 开发。目前，使用 Electron 的跨平台应用十分流行，因此这里我们主要介绍两款基于 Electron 的应用插件开发——Visual Studio Code 和 Obsidian，其他插件的开发也大同小异，大家参考官网的文档即可。

对于选题，大家可以自行选择，只要是你觉得有用的插件都可以，这里给大家提供一些参考。

- 生产力工具：快捷键，代码建议，TODO 集成等。
- 休闲娱乐：提高代码编写乐趣的小工具。（例如 [Power Mode](https://github.com/hoovercj/vscode-power-mode)）

## 准备工作

对于 Electron 应用的插件开发，我们使用 JavaScript 或者 TypeScript。

> 其实本质是 JavaScript，TypeScript 只是有显示类型，最终仍会被编译为 JavaScript。

具体地，你需要有以下的工具和环境：

- [Visual Studio Code](https://code.visualstudio.com/) 或其他你熟悉的 JavaScript 开发环境。
- [Node.js](https://nodejs.org/en)
- [Git](https://git-scm.com/)

---

## Visual Studio Code 插件开发

### 开发流程

> 具体参考 [VSCode 插件开发][1]。

1. 安装 [Yeoman](https://yeoman.io/) 和 [VS Code Extension Generator](https://www.npmjs.com/package/generator-code)。
2. 创建插件模板。
3. 编写代码（推荐使用 TypeScript）。
4. 运行和调试
5. 发布插件

Visual Studio Code 的插件的发布使用 Azure 的 CI/CD，无需任何费用，也没有审核，只需要创建 Azure 账号即可，因此还是推荐大家将自己的插件发布到[插件市场](https://marketplace.visualstudio.com/)。

### 参考资料

- [插件开发][1]
- [主题开发][2]（只涉及 CSS，不能单独作为课程作品）
- [UI 设计指南][3]
- [插件发布][4]

### 参考插件

- [vscode-extension-samples](https://github.com/microsoft/vscode-extension-samples)（官方）

----

## Obsidian 插件开发

> 适合之前使用并熟悉 Obsidian 的同学。

### 开发流程

> 具体参考 [Obsidian 插件开发][5]。

- 下载插件样例。
- 编写代码（推荐 TypeScript）。
- 在 Obsidian 中加载插件调试（可结合 [Hot Reload](https://github.com/pjeby/hot-reload) 插件自动热更新）。
- 发布插件到 GitHub
- 发布插件至插件市场（可选）

Obsidian 官方提供了 GitHub Workflow 从而能够在 GitHub 中自动打包发布 Obsidian 插件，就可以供别人使用了。但是要上传到插件市场则需要向官方仓库提 PR，并且需要通过审核。如果插件效果比较好，可以考虑在课程结束后发布到插件市场。

### 参考资料

- [插件开发][5]
- [插件开发（中文）][7]
- [插件发布][6]

### 参考插件

- [Heading Toggler](https://github.com/Lord-Turmoil/heading-toggler-obsidian)
- [Emoji Toolbar](https://github.com/oliveryh/obsidian-emoji-toolbar)



[1]: https://code.visualstudio.com/api/get-started/your-first-extension	"VSCode extension example"
[2]: https://code.visualstudio.com/api/extension-guides/color-theme	"VSCode color theme"
[3]: https://code.visualstudio.com/api/ux-guidelines/overview	"VSCode UX guidelines"
[4]: https://code.visualstudio.com/api/working-with-extensions/publishing-extension	"VSCode extension publishing"
[5]: https://docs.obsidian.md/Plugins/Getting+started/Build+a+plugin	"Obsidian plugin example"
[6]: https://docs.obsidian.md/Plugins/Releasing/Release+your+plugin+with+GitHub+Actions	"Obsidian plugin publishing"
[7]: https://luhaifeng666.github.io/obsidian-plugin-docs-zh/zh2.0/getting-started/create-your-first-plugin.html	"Obsidian plugin example (zh-cn)"





