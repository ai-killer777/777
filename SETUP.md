# 3 分鐘設定 Codex

1. 使用 Codex Desktop / Codex CLI 選擇自己的網站專案資料夾（或新建空 repo）。
2. 將本套件 `project/` 裡的所有 .md 檔放到該 repo 根目錄；若已有 AGENTS.md，先合併內容，不要覆寫。
3. 若希望「每個」Codex 專案都使用這套創辦人風格，可將 `global/AGENTS.md` 複製到 `~/.codex/AGENTS.md`（Windows 通常是 `%USERPROFILE%\.codex\AGENTS.md`）。若已有檔案，先合併。
4. 使用 Git 版控保存文字、程式碼與決策；不要提交資料庫備份、客戶個資、明文密碼、API keys 或 .env。
5. 在 Codex 首個對話貼上 `project/START_PROMPT.md` 的內容；優先提交現有 repo 或備份以便唯讀稽核。
6. Codex 的審批設定建議保留人工批准；未經同意不可部署、付款、改正式環境或執行不可逆指令。

`AGENTS.md` 是 Codex 可自動讀取的指令檔；其他 Markdown 是你/專案的可持續記憶與作業資料，不是自動生效的系統特權。若帳號或版本介面不同，以實際 Codex 設定為準。
