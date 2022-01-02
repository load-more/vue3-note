# Vue3 学习笔记

## NPM

### 基本命令

- `npm -v`
- `npm install <Module Name>`
- `npm install <Module Name> -g`
- `npm list -g`
- `npm list <Module Name>`
- `npm install <Module Name>@x.x.x`
- `npm install --save <Module Name>`
- `npm install --save-dev <Module Name>`
- `npm help <command>`
- `npm update <Module Name>`
- `npm update <Module Name> -g`
- `npm cache clear`
- `npm publish <package>@<version>`
- `npm unpublish <package>@<version>`

### package.json属性说明

- name
- version
- description
- homepage - 包的官网 url
- author
- contributors - 包的其他贡献者姓名
- dependencies
- devDependencies
- main
- keywords

**package.json 文件中版本号说明：**

- `5.0.3`：表示安装固定版本 5.0.3；
- `^5.0.3`：表示安装 5.x.x 中最新的版本；
- `~5.0.3`：表示安装 5.0.x 中最新的版本。

