# API 文件

## API 概述
本文件說明系統提供的所有 API 介面。

## 認證機制
- API 金鑰認證
- OAuth 2.0
- JWT Token

## API 端點
1. [使用者管理 API](./user-management.md)
2. [資源管理 API](./resource-management.md)
3. [排程管理 API](./scheduling.md)
4. [報表 API](./reporting.md)

## 錯誤代碼
| 代碼 | 說明 | 處理方式 |
|-----|------|---------|
| 400 | 請求錯誤 | 檢查請求參數 |
| 401 | 未授權 | 確認認證資訊 |
| 403 | 禁止訪問 | 確認使用權限 |
| 500 | 伺服器錯誤 | 聯繫系統管理員 |