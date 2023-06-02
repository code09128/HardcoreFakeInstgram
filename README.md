# FakeInstagram

## 仿Instagram

1. Infinite scroll 捲軸瀏覽至底載入新資料，直到 API 沒有資料
2. Pull-to-refresh下拉更新圖片
3. Error handling 呈現 retry 頁面

## 程式結構

1. UIKit programmatically
2. 使用 MVVM 架構
3. 基於 enum 建立 TableView Section 以及 Cell 的類型
4. batch update Tableview Cell
5. GCD
