# 星影导航站

`home.starshadow.cc` 的静态导航站源码。

## Cloudflare Pages

- Build command: 留空
- Build output directory: `public`
- Custom domain: `home.starshadow.cc`

所有服务入口都在 `public/index.html` 中维护。

## 发布命令

```powershell
git init -b main
git add .
git commit -m "Initial home navigation site"
git remote add origin https://github.com/starshadows/starshadow-home.git
git push -u origin main
```

如果需要先走 Direct Upload：

```powershell
npx wrangler pages deploy public --project-name starshadow-home --branch main
```
