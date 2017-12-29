## 代码检查基本配置

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

如果怕自己写不好格式的代码
```dash
#  npm > 5.2.0
npx onchange '**/*.js' -- npx prettier --write {{changed}}

```
