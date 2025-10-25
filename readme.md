# 表情包仓库概述

欢迎来到表情包仓库！这里是一个收集各种精美表情包的聚集地，为您的聊天、社交和表达情感提供了丰富多彩的选择。无论您需要表达的是开心、难过、惊讶还是其他情感，这里都有一个适合的表情等待着您。

## 介绍

本仓库致力于收集各种类型的表情包，从经典的静态表情到生动的动态表情，以及各种主题和风格的表情，涵盖了丰富的内容，满足了不同用户的需求。

## 表情包列表

以下是本仓库目前收集的一些表情包，欢迎随时查看和使用：

- **线条小狗动态表情包**：这个系列包含了一系列生动有趣的线条小狗动态表情，总共 43 种，每一种都展现了线条小狗的可爱与机智。无论是表达情感、分享心情，还是幽默地传递讯息，这些表情都是绝佳的选择。
- **Blobcat 动态表情包**：这个系列包含了多种生动有趣的 Blobcat 动态表情，总共 54 种，每一种都展现了 Blobcat 的可爱和俏皮。无论是表达情感、分享心情，还是幽默地传递讯息，这些表情都是绝佳的选择。
- **bilibili动态表情包**：这个系列包含了多种独特而有趣的 bilibili 动态表情，展现了各种可爱和有趣的角色。无论您想要表达喜悦、惊讶、困惑还是其他情绪，这些表情都能帮助您传达出您的心情。总共包含了多种风格，每一种都充满了个性和魅力。

## 如何使用

您可以通过以下方式使用本仓库中的表情包：

1. **浏览表情包列表**：在本仓库中查看表情包列表，选择您喜欢的表情。
2. **复制表情链接**：复制您喜欢的表情的链接地址，并在需要的地方粘贴使用。
3. **引导他人使用**：将本仓库链接分享给朋友，让更多人分享表情的乐趣。

您也可以在twikoo中直接调用owo.json进行使用：

原仓库表情包调用：

```
https://fastly.jsdelivr.net/gh/willow-god/owo/.json/twikoo-emoji.json
```

本仓库表情包调用：
```
https://fastly.jsdelivr.net/gh/ljxme/owo/.json/twikoo-emoji.json
```
或者：
```
https://xget.artemisia.icu/gh/ljxme/owo/raw/refs/heads/main/.json/twikoo-emoji.json
```
最新版调用（无需等待刷新）：
```
https://fastly.jsdelivr.net/gh/ljxme/owo@main/.json/twikoo-emoji.json?v=2
```

### Waline 评论系统

本项目现已支持 Waline 评论系统！您可以在 Waline 中使用这些精美的表情包。

**使用方法：**

在 Waline 初始化时添加 `emoji` 选项：

```javascript
Waline.init({
  el: '#waline',
  serverURL: '您的 Waline 服务端地址',
  emoji: [
    'https://fastly.jsdelivr.net/gh/ljxme/owo/.json/waline/blobcat/',
    'https://fastly.jsdelivr.net/gh/ljxme/owo/.json/waline/linedog/',
    'https://fastly.jsdelivr.net/gh/ljxme/owo/.json/waline/bilibili/',
    'https://fastly.jsdelivr.net/gh/ljxme/owo/.json/waline/heybox_cube/',
    'https://fastly.jsdelivr.net/gh/ljxme/owo/.json/waline/heybox_heniang/',
  ]
});
```

**支持的表情包系列：**
- **可爱猫** (blobcat) - 54个PNG表情
- **线条狗** (linedog) - 43个GIF动态表情  
- **小电视** (bilibili) - 21个PNG表情
- **小黑盒方块** (heybox_cube) - 78个PNG表情
- **小黑盒盒娘** (heybox_heniang) - 24个PNG表情

每个表情包都包含完整的 `info.json` 配置文件，符合 Waline 官方规范。

## 贡献

如果您有自己制作或发现的精美表情包，并愿意分享给大家，欢迎提交 Pull Request 或者提出 Issue。我们欢迎各种形式的贡献，一起让这个仓库变得更加丰富和有趣！

## 致谢

感谢所有为本仓库贡献过表情包的创作者和贡献者，也感谢所有使用和支持本仓库的用户！

