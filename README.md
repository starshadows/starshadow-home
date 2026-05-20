# 星影导航站

`home.starshadow.cc` 的静态导航站源码。

## Cloudflare Workers

- Static assets directory: `public`
- Worker name: `starshadow-home`
- Custom domain: `home.starshadow.cc`

所有服务入口都在 `public/index.html` 中维护。

## GitHub 发布命令

```powershell
git init -b main
git add .
git commit -m "Initial home navigation site"
git remote add origin https://github.com/starshadows/starshadow-home.git
git push -u origin main
```

## Workers 部署命令

```powershell
npx wrangler deploy
```

或安装依赖后：

```powershell
npm run deploy
```
