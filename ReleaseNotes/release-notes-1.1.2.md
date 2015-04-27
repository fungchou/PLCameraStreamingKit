# PLCameraStreamingKit Release Notes for 1.1.2

## 内容

- [简介](#简介)
- [问题反馈](#问题反馈)
- [记录](#记录)
	
## 简介

PLCameraStreamingKit 1.1.2 为 iOS 开发者提供直播推流 SDK。

## 问题反馈

当你遇到任何问题时，可以通过在 GitHub 的 repo 提交 ```issues``` 来反馈问题，请尽可能的描述清楚遇到的问题，如果有错误信息也一同附带，并且在 ```Labels``` 中指明类型为 bug 或者其他。

[通过这里查看已有的 issues 和提交 Bug](https://github.com/pili-io/PLCameraStreamingKit/issues)

## 记录

### 系统

- 添加了系统分类，便于在更复杂的功能添加后接口也能保持逻辑的清晰。
- 添加了对屏幕常亮的支持。默认情况下是开启的，你也可以根据自己的需求关闭。这个开关在开始推流时起效，关闭推流时恢复为用户自己的设定。

### 视频源

- 拆分了视频源分类，便于在更复杂的功能添加后接口也能保持逻辑的清晰。

### 音频源

- 拆分了音频源分类，便于在更复杂的功能添加后接口也能保持逻辑的清晰。

### 编码

- 添加了用户自定义视频尺寸的支持。可以通过初始化不同的配置对象来实现你想要的效果。

### 其他

- 添加了固化视频截图为图片的方法。方便你获取视频截图。