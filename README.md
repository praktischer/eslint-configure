# eslint-configure
easy eslint custom configure

# 安装依赖
```shell
npm install eslint @babel/eslint-parser @babel/eslint-plugin -D
```

# 使用ESLint配置
在.eslintrc.js中使用
```js
module.export = {
    extends: [
        '@praktisch/eslint-configure'
    ]
};
```

开启严格模式
```js
module.export = {
    extends: [
        '@praktisch/eslint-configure/strict'
    ]
};
```
