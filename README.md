# ChronoGuess 台南歷史全景小遊戲

這是一個可直接部署到 GitHub Pages 的靜態網站。入口檔是 `index.html`，會直接開啟 `chrono-guess.html`。

## 本機預覽

```sh
python3 -m http.server 8765
```

然後打開 `http://localhost:8765/`。

## GitHub Pages 部署

1. 在 GitHub 建立一個新的 public repository。
2. 將這個資料夾內的檔案推到 repository 的 `main` branch。
3. 到 repository 的 `Settings` → `Pages`。
4. 在 `Build and deployment` 選 `Deploy from a branch`。
5. Branch 選 `main`，folder 選 `/(root)`，按 `Save`。
6. 等 GitHub Pages 部署完成後，網址會是 `https://你的帳號.github.io/repository-name/`。

如果 repository 名稱是 `你的帳號.github.io`，網址會是 `https://你的帳號.github.io/`。
