# 链接助手 - 三击自动转换

你是否遇到过这样的情况：在浏览网页时，看到一个纯文本的URL，但它并不是一个可点击的链接？

```plain
就像这样：

https://example.org/
```

此脚本可以帮助你解决这个问题。只需在文本URL上快速连续点击三次，它就会自动转换为可点击的链接。

![Screenshot](https://s2.loli.net/2025/04/04/sWSK4QmZAuXzYfj.gif)

## 功能特性

✅ **智能触发**  
- 三次连续点击（1秒内）同一位置激活
- 10像素范围位置容差检测

✅ **精准识别**  
- 自动检测 `http://` `https://` `www.` 开头的URL
- 跳过已存在于 `<a>` 标签内的文本
- 支持多URL文本段同时转换

✅ **安全替换**  
- 非破坏性DOM操作
- 保留原始文本格式
- 自动添加 `target="_blank"` 属性

## 使用说明

1. **定位文本URL**  
   找到需要转换的纯文本URL（如：`https://example.com`）

2. **三次快速点击**  
   在文本URL位置快速连续点击三次（鼠标左键）

3. **自动转换**  
   成功转换后文本将变为蓝色可点击链接

## 配置

你可以修改脚本中的常量以满足你的需求。

```javascript
const CLICK_TIMEOUT = 1000;
const CLICK_THRESHOLD = 10;
const URL_REGEX = /(https?:\/\/[^\s<]+|www\.[^\s<]+\.[^\s<]{2,})/gi;
const STYLE = "color: #66CCFF; background: #163E64";
```
