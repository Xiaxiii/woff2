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
