> ⚠️ **警告：请勿直接修改此仓库！本仓库属于镜像仓库**，由私有 monorepo `neo-idea/official-website` 自动同步发布，手动修改会被下次发布覆盖。

# Official website

Production domain: `https://tarot.zpad.app/`

## Deploy

```bash
cd Website
npx wrangler@latest deploy
```

The Worker is named `tarot-one-card-insight` and serves the static files in `public/`.
