---
title: 开发和构建
---

# 开发和构建

## 开发

### 安装依赖

```bash
$ npm i
```

### 启动开发服务

```bash
$ npm start
```

### 提交代码

```bash
$ npm run commit
```

### 单元测试

```bash
$ npm run test
```

## 构建

### 构建站点

```bash
$ npm run build:site
```

### 部署站点

```bash
$ npm run deploy:site
```

### 打包

```bash
$ npm run build
```

### Release

```bash
# https://github.com/lerna/lerna/blob/d93510847a7ee37c56b196c0a5f32c746319b542/commands/version/README.md#--conventional-commits
$ npm run release
```

### Pre-Release

```bash
# https://github.com/lerna/lerna/blob/d93510847a7ee37c56b196c0a5f32c746319b542/commands/version/README.md#--conventional-prerelease
$ npm run release -- --conventional-prerelease
```
