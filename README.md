# 🐍 高一 Python 自主學習

**每週一小步，用程式完成自己的小作品。**

適合高中一年級上學期、完全沒有程式經驗的學生。使用學校電腦教室，透過線上 Jupyter 學習 Python，教材採繁體中文、生活例子與短任務。

- **期間：22 週，每週 1 節，約 50 分鐘。**
- **第 6、10、12、16、22 週停課**，實際學習 17 次，共 850 分鐘。
- **目標：**理解 Python 初階語法、程式執行順序與基本邏輯，練習測試及除錯，完成一件簡易作品。
- **環境：**透過瀏覽器操作 Jupyter 筆記本；第一週可直接使用 [Google Colab](https://colab.research.google.com/drive/1LXPag1eda66wTrA1mrwClNdxuGomTEK2)，也可使用 [JupyterLite](https://jupyter.org/try-jupyter/lab/)。

## 📋 計畫書與學習進度

| 你需要什麼？ | 從這裡開始 |
| --- | --- |
| 學校申請用簡版計畫書 | [四項計畫書](plans/22-week-self-study-plan.md) |
| A4 列印版本 | [下載計畫書 PDF](plans/高一Python自主學習計畫書_A4.pdf) |
| 22 週安排與每週成果 | [週進度表](COURSE_PLAN.md) |
| 開啟、執行與備份筆記本 | [線上 Jupyter 操作指南](SETUP.md) |

計畫書包含計畫名稱、100 字以內的內容說明、每週 20 字以內的週計畫及預期成果。PDF 為 A4 直式單頁，列印可選「A4、實際大小／100%」。

## 🚀 第一週：讓電腦說話

用 `print()` 做一張自己的「程式名片」：

```text
暱稱：星際飯糰
興趣：聽音樂
招牌技能：把問題拆小
```

**[直接在 Colab 開始第一週 →](https://colab.research.google.com/drive/1LXPag1eda66wTrA1mrwClNdxuGomTEK2)**

登入 Google 帳號後，先選 **檔案 → 在雲端硬碟中儲存複本**，再修改自己的副本。筆記本精簡為一個示範、一次除錯與一張文字名片，共 3 個程式格；所有練習都在同一本完成。點程式格左側 **▶** 或按 **Shift + Enter** 執行。

Colab 副本會儲存在自己的 Google 雲端硬碟；下課前確認儲存完成，也可選 **檔案 → 下載 → 下載 .ipynb** 備份。

[閱讀第一週學生講義](lessons/01-first-program/README.md)

**若改用 JupyterLite，請依下列步驟：**

1. 取得 [W01_我的第一支程式.ipynb](lessons/01-first-program/W01_我的第一支程式.ipynb)：在檔案頁按 **Download raw file**。也可在首頁選 **Code → Download ZIP** 並解壓縮。
2. 開啟[線上 Jupyter](https://jupyter.org/try-jupyter/lab/)，按左側檔案區的 **Upload Files** 上傳筆記本，再雙擊開啟。
3. 點選程式儲存格，按 **Shift + Enter**，看看程式會說什麼；詳細操作見 [SETUP](SETUP.md)。
4. 完成名片與反思後，儲存並下載 `.ipynb`，放到學校允許的個人雲端空間或隨身碟。

**每堂都要下載備份。** JupyterLite 主要把檔案存在目前瀏覽器中，換電腦或清除資料後，不能保證原檔仍在；按儲存不等於已同步到個人雲端。

| 第一週資源 | 用途 |
| --- | --- |
| [學生講義](lessons/01-first-program/README.md) | 50 分鐘的操作與概念說明 |
| [Jupyter 筆記本](lessons/01-first-program/W01_我的第一支程式.ipynb) | 精簡說明、1 個示範、1 次除錯與1 張名片 |
| [Colab 線上版](https://colab.research.google.com/drive/1LXPag1eda66wTrA1mrwClNdxuGomTEK2) | 先存到自己的雲端硬碟，再開始操作 |
| [作品完成條件](lessons/01-first-program/exercises.md) | 對照同一張名片，不另加練習 |
| [紙本學習紀錄](lessons/01-first-program/worksheet.md) | 需要紙本時才填，不重抄程式 |
| [教師指引](lessons/01-first-program/teacher-guide.md) | 協助設備準備與引導 |
| [參考解答](lessons/01-first-program/solutions/README.md) | 完成後比較做法 |

## 第一週的完成線

- [ ] 能開啟 Notebook，執行及修改程式儲存格。
- [ ] 用 `print()` 顯示至少三行自己設計的文字。
- [ ] 能說明程式順序與 `#` 註解，修正一次引號或括號錯誤。
- [ ] 完成簡短反思，下載並保存本週 `.ipynb`。

GitHub 用來閱讀及下載教材，程式在 Jupyter 執行。儲存庫已公開，學生可直接閱讀及下載教材；學生不需要學 Git 才能開始。

## 🎒 第二週：變數與角色補給站

讓程式記住角色資料、計算購買花費，再交換兩件裝備。內容包含變數命名、重新指定、四則運算、常數與變數交換。

**[在 Colab 開始第二週 →](https://colab.research.google.com/github/AndyFeng0802/high-school-python/blob/main/lessons/02-variables/W02_%E8%AE%8A%E6%95%B8%E8%88%87%E8%A7%92%E8%89%B2%E8%A3%9C%E7%B5%A6%E7%AB%99.ipynb)**

[課程導覽](lessons/02-variables/README.md) · [下載 Notebook](lessons/02-variables/W02_變數與角色補給站.ipynb) · [教師指引](lessons/02-variables/teacher-guide.md)

前言 3 分鐘，中間每個重點 5–10 分鐘，最後結論 2 分鐘，共 50 分鐘。18 格筆記、6 個程式格串起同一個情境，完成一張角色補給資料卡；沒有額外闖關或重複作業。

## 教材狀態

已提供 **22 週規劃、簡版申請書與 A4 PDF，以及第一、二週完整教材**。其餘 15 次學習目前列出進度與任務，詳細教材尚未製作。第 21 週完成成果展示，停課週不安排必要作業。

[設計依據與參考資料](REFERENCES.md) · [驗證紀錄](VALIDATION.md)
