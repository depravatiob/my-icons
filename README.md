# my-icons

## 图标清单（index）
https://cdn.jsdelivr.net/gh/depravatiob/my-icons@v1.0.2/index.json

## CDN 基础地址（推荐）
https://cdn.jsdelivr.net/gh/depravatiob/my-icons@v1.0.2/

## 推荐拉取方式（给其他软件/项目）
1) 先拉取图标清单：
https://cdn.jsdelivr.net/gh/depravatiob/my-icons@v1.0.2/index.json

2) 读取其中的：
- base（基础地址）
- icons（图标名 -> 相对路径）

3) 最终图标 URL = base + icons[name]
示例：
base = https://cdn.jsdelivr.net/gh/depravatiob/my-icons@v1.0.2/
icons["discord"] = icons/png/discord.png
最终：
https://cdn.jsdelivr.net/gh/depravatiob/my-icons@v1.0.2/icons/png/discord.png

## 示例（PNG）
- https://cdn.jsdelivr.net/gh/depravatiob/my-icons@v1.0.2/icons/png/xxx.png

## 使用示例
### HTML
<img src="https://cdn.jsdelivr.net/gh/depravatiob/my-icons@v1.0.2/icons/png/xxx.png" width="24" height="24" />

### CSS
.icon-xxx {
  background-image: url("https://cdn.jsdelivr.net/gh/depravatiob/my-icons@v1.0.2/icons/png/xxx.png");
  width: 24px;
  height: 24px;
  background-size: contain;
  background-repeat: no-repeat;
}
