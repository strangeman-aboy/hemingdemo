# 龙膜全球臻选店获客与门店经营方案 Demo

这是为 **上海龙膜全球臻选店（绮源空间店）** 制作的静态演示网页，用于向客户展示从获客诊断、内容获客、车主转化页到后续门店经营看板的完整方案。

## 在线预览

- GitHub 仓库：[strangeman-aboy/hemingdemo](https://github.com/strangeman-aboy/hemingdemo)
- GitHub Pages 预期地址：[https://strangeman-aboy.github.io/hemingdemo/](https://strangeman-aboy.github.io/hemingdemo/)

如果 GitHub Pages 地址暂时显示 404，请在仓库的 `Settings > Pages` 中把发布来源设置为 `GitHub Actions`，然后等待部署完成。

## 页面内容

网页按照客户沟通顺序组织：

1. **项目定位**：先解决获客，再延伸到跟进、交付和经营。
2. **AI 搜索 / GEO 诊断**：检查门店在 AI 搜索、地图、点评、本地内容里的可见度。
3. **门店优势资产化**：把授权、案例、质保、施工流程、客户评价整理成可被搜索和销售调用的资料。
4. **多平台获客**：围绕小红书、视频号、抖音、大众点评 / 地图等入口说明内容怎么发、线索怎么接、AI 怎么参与。
5. **车主视角购买页**：模拟车主打开页面后如何理解痛点、方案、证据、对比、保障和预约路径。
6. **后续全场景能力**：客户量起来后，再扩展到客服、销售跟单、工单生产和经营复盘。
7. **门店经营看板**：展示老板、销售、客服、工厂各角色如何从同一个经营大脑里拿到提醒和建议。

## 本地预览

这是纯静态页面，不需要安装依赖。直接打开 `index.html` 即可预览。

也可以在项目目录启动本地服务：

```bash
python -m http.server 5173
```

然后访问：

```text
http://127.0.0.1:5173/index.html
```

## 文件结构

```text
.
├── index.html
├── styles.css
├── script.js
├── assets/
│   ├── cool-ai-logo-light-cropped.png
│   ├── cool-ai-logo.png
│   └── cool-symbol.png
└── .github/workflows/deploy-pages.yml
```

## 部署说明

项目已经配置 GitHub Pages 自动部署流程：

- 每次推送到 `main` 分支会触发 `.github/workflows/deploy-pages.yml`
- 部署产物为仓库根目录下的静态文件
- 首次使用时，需要仓库开启 GitHub Pages，并选择 `GitHub Actions` 作为发布来源
