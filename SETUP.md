# 線上 Jupyter：Colab 與 JupyterLite

[回課程首頁](README.md) · [進入第一週](lessons/01-first-program/README.md)

使用學校電腦教室的瀏覽器，選擇 Colab 或 JupyterLite 學 Python。電腦不需安裝 Python 或開發工具。

## 第一週可直接使用 Colab

1. 開啟 [第一週 Colab 筆記本](https://colab.research.google.com/drive/1LXPag1eda66wTrA1mrwClNdxuGomTEK2)，登入 Google 帳號。
2. 選 **檔案 → 在雲端硬碟中儲存複本**（File → Save a copy in Drive），在自己的副本練習。
3. 點程式格左側 **▶** 或按 **Shift + Enter** 執行；第一次執行可能需要等待連線。
4. 修改內容後重新執行，再確認上方顯示儲存完成。登入且可編輯的雲端硬碟副本會自動儲存，也可按 **Ctrl + S**（Mac：Command + S）。
5. 下課前可選 **檔案 → 下載 → 下載 .ipynb**，額外保留一份檔案；下週直接打開自己雲端硬碟中的副本。

Colab 左側「檔案」是執行環境的檔案區；下載這份筆記本請使用上方「檔案」選單。程式執行狀態可能在連線結束後清除，下次使用時依順序重新執行。

**以下操作適用於 JupyterLite；兩種方式擇一即可。**

## JupyterLite 上課前準備

- 可連網、具有鍵盤的學校電腦，瀏覽器允許 JavaScript。
- 下載 [第一週 Notebook](lessons/01-first-program/W01_我的第一支程式.ipynb)。GitHub 檔案頁按 **Download raw file**，保留 `.ipynb` 副檔名。
- 準備學校允許的個人雲端空間或隨身碟，存放每週成果。

教師先在教室電腦確認網站可開啟、Python 核心可啟動、中文可顯示，並試過一次上傳及下載。若校內網路封鎖網站，請先與學校確認可用的線上 Jupyter 環境。

## 開啟第一週筆記本

1. 開啟 [線上 Jupyter](https://jupyter.org/try-jupyter/lab/)，等候載入。
2. 在左側檔案區按 **Upload Files**（向上箭頭），選取 `W01_我的第一支程式.ipynb`。
3. 在檔案清單雙擊筆記本。如果跳出核心選擇，選可用的 **Python** 核心，例如名稱含 **Pyodide** 的選項。
4. 點選第一個程式儲存格，按 **Shift + Enter**。看到 `你好，Python！` 就成功了。
5. 修改引號內的文字，再按 **Shift + Enter**，觀察輸出改變。

Notebook 就像一本可以執行程式的學習筆記：**Markdown 儲存格**放說明，**Code 儲存格**放 Python。程式結果出現在該格下方。雙擊文字格可編輯文字，按 **Shift + Enter** 顯示排版後的內容。

同一個程式格的指令由上往下執行；不同格子依你實際按執行的順序運作。初學時請跟著教材由上往下執行，避免跳格。

## 想自己建立一本？

1. 按左上方 **＋** 開啟 Launcher，選 **Notebook** 下的 Python 核心。
2. 在第一個 Code 儲存格輸入：

```python
print("你好，Python！")
```

3. 按 **Shift + Enter** 執行。可用工具列 **＋** 增加儲存格，從格子類型選單切換 Code 或 Markdown。
4. 在左側檔案清單右鍵點筆記本，選 **Rename**，命名為 `W01_我的第一支程式.ipynb`。

## 下課前：儲存、下載、備份

1. 按 **File → Save Notebook** 或工具列儲存圖示，先儲存目前內容。
2. 在左側檔案清單右鍵點自己的 `.ipynb`，選 **Download**。
3. 確認電腦下載資料夾中的檔案名稱及時間，再存到學校允許的個人雲端空間或隨身碟。
4. 下週先取回備份，再用 **Upload Files** 上傳，接著學習。

**按儲存不代表已存到個人雲端。** JupyterLite 預設使用瀏覽器的本機儲存空間。共用電腦可能清除資料，換電腦也不會自動帶走筆記；請每次離開前下載備份。

## 常見卡關

| 看見什麼 | 可以怎麼做 |
| --- | --- |
| GitHub 頁面不能執行程式 | 下載 `.ipynb`，上傳到線上 Jupyter |
| 格子顯示文字，沒有執行結果 | 確認該格類型是 Code，再按 Shift + Enter |
| 改了文字，結果還是舊的 | 點回剛修改的程式格，重新執行 |
| 顯示 `[*]` 很久 | 第一次啟動需等候；仍無回應時請老師協助檢查網路或核心 |
| 跳出紅色錯誤 | 檢查引號、括號、大小寫與半形符號，一次改一處 |
| 重啟核心後變數不見了 | 重啟會清除執行狀態，請由上往下重新執行必要格子 |
| 找不到上週的筆記本 | 從自己的雲端空間或隨身碟取回備份後上傳 |

如需中止長時間執行，可使用 **Kernel → Interrupt Kernel**。重啟前先儲存可保存的內容，並了解先前執行狀態會清除。

既有 `.py` 範例仍可閱讀：把檔案內的 Python 程式複製到 Code 儲存格再執行。第一週主要使用 `.ipynb`，不必另外操作終端機。

操作及儲存依據：[JupyterLite 官方使用說明](https://jupyterlite.readthedocs.io/en/latest/quickstart/using.html)。
