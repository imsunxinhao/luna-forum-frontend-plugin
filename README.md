# Luna Forum UI

## 描述

Luna Forum UI 是 Luna Forum 的前端插件，使用 Fluent UI Web Components 构建。

## 注意

本插件已经过时，不建议继续使用。

原因：

- Fluent UI Web Components 存在许多漏洞和未实现的功能特点；
- 自行实现的功能大多违背 Fluent UI 设计理念，难以维护；
- 前后端融合易产生安全问题；
- MPA 不适合现代 Web 开发。

最后适配于 Luna Forum 提交 `4eb8466`。

在 `4eb8466` 之后的版本中，Luna Forum 将移除所有的相关支持，包括但不限于 i18n 和表单式提交。

## 安装

将插件解压到 plugins/ 目录下，在 `config.json` 中的 `plugins` 数组中添加以下内容：

```json
{
    "name": "frontend",
    "main": "./plugins/frontend/",
    "deps": []
}
```

重启 Luna Forum 即可应用更改。