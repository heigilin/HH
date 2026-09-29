# 軒儀照護院手部衛生互動教學

這個資料夾是可上傳 GitHub 的網站包。

## 檔案

- `index.html`：網站首頁
- `handwashing_training_web.mp4`：首頁濕洗手示範影片，已轉成網頁通用 H.264 格式
- `照片/`：網站引用的手部衛生照片
- `.nojekyll`：讓 GitHub Pages 直接照原始檔案提供網站
- `.gitattributes`：設定 MP4 使用 Git LFS

## 重要提醒

影片已轉為約 20 MB 的 H.264 MP4，可直接上傳 GitHub repo。

```powershell
git add index.html handwashing_training_web.mp4 照片 .nojekyll README.md
git commit -m "Add hand hygiene training site"
git push
```

## GitHub Pages

上傳後可在 repository 的 Settings -> Pages 啟用 GitHub Pages，來源選擇 `main` branch / root。
