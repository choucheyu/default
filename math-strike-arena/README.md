# 算域突擊｜Math Strike Arena

原創瀏覽器數學射擊遊戲，版本 **v1.0.1**。本版包含 Windows 觸控電腦與一般滑鼠的左鍵射擊修正。

## 直接遊玩

穩定版本：

https://rawcdn.githack.com/choucheyu/default/ae67763fb2b72b97a8d4d59bda5a6cad3d0e4c65/math-strike-arena/index.html

分支最新版：

https://raw.githack.com/choucheyu/default/math-strike-arena/math-strike-arena/index.html

首次開啟時，靜態轉譯服務可能顯示來源確認頁；確認後即可進入遊戲。

## 操作

- `W A S D`：移動
- 滑鼠：瞄準
- 滑鼠左鍵：射擊
- `R`：換彈
- `Q`：分析脈衝
- `Shift`：衝刺
- `Esc`：暫停

## 檔案結構

`index.html` 會載入同目錄的六段壓縮資料，於瀏覽器內還原為完整單檔遊戲。這種安排保留原始遊戲內容，同時讓 GitHub 連線能可靠提交大型 HTML。

原始遊戲 SHA-256：

`6bdf68a930b697e6d357c12bb9aa26e2a22bdf36ae7acccd2177b91aba3afb98`

本分支為獨立發布分支，不會修改儲存庫的 `master` 預設分支。
