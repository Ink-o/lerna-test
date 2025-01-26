# 介绍
这里列举了 lerna + pnpm 的案例
# 安装依赖
```js
pnpm i
```
这里不要再写 postinstall 脚本了，详看 lerna + pnpm 整合
https://lerna.js.org/docs/recipes/using-pnpm-with-lerna
# 脚本
```js
test： lerna 运行指定任务
addPkg：lerna 添加子包
execTaskA：执行 a 包脚本
graph：查看项目中的相互依赖
```