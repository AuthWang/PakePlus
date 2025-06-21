# 图片资源目录

此目录用于存放飞锐云OBS定时推流插件的图片资源。

**注意：** 图片实际存放位置为 `public/Image` 目录，此文件仅作说明用途。

## 当前可用的图片文件

- `obs-logo.png` - OBS Logo (34KB)
- `logo.svg` - 飞锐云Logo (14KB)
- `icon.ico` - 应用图标 (26KB)

## 支持的图片格式

- PNG (推荐)
- JPG/JPEG
- SVG
- WebP
- ICO

## 建议的图片文件

### 当前已有
- `obs-logo.png` - OBS Logo
- `logo.svg` - 飞锐云Logo
- `icon.ico` - 应用图标

### 可选添加
- `banner.png` - 横幅图片 (1200x300px)
- `background.jpg` - 背景图片

## 使用方法

在Vue组件中使用 `@image` 别名引用图片：

```vue
<template>
  <img src="@image/obs-logo.png" alt="OBS Logo" />
  <img src="@image/logo.svg" alt="飞锐云Logo" />
</template>
```

## 注意事项

1. 图片文件名建议使用小写字母和连字符
2. 图片大小建议控制在合理范围内，避免影响加载速度
3. 支持透明背景的PNG格式
4. 建议提供多种尺寸的图片以适应不同场景

## 路径别名配置

项目已配置以下路径别名：

- `@image` - 指向 `public/Image` 目录
- `@public` - 指向 `public` 目录
- `@` - 指向 `src` 目录 