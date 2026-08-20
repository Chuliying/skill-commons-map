# skill-commons map

`skill-commons` 的公開互動式 repo map。頁面呈現 workflow flow、技能 profile、
execution mode／artifact 契約、人工 Gate 與驗證邊界。

- 權威來源：[`Chuliying/skill-commons`](https://github.com/Chuliying/skill-commons)
- 部署內容：單一自足的 [`index.html`](index.html)，沒有 runtime package 或外部 asset
- 生成方式：由 source repo 的 `scripts/repo_visual.py render --source-base ...` 產生

`index.html` 是生成產物；內容變更應回到 source repo，再重新生成與驗證，避免部署 repo
成為第二份手寫真相。

## Local preview

```bash
python3 -m http.server 4173
```

開啟 <http://localhost:4173>。正式站由 Vercel production deployment 提供。
