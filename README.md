# Clear Book Rules

Clear Book 规则市场 — 社区规则仓库。

## 使用

在线访问 [Clear Book](https://hrk666666.github.io/clearbook/)，进入「市场」页浏览和安装规则包。

## 规则包格式

```json
{
  "id": "规则包ID",
  "name": "规则包名称",
  "author": "作者",
  "desc": "描述",
  "version": "1.0.0",
  "rules": [
    {"pattern": "正则表达式", "flags": "gi"}
  ],
  "homophones": [
    {"dirty": "混淆词", "clean": "正确词"}
  ]
}
```

## 提交规则

1. Fork 本仓库
2. 添加规则包 JSON 文件
3. 更新 `index.json`
4. 提交 Pull Request

或在 Clear Book 应用内创建规则包后通过 GitHub Issue 提交。

## 已有规则包

| 规则包 | 描述 |
|--------|------|
| novel-ads | 小说广告清理 |
| chinese-novel | 中文小说增强 |
| txt-compact | TXT 极致压缩 |
| homophone-ads | 广告同音字混淆 |

## 许可证

AGPL-3.0
