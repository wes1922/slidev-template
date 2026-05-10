# 專題簡報模板（Slidev）

> 使用此模板製作專題簡報，推送後自動部署到網路，不需安裝任何軟體。

## 使用步驟

### 第一步：建立自己的 repo

點擊右上角的 **「Use this template」→「Create a new repository」**

- 填入 repo 名稱（例如：`my-slides`）
- 選擇 **Public**
- 點擊「Create repository」

---

### 第二步：編輯簡報內容

進入你的新 repo，點擊 `slides.md`，再點右上角的 **鉛筆圖示 ✏️**

把內容改成你的專題資料，完成後點 **「Commit changes」→「Commit changes」**

存檔後頁面會跳回 repo 首頁，這時候簡報正在背景自動編譯，請繼續下一步。

---

### 第三步：等待自動部署（約 2 分鐘）

點上方的 **「Actions」** 頁籤，會看到一筆正在執行的工作。

等到左邊圓圈變成 **綠色勾勾 ✅** 才能繼續，若是 **紅色 ✗** 請告知老師。

---

### 第四步：開啟 GitHub Pages

Actions 完成後：

1. 點 **Settings → Pages**
2. Source 選 **Deploy from a branch**
3. Branch 選 **gh-pages**，資料夾選 **/ (root)**
4. 點 **Save**

---

### 第五步：查看你的簡報

約 1 分鐘後，簡報網址為：

```
https://你的帳號.github.io/你的repo名稱/
```

---

## 投影片語法

每個 `---` 代表一張新投影片：

```markdown
---
# 這是標題

- 列點一
- 列點二

---

# 下一張投影片
```

更多語法：[Slidev 官方文件](https://sli.dev)
