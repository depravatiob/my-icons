## 图标清单（index）
https://cdn.jsdelivr.net/gh/depravatiob/my-icons@main/index.json

## CDN 基础地址
https://cdn.jsdelivr.net/gh/depravatiob/my-icons@main/

## 示例（PNG）
- https://cdn.jsdelivr.net/gh/depravatiob/my-icons@main/icons/png/xxx.png

## 使用示例
### HTML
<img src="https://cdn.jsdelivr.net/gh/depravatiob/my-icons@main/icons/png/xxx.png" width="24" height="24" />

### CSS
.icon-xxx {
  background-image: url("https://cdn.jsdelivr.net/gh/depravatiob/my-icons@main/icons/png/xxx.png");
  width: 24px;
  height: 24px;
  background-size: contain;
  background-repeat: no-repeat;
}

## 推荐拉取方式（自己用）
1) 先拉取图标清单：
https://cdn.jsdelivr.net/gh/depravatiob/my-icons@main/index.json

2) 最终图标 URL = base + icons[name]
示例：
https://cdn.jsdelivr.net/gh/depravatiob/my-icons@main/icons/png/discord.png

## 维护/更新流程（自己用）
1) 把新图标放到：icons/png/
2) 更新根目录 index.json（添加/修改 icons 映射）
3) 直接使用 main 链接（无需发新版本）：
- index: https://cdn.jsdelivr.net/gh/depravatiob/my-icons@main/index.json
- base:  https://cdn.jsdelivr.net/gh/depravatiob/my-icons@main/
