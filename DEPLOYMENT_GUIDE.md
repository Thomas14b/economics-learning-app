# 經濟學概念學習應用部署說明

## 📁 文件說明
本目錄包含以下文件：
1. `index.html` - 主要應用界面（繁體中文版）
2. `concepts.json` - 經濟學概念數據庫（繁體中文）

## 🚀 快速部署方法

### 方法一：GitHub Pages（推薦，永久免費）
最簡單的部署方式，只需幾個步驟：

**步驟：**
1. 訪問 https://github.com 並登錄/註冊
2. 點擊右上角「+」->「New repository」
3. 填寫倉庫名稱：`economics-learning-app`
4. 選擇「Public」（公開）
5. 點擊「Create repository」
6. 在倉庫頁面，點擊「Uploading an existing file」
7. 將本目錄的兩個文件（index.html和concepts.json）拖拽上傳
8. 點擊「Commit changes」
9. 進入「Settings」->「Pages」
10. 在「Source」選擇「Deploy from a branch」
11. 選擇分支「main」和文件夾「/ (root)」
12. 點擊「Save」
13. 等待幾分鐘，獲得您的URL：`https://[您的用戶名].github.io/economics-learning-app/`

### 方法二：Vercel（最簡單，自動HTTPS）
**步驟：**
1. 訪問 https://vercel.com
2. 使用GitHub帳號登錄
3. 點擊「Add New...」->「Project」
4. 導入您的GitHub倉庫（或直接拖拽文件上傳）
5. 點擊「Deploy」
6. 獲得URL如：`https://economics-learning-app.vercel.app`

### 方法三：Netlify（功能豐富）
**步驟：**
1. 訪問 https://app.netlify.com
2. 使用GitHub帳號登錄
3. 拖拽本目錄文件到上傳區域
4. 獲得URL如：`https://[隨機名稱].netlify.app`

## 📱 在飛書中使用

部署完成後，在飛書中使用的方法：

### 方式一：直接分享鏈接
1. 複製您的部署URL
2. 在飛書聊天中粘貼發送
3. 點擊鏈接即可訪問

### 方式二：添加到工作台
1. 在飛書工作台點擊「+」
2. 選擇「添加網頁應用」
3. 填寫：
   - 應用名稱：經濟學概念學習
   - 應用圖標：可上傳自定義圖標
   - 應用鏈接：您的部署URL
4. 點擊「確定」添加到工作台

### 方式三：創建群快捷方式
1. 在飛書群設置中
2. 選擇「群機器人」或「群應用」
3. 添加網頁應用鏈接
4. 設置快捷訪問

## 🔧 技術注意事項

1. **跨域問題**：確保concepts.json與index.html在同一域名下
2. **HTTPS**：現代瀏覽器要求HTTPS，上述平台都自動提供
3. **瀏覽器兼容**：
   - Chrome 50+ ✓
   - Firefox 45+ ✓  
   - Safari 10+ ✓
   - Edge 79+ ✓

4. **語音功能**：需要瀏覽器支持Web Speech API
   - Chrome/Edge：完全支持
   - Firefox/Safari：部分支持

## 🛠️ 維護與更新

### 更新應用內容：
1. 修改本地文件
2. 重新上傳到部署平台
3. 平台會自動重新部署

### 添加新概念：
1. 編輯concepts.json文件
2. 按照現有格式添加新概念
3. 確保所有中文使用繁體字
4. 重新部署

## ❓ 常見問題

### Q1：頁面打開空白？
檢查瀏覽器控制台（F12）是否有錯誤，確保concepts.json路徑正確。

### Q2：發音功能不工作？
- 確保使用HTTPS
- 檢查瀏覽器是否支持SpeechSynthesis
- 嘗試使用Chrome瀏覽器

### Q3：如何備份數據？
定期下載concepts.json文件到本地備份。

### Q4：可以自定義樣式嗎？
可以，編輯index.html中的CSS部分。

## 📞 支持與幫助

如需技術支持：
1. 查看平台文檔
2. 在GitHub創建Issue
3. 聯繫平台技術支持

---
部署完成後，您就可以在飛書中分享和使用這個經濟學概念學習應用了！
