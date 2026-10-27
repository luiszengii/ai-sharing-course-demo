# AI 分享会 · 第一讲开场演示

在线展示：[第一讲开场 1—13](https://luiszengii.github.io/ai-sharing-course-demo/)

当前固定为 **v0.1**：原来的柔和起步、按内容配置的分段时长与渐缓收尾。

这个仓库仅保存发布用的自包含 HTML 与部署配置。`index.html` 是 v0.1 固定离线快照的原样副本，图片、样式和脚本全部内嵌，没有重新编译或修改动画。

## 操作

- 滚轮 / 触控板：连续推进与回退。
- 左右方向键：前后切换关键帧。
- Home / End：回到开头 / 到达结尾。

## 发布与版本校验

GitHub Actions 在发布前校验 `index.html` 的 SHA-256；不符合固定版本即停止发布。`version.json` 记录当前版本及其校验值。

v0.1 SHA-256：

```text
3bb96eb0955604ad8cd75790398f9a159933d57d7260585bdafe41111d69e88e
```

第三方图片与组件保留原有权利、署名和许可，来源记录保留在 HTML 的 `asset-credits` 元数据中。
