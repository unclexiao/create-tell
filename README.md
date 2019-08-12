create-tell
=======
Egg 应用初始化工具，所有 egg 应用开发必须安装。

## Install

```bash
$ npm i tell-init -g
$ tell-init -h
```

## 创建 `simple` 类型的应用

```bash
$ tell-init --type simple [dest]
```

## 不输入类型可以选择

```bash
$ tell-init dest
? Please select a boilerplate type (Use arrow keys)
❯ basic - egg-boilerplate-basic
  mp - echat miniprogram app boilerplate
  rtc - real time communication app boilerplate
```

## 支持的参数

```
Usage: tell-init [dir] --type=simple

Options:
  --type          boilerplate type                                                [string]
  --dir           target directory                                                [string]
  --force, -f     force to override directory                                     [boolean]
  --template      local path to boilerplate                                       [string]
  --package       boilerplate package name                                        [string]
  --registry, -r  npm registry, support china/npm/custom, default to auto detect  [string]
  --silent        don't ask, just use default value                               [boolean]
  --version       Show version number                                             [boolean]
  -h, --help      Show help                                                       [boolean]
```

## License

[MIT](LICENSE)
