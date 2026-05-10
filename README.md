# 專題簡報模板（Slidev）

> 使用此模板製作專題簡報，推送後自動部署到網路，不需安裝任何軟體。

## 使用步驟

### 第一步：建立自己的 repo

點擊右上角的 **「Use this template」→「Create a new repository」**

- 填入 repo 名稱（例如：`my-thesis-slides`）
- 選擇 **Public**（GitHub Pages 免費版需要是公開 repo）
- 點擊「Create repository」

### 第二步：開啟 GitHub Pages

在你的 repo 中：

1. 點擊上方的 **Settings**
2. 左側選單找到 **Pages**
3. Source 選擇 **GitHub Actions**
4. 儲存

### 第三步：編輯簡報內容

找到 `slides.md` 檔案，點擊右上角的鉛筆（✏️）直接在網頁上編輯：

- 修改標題、姓名、內容
- 每個 `---` 分隔線代表一張新的投影片
- 編輯完後按 **Commit changes**

### 第四步：等待部署

推送後約 **1～2 分鐘**，GitHub Actions 會自動部署。

完成後可在 **Settings → Pages** 看到你的簡報網址，格式為：

```
https://你的帳號.github.io/你的repo名稱/
```

---

## 投影片語法參考

```markdown
---
# 這是一張投影片的開始（用 --- 分隔）
---

# 標題

- 列點一
- 列點二

---

# 下一張投影片
```

更多語法請參考：[Slidev 官方文件](https://sli.dev)
