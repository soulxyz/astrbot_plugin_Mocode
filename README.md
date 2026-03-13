# Mocode - AstrBot 在线运行代码插件

支持多种编程语言，运行于 [glot.io](https://glot.io/)

## 来源与致敬

本项目移植自 [nonebot-plugin-code](https://github.com/yzyyz1387/nonebot_plugin_code)，感谢原作者的出色工作！

## 安装

1. 在 AstrBot 插件管理面板中添加仓库地址：
   ```
   https://github.com/NumInvis/astrbot_plugin_Mocode
   ```

2. 点击安装即可

## 配置

在 AstrBot 插件配置面板中设置：
- `glot_api_url`: Glot API 地址（默认：https://glot.io/api）
- `glot_access_token`: Glot 访问令牌（从 [glot.io](https://glot.io/) 获取）
- `admin_only`: 是否仅管理员使用（默认：false）
- `timeout_seconds`: 代码执行超时时间（默认：30秒）

## 使用

### 基本用法
```
code [语言] [输入(可选)]
[代码]
```

### 示例

运行 Python Hello World：
```
/code py
print("Hello World!")
```

带输入的 Python 示例：
```
/code py 你好，世界！
print(input())
```

运行 JavaScript：
```
/code js
console.log("Hello from JavaScript!");
```

### 支持的语言

Python(py), JavaScript(js), TypeScript(ts), Java, C, C++, Go(golang), Rust(rs),
Ruby(rb), PHP, Bash(sh), Lua, Perl(pl), C#(cs), F#(fs), VB.NET(vb), R,
Scala, Swift, Kotlin(kt), Clojure(clj), Haskell(hs), Erlang(erl),
Elixir(ex), OCaml(ml), Julia, Nim, Crystal, D

## 命令

- `/code` - 运行代码
- `/mocode` - 查看帮助信息

## 致谢

- 原项目：[nonebot-plugin-code](https://github.com/yzyyz1387/nonebot_plugin_code)
- API 服务：[glot.io](https://glot.io/)

## License

MIT License
