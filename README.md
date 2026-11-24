# Apex GenSen Round

Apex GenSen Round 是基于源泉圆体 2.100 TW（月版）制作的圆体子集，包含 Regular（400）和 Bold（700）两个字重。两个字重各收录 479 个 Unicode 字符，其中有 361 个汉字，另有拉丁字母、数字和常用标点。覆盖范围以原界面预览使用的字符为准，适合选定文案与界面标签。

> 开始　整理片段　统计数据　字体预览　ABC abc 0123456789

## 下载和使用

从 [GitHub Releases](https://github.com/LilycleHeart/apex-gensen-round/releases) 下载压缩包。桌面应用可直接安装 `fonts/` 下的 `.otf` 文件。网页可使用原版 `.woff` 文件，按下列示例配置两个字重，并设置系统字体作为缺字回退。

```css
@font-face {
  font-family: 'Apex GenSen Round';
  src: url('./fonts/Apex-GenSen-Round-Regular.woff') format('woff');
  font-weight: 400;
  font-display: swap;
}

@font-face {
  font-family: 'Apex GenSen Round';
  src: url('./fonts/Apex-GenSen-Round-Bold.woff') format('woff');
  font-weight: 700;
  font-display: swap;
}

body {
  font-family: 'Apex GenSen Round', system-ui, sans-serif;
}
```

## 字体来源与许可

原版 WOFF 经过裁字和重命名。OTF 从这两个 WOFF 转出，保留全部轮廓和字宽，并统一了桌面字体名称和粗体样式标记。完整字库可从上游下载。[源泉圆体](https://github.com/ButTaiwan/gensen-font)

上游源泉圆体由 ButTaiwan 维护，源自思源黑体。字体随附 SIL Open Font License 1.1 及上游版权声明。[OFL.txt](OFL.txt)
