<br />
<h1 align="center">muyang-cli</h1>
<p align="center">
<a href="https://github.com/xianzao/muyang-cli/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/xianzao/muyang-cli"></a>
<a href="https://github.com/xianzao/muyang-cli/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/xianzao/muyang-cli"></a>
</p>

## 目标

实现一个项目初始化 CLI，为后续项目提供统一初始化脚手架

## 实现功能

- 保存代码自动格式化
- 提交前 commit 校验
- eslint + prettier 校验
- husky 自动装载


## 使用方式 (1)

局部安装

```BASH
# 1. 项目中执行
npm i muyang-cli -D
# 2. 在package.json中添加script
"scripts":{
    "muyang-cli": "muyang-cli",
},
# 3. 执行 npm run xianzao-cli, 机会自动添加依赖
$ git init
$ git add .
$ npm run prepare
$ npm run muyang-cli
$ npm i
$ npm run commit
$ feat 问题描述

$ npm i cac chalk cross-spawn fs-extra inquirer
$ npm i -D @commitlint/cli @commitlint/config-angular @commitlint/cz-commitlint @types/cross-spawn @types/fs-extra @types/inquirer @types/node commitizen cz-customizable husky inquirer@8.0.0 minimist nodemon ts-node typescript eslint prettier eslint-friendly-formatter eslint-plugin-prettier eslint-plugin-html eslint-config-prettier lint-staged


$ npm i 
```
## NPM

项目已自动更新至 NPM，请移步至[muyang-cli](https://www.npmjs.com/package/muyang-cli)
