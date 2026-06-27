<br /><br />

<h1 align="center"><img height="150" src="https://driverjs.com/mascot-head.png?v=1" /><br> Driver.js</h1>

<p align="center">
  <a href="https://github.com/nilbuild/driver.js/blob/master/license">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://www.jsdelivr.com/package/npm/driver.js">
    <img src="https://data.jsdelivr.com/v1/package/npm/driver.js/badge?style=rounded" alt="jsdelivr hits" />
  </a>
  <a href="https://npmjs.org/package/driver.js">
    <img src="https://img.shields.io/npm/dm/driver.js" alt="downloads" />
  </a>
</p>

<p align="center">
  <b>功能强大、高度可定制的产品引导和功能介绍库</b></br>
  <sub>无外部依赖、轻量级、支持所有主流浏览器且高度可定制</sub><br>
</p>

<br />

- **简单**: 易于使用，完全没有任何外部依赖
- **轻量级**: 压缩后仅 5kb，而其他库压缩后超过 12kb
- **高度可定制**: 拥有强大的 API，可按需自由使用
- **高亮任意元素**: 可以高亮页面上的（名副其实的）任何元素
- **功能介绍**: 为你的 Web 应用创建强大的功能引导介绍
- **焦点切换器**: 为用户添加焦点切换功能
- **用户友好**: 所有操作均可通过键盘控制
- **TypeScript**: 使用 TypeScript 编写
- **行为一致**: 在所有浏览器中表现一致
- **MIT 许可**: 个人和商业使用免费

<br />

## 文档

如需查看演示和文档，请访问 [driverjs.com](https://driverjs.com)

<br />

## 又是一个引导库吗？

**不是**，它不仅仅是一个引导库。**产品引导只是其众多用例之一**。Driver.js 可用于任何需要为页面添加覆盖层的场景；常见用例包括：当用户与页面组件交互时高亮该组件以保持用户专注，提供上下文帮助——例如在用户填写表单时显示带暗色背景的弹出框，用作焦点切换器将用户的注意力引导至页面上的某个组件，模拟你可能在在线视频播放器上见过的"关灯"效果，用作简单的模态框，当然也包括产品引导等。

Driver.js 使用原生 TypeScript 编写，零依赖，且高度可定制。它提供了多种选项供你调整行为，并**为你提供钩子函数**，在元素被高亮、即将被高亮或取消选中时进行操作。

> 此外，将 Driver.js 与其他库进行大小对比，它是最轻量的——**压缩后仅约 5kb**，而其他库则在 12kb 以上。

<br>

## 本地开发

库的源码位于 `src/` 目录。若要在实际的示例集合中调试你的修改，可以运行 playground——它是位于 `playground/` 目录下的 Astro 应用，直接从源码引入库，编辑后会即时热重载：

```sh
pnpm install
pnpm run playground:install
pnpm dev
```

每个示例都有独立的文件，位于 `playground/src/examples/` 目录下，并作为侧边栏中的页面展示。如需添加示例，将条目放入相应的分组中（`highlight.ts`、`popover.ts`、`tour.ts`、`api.ts`）。

其他常用脚本：

```sh
pnpm build
pnpm test
```

## 贡献

欢迎提交 Pull Request、创建 Issue 或帮助宣传。

## 许可证

MIT &copy; [Kamran Ahmed](https://twitter.com/nilbuild)
