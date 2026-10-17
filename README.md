# 水色心动韩系手帐体

用于酒馆字体设置的原始 WOFF2 字体和 CSS 导入代码。

## 导入字体

在「字体 → 添加新字体」中粘贴以下代码：

```css
@font-face {
  font-family: "ShuiseXindong";
  src: url("https://cdn.jsdelivr.net/gh/Xiaxiii/woff2@main/shuise-xindong.woff2") format("woff2");
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}

body {
  font-family: "ShuiseXindong", sans-serif;
}
```

自定义字体名称填写 `ShuiseXindong`，点击「添加」，选中该字体并开启字体功能。

字体文件为 `shuise-xindong.woff2`，来自上传的「水色心动韩系手帐体.woff2」，未作转换。

如果无法访问 jsDelivr，可将 `src` 中的地址替换为：

```text
https://raw.githubusercontent.com/Xiaxiii/woff2/main/shuise-xindong.woff2
```

## 古早小兔叽打字机（重新编码版）

旧 WOFF/WOFF2 文件及对应导入 CSS 已从当前分支删除。以下为此次上传文件解码、重新编码后的版本。

在「字体 → 添加新字体」中粘贴：

```css
@font-face {
  font-family: "GuzaoRabbitRebuilt";
  src: url("https://cdn.jsdelivr.net/gh/Xiaxiii/woff2@main/guzao-rabbit-rebuilt-v1.woff2") format("woff2");
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}
body {
  font-family: "GuzaoRabbitRebuilt", sans-serif;
}
```

自定义字体名称填写 `GuzaoRabbitRebuilt`。在酒馆内删除先前添加的 `GuzaoXiaotuji`、`GuzaoXiaotujiWoff` 条目，然后添加并选中这个新条目。

此版本重新生成了字体内部名称，保留了字形、字符映射、字宽及原有版权和许可信息。浏览器加载已验证；具体酒馆插件和设备上的显示效果仍需实测。

若需要 GitHub 原始文件地址：

```text
https://raw.githubusercontent.com/Xiaxiii/woff2/main/guzao-rabbit-rebuilt-v1.woff2
```
