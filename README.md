# 作業四-桌面單機版電商平台

這是一個以 **Java Swing + JDBC + MVC/DAO 架構** 開發的桌面電商平台，完整涵蓋從前台購物到後台管理的流程。

---

## 功能

### 前台
- 商品瀏覽與分類
- 訪客購物（免登入即可下單）
- 會員註冊、登入（密碼雜湊處理）
- 購物車與結帳流程
- 訂單查詢與取消訂單

### 後台
- 角色導向介面：會員 / 店員 / 店長
- 商品、會員、員工的 CRUD 功能
- 訂單管理與庫存控管
- 銷售報表（JFreeChart）
- 匯出 Excel / Word 文件（Apache POI）

---

## 系統架構

- **前端**：Java Swing (桌面 GUI)
- **後端**：JDBC + MySQL
- **設計模式**：MVC、DAO、Service Layer
- **報表**：JFreeChart、Apache POI
- **安全性**：SHA-256 密碼雜湊

專案目錄結構：
```
├─ src/
│ ├─ controller/
│ ├─ dao/
│ │ └─ impl/
│ ├─ model/
│ ├─ service/
│ │ └─ impl/│ 
└─└─ util/
```



