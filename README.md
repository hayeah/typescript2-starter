# Example TypeScript 2 Project

+ 用 TypeScript 2.0 RC 版，有不少很实用的新功能
	+ [strict null check](https://github.com/Microsoft/TypeScript/wiki/What's-new-in-TypeScript#null--and-undefined-aware-types)
	+ [control flow analysis](https://github.com/Microsoft/TypeScript/wiki/What's-new-in-TypeScript#control-flow-based-type-analysis)
	+ [tagged union types](https://github.com/Microsoft/TypeScript/wiki/What's-new-in-TypeScript#tagged-union-types)
+ 用 tslint 保证风格统一。装上 vscode 插件，实时确认风格。
+ 用 typings 为 npm 依赖包加上 API 类型文件。

# 构建和调试

TypeScript 脚本需要先转义才能调试。先运行 watch 任务去构建项目：

```js
npm run watch
```

在编辑器里打开 src/sandbox.ts 或任何其他的文件，设置断点，按 F5开始调试。
