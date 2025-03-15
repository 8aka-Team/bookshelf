# BookShelf

国内翻译 Wiki 的书架!

访问网站: https://bookshelf.8aka.org/

## 数据格式

数据定义在`bookshelf.json`,格式为 JSON

每个项目有以下属性：

| 属性键名称        | 属性值类型  | 属性值描述                  |
|--------------|--------|------------------------|
| `title`      | String | 翻译的插件名称。               |
| `url`        | String | 网站 URL 地址。             |
| `image`      | String | 网站图标,URL               |
| `note`       | String | 备注。                    |
| `translator` | String | 翻译者,特别的`unknown` 表示未知。 |
