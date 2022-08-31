# 🔨MinSmartyUI 是什么?

一个 Mini 版的组件库，基于 Vite 栈。为需要学习前端工程化的同学搭建的组件库搭建教学模型

## Features

- ⚡️ Vue 3, Vite 2, pnpm, ESBuild - born with fastness
- 🦾 TypeScript, of course
- 🗂 File based routing
- ⚙️ Unit Testing with Vitest
- 😃 Eslint + Prittier
- 🎨 UnoCSS - the instant on-demand atomic CSS engine
- 🌍 I18n ready
- 🚘 CI/CD with GithubActions

## Install

```bash
npm i min-smarty-ui-vite
```

## Quick Start

```js
import Vue from "vue";
import "min-smarty-ui-vite/entry.css";
import MinSmartyUI from "min-smarty-ui-vite";

const App = {
  template: `
       <SButton color="blue">主要按钮</SButton>
    `,
};
createApp(App).use(MinSmartyUI).mount("#app");
```
