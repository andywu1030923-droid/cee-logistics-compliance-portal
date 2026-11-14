# CEE Logistics Compliance Portal

双语静态网页原型，覆盖塞尔维亚、匈牙利、克罗地亚、斯洛文尼亚、波黑、黑山。

## 在线访问
GitHub Pages 发布地址：https://andywu1030923-droid.github.io/cee-logistics-compliance-portal/

## 本地预览
直接打开 `index.html`，或在此目录运行：
`python -m http.server 8000`
然后打开 http://localhost:8000

## GitHub Pages 部署
仓库 Settings → Pages → Build and deployment：
1. Source 选择 Deploy from a branch。
2. Branch 选择 `main`，目录选择 `/ (root)`。
3. 点击 Save，等待 GitHub Pages 构建完成。

## 重要说明
这是可交互的第一版网站原型。当前关税表只给出HS归类检索起点，不编造未经核实的国家级完整税号税率。正式使用前需根据每个SKU的技术参数、完整税号、原产地及进口日期，在官方税则中逐项确认；环保费率和申报周期也需按实际投放市场主体及当地制度复核。内容不构成法律、税务或海关归类意见。
