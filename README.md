# 真实照片分类与特征训练

独立课程实验 007/03。

- 网站：[运行真实示例](https://hub-fover.github.io/Vision-Lab-007-03-Classification/)
- 源码：[GitHub](https://github.com/hub-fover/Vision-Lab-007-03-Classification)
- 课件关联：第 37–53、86–104 页。标注不同照片为 A/B，再用独立照片测试，区分拟合与泛化。

本仓库包含本实验网页、真实样例、运行时及资源来源说明，可部署到任意静态服务器。无需其他课程仓库；相机要求 HTTPS。打开即运行真实模型示例；分类/迁移使用 2 张训练照片及另一张测试照片，小样本不代表泛化能力。

本地运行：

```sh
python -m http.server 8000
```

浏览器打开 http://localhost:8000/。请通过 HTTP/HTTPS 运行，不使用 file://。

验证：`npm test` 检查随附资源 SHA-256。许可证及素材来源见 LICENSES.md、THIRD_PARTY_NOTICES.md（如适用）及各 assets 下 metadata/来源台账。
