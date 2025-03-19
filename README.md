# Rainmeter 皮肤合集

## 包含组件

### 1. 简约电量显示器 (SimpleElectricDisplay)

- 实时显示电池百分比
- 充电状态指示（闪电图标）
- 多级电量图标显示：
  - 空电池（≤5%）
  - 低电量（5%-20%）
  - 中等电量（20%-70%）
  - 高电量（>70%）
- 自适应尺寸调节（通过修改Scale变量）

### 2. 声音控制器 (SoundController)

- 可视化音量滑块调节
- 静音切换按钮
- 实时音量百分比显示
- 磨砂玻璃视觉效果
- 支持系统音量同步更新

## 安装方法

### 自动安装

1. 进入 `Skins/`目录
2. 双击对应的 `.rmskin`安装包

### 手动安装

1. 复制皮肤文件夹到Rainmeter的Skins目录
2. 刷新Rainmeter皮肤列表
3. 双击皮肤名称加载

## 自定义配置

在皮肤文件内可修改以下参数：

```ini
[Variables]
Scale=1.2  ; 整体缩放比例
MarginY=10  ; 垂直边距
SliderWidth=100  ; 滑块长度
```

## 效果预览

`SimpleElectricDisplay` 运行效果：

![电量显示截图](images/preview.png)

`SoundController` 运行效果：

![声音控制截图](images/preview2.png)

## 许可证

本项目采用 [MIT License](LICENSE) 授权
Copyright (c) 2025 hhyufan
