# 課前準備：讓第一堂課順利開跑

[回課程首頁](README.md) · [進入第一堂](lessons/01-first-program/README.md)

建議老師或家長在上課前完成環境準備；第一堂保留時間讓學生親手建立檔案、執行與修改。

## 需要準備

- 一台有實體鍵盤的電腦。
- Python 3 與 PyCharm。參考課程使用 PyCharm 2025.2.1.1，本教材依 2025.2 文件整理；其他版本的按鈕位置可能不同。
- 下載並解壓縮這份教材。**開啟解壓縮後的資料夾，不是 ZIP 檔。**

PyCharm 是寫程式的工作桌；Python 直譯器是實際執行程式的工具。兩者都要準備好。若沒有安裝，請由老師／家長透過 [Python 官方網站](https://www.python.org/downloads/)與 [PyCharm 官方網站](https://www.jetbrains.com/pycharm/download/)完成。

## 路線 A：直接使用下載的教材

1. 啟動 PyCharm，選 **Open**，開啟教材資料夾。
2. 確認專案有 Python 3 直譯器。若顯示未設定，進入 **Settings**，搜尋 **Python Interpreter**，選取已安裝的 Python；需要新增時使用 **Add Interpreter → Add Local Interpreter**。
3. 在左側 Project 檔案清單中開啟 `lessons/01-first-program/examples/01_hello.py`。
4. 在程式編輯區按右鍵，選 **Run '01_hello'**。
5. 在 **Run** 視窗找到 `你好，Python！`。出現 `Process finished with exit code 0` 表示這次程式正常結束；那行是工具訊息，不是你寫的文字。

## 路線 B：學生親手建立自己的檔案

1. 在已開啟的專案中，右鍵點左側的專案資料夾，選 **New → Python File**。
2. 輸入名稱 `my_card`，確認產生 `my_card.py`。
3. 輸入下面一行，不要連同 Markdown 的三個反引號一起貼入：

```python
print("你好，Python！")
```

4. 在編輯區按右鍵，選 **Run 'my_card'**。
5. 改變引號內的文字，再執行一次。確認 Run 顯示的是 `my_card`，避免跑到先前的範例。

若需要全新專案，可從歡迎畫面選 **New Project → Pure Python**，選擇資料夾與可用的 Python 3，保留適合新專案的環境設定後建立。

## 常見卡關

| 看見什麼 | 先做什麼 |
| --- | --- |
| 沒有 Python interpreter／Invalid environment | 請老師確認已安裝 Python，並選到有效的直譯器路徑 |
| 改了文字，輸出仍然沒變 | 重新執行；檢查 Run 的檔名是否正確 |
| 紅色錯誤訊息 | 回編輯區檢查引號、括號與大小寫，參考第一堂的除錯表 |
| 程式一下就結束 | 這堂的 `print()` 程式顯示完就會結束，屬正常現象 |
| 不知道要在哪裡打程式 | 在 `.py` 檔的編輯區輸入，不是 Run 輸出區 |

Run 裡的停止按鈕可中止仍在執行的程式；這堂範例很快就會完成，按鈕可能變成不可用。

## 教師的課前確認

- [ ] 範例能顯示中文。
- [ ] 學生知道如何切換英文輸入、輸入半形 `()` 與 `"`。
- [ ] 第一行程式前面沒有多餘空格。
- [ ] 斷網時仍可開啟本機教材並執行範例。

熟悉終端機的人也可以在教材根目錄執行：

```sh
python3 lessons/01-first-program/examples/01_hello.py
```

Windows 若使用 Python Launcher，可將前面的 `python3` 改為 `py`。這是替代操作方式，不是第一堂必修內容。

操作依據：[PyCharm 建立與執行專案](https://www.jetbrains.com/help/pycharm/2025.2/creating-and-running-your-first-python-project.html)、[設定 Python 直譯器](https://www.jetbrains.com/help/pycharm/2025.2/configuring-python-interpreter.html)。
