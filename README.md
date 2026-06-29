# LILI 拒馬訂購網站 — liliobject.com

立立(LILI)拒馬產品的訂購單頁網站。單一自包含 HTML,以 GitHub Pages 部署。

## 檔案
- `index.html` — 網站本體(含產品規格、價格試算、出貨/運費資訊、訂購表單)
- `CNAME` — GitHub Pages 自訂網域設定(liliobject.com)
- `.nojekyll` — 讓 GitHub Pages 直接服務靜態檔,不跑 Jekyll

## 更新方式
用最新版 HTML 覆蓋 `index.html`,然後:
```bash
git add -A && git commit -m "update site" && git push
```
推上去後 GitHub Pages 會自動重新部署。

## 部署步驟與 DNS
見 `部署指南.md`。
