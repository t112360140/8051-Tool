# 8051 Tool

這是一個8051的工具網站，可以將8051的程式進行組譯、連結並下載至實驗板。

## 如何使用
在網頁的文字輸入框輸入程式碼，按下中間的 `＞` 按鈕，這會將程式導入DOS模擬器並用X8051組譯。

> 提示:
> - 如果啟用了 `Auto Link` ，在組譯後如果為0錯誤，將自動使用LINK4進行連結。
> - 如果啟用了 `Auto Download` ，在連結後如果為0錯誤，並且以連接UART，將會自動下載程式到實驗板。

## 依賴項
- **JS-DOS**: [Github](https://js-dos.com/)
