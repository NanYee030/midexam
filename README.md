# 1142 Web 程式設計 - 期中考：簡易會員系統

這是一個基於 Flask 框架開發的簡易會員管理系統。具備會員註冊、登入、公告瀏覽以及管理員專屬的會員管理功能（包含編輯使用者資料）。

## 功能特點
- **會員系統**：支援註冊與登入功能。
- **身分驗證**：區分一般使用者與管理員（admin）。
- **權限控管**：僅限管理員可進入「會員管理」頁面。
- **資料持久化**：使用 `users.json` 存儲會員資訊。
- **響應式設計**：採用 Pico CSS 打造簡潔的 UI 介面。

## 技術棧
- **後端**: Python 3.14 (Flask)
- **前端**: Jinja2 Template, Pico CSS
- **資料格式**: JSON

## 安裝與運行
1. **複製專案**：
   ```bash
   git clone <你的專案網址>
   cd 1142midexam


安裝依賴：
Bash
pip install -r requirements.txt
執行程式：

Bash
python midtest.py
存取網址：
開啟瀏覽器前往 http://127.0.0.1:5000

👤 預設管理員帳號
Email: admin@example.com

Password: admin123

---

## 2. .gitignore
這個檔案用來告訴 Git 哪些檔案「不要」上傳到 GitHub（例如虛擬環境或快取）。

```text
# Python 快取
__pycache__/
*.py[cod]
*$py.class

# 虛擬環境
venv/
env/
ENV/

# 編輯器設定
.vscode/
.idea/

# 作業系統暫存
.DS_Store
Thumbs.db
