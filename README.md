# 小白随记支持网站

这是小白随记 (Leukanote) iOS App 的支持网站，托管在 GitHub Pages 上。

## 网站地址

- 支持主页: https://leukanote.cn
- 隐私政策: https://leukanote.cn/privacy.html
- 用户协议: https://leukanote.cn/terms.html

## App Store Connect 填表建议

在 App Store Connect 提交审核时，请填写以下 URL：

| 字段 | URL |
|------|-----|
| Support URL (支持 URL) | `https://leukanote.cn` |
| Privacy Policy URL (隐私政策 URL) | `https://leukanote.cn/privacy.html` |

## 本地预览

在网站目录下运行：

```bash
python3 -m http.server 8080
```

然后在浏览器访问 http://localhost:8080

## 部署说明

1. 将本仓库设为 GitHub Pages 源（Settings → Pages → Source: Deploy from a branch → Branch: main / root）
2. 在域名服务商（阿里云/腾讯云）添加 DNS 解析：
   - 类型 A 记录：@ → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
3. 在 GitHub Pages 设置中启用 "Enforce HTTPS"
4. 等待 DNS 生效（通常 5-10 分钟）

## 文件说明

- `index.html` - 支持主页（联系信息、FAQ）
- `privacy.html` - 隐私政策
- `terms.html` - 用户协议
- `CNAME` - GitHub Pages 自定义域名配置

## 联系方式

- 邮箱: leukanote@163.com
