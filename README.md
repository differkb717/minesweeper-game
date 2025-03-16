踩地雷 Minesweeper 遊戲
項目簡介
這是一個使用 HTML、CSS 和 JavaScript 實現的經典踩地雷遊戲。玩家需要在不踩到地雷的情況下，揭示所有安全的格子。遊戲提供多種難度、計時功能和統計數據，適合休閒娛樂或學習前端開發。

功能特色
多種難度選擇：
初級：9x9 格，10 個地雷
中級：16x16 格，40 個地雷
高級：24x24 格，99 個地雷
模式切換：
Mine Mode：點擊格子揭示內容
Flag Mode：標記或取消標記地雷旗子
計時器：記錄遊戲進行時間
旗標計數：顯示剩餘地雷數（總數 - 已標記數）
統計數據：記錄最佳完成時間和平均完成時間，儲存在瀏覽器本地
操作說明：內建「How to Play」按鈕，彈出玩法說明
技術棧
HTML：用於頁面結構
CSS：負責遊戲介面樣式
JavaScript：實現遊戲邏輯、事件處理和本地存儲（localStorage）

安裝與運行
方法 1：本地運行
下載 Minesweeper2.html 文件到你的電腦。
打開文件所在資料夾，雙擊 Minesweeper2.html，即可在瀏覽器中啟動遊戲。

使用說明
選擇難度：遊戲開始前，從下拉選單選擇初級、中級或高級。
切換模式：
點擊「Mine Mode」按鈕，進入揭示模式，點擊格子揭示內容。
點擊「Flag Mode」按鈕，進入標記模式，點擊格子標記或取消旗子。
遊戲目標：揭示所有非地雷格子即獲勝。
失敗條件：點到地雷，遊戲結束。
重新開始：點擊「重新開始」按鈕，重置遊戲。
統計數據
遊戲會自動儲存當前難度的最佳完成時間和平均完成時間。
數據儲存在瀏覽器的 localStorage 中，清除瀏覽器緩存會重置數據。
注意事項
請確保你的瀏覽器啟用了 JavaScript 和 localStorage。
若瀏覽器不支援這些功能，遊戲可能無法正常運行，建議使用最新版本的 Chrome、Firefox 或 Edge。
