# 項目簡介

此專案是本人用Android Studio開發的簡單計算器，這個計算器功能為括號的加減乘除多項式計算！

### "activity_main.xml"部分展示  
Android Studio開發當中的版面是".XML"的檔案格式，我這裡主要使用linear layout來進行布局，各個區塊大小依權重進行分配。而在分配每個按鈕時會將左右空出10dp的距離，導致那些較大的按鈕至中後在布局上會差個幾dp。未來若優化會考慮grid layout與linear layout交叉使用。

<p align="center">
  <img src="https://github.com/xuexiahanmei/Mycalculator/blob/master/doc/pic/docpic1.png" width="550">
</p>

### "Main_Activity.java"部分展示
在GitHub上建立一個新的存儲庫，這是你要上傳資料夾的地方。你可以在GitHub網站上的首頁上找到「New」按鈕來創建新存儲庫。
```xml
    protected void onCreate(Bundle savedInstanceState) {

      ...

        // 設置數字按鈕的點擊監聽器
        for (int i = 0; i <= 9; i++) {
            int buttonId = getResources().getIdentifier("btn_" + i, "id", getPackageName());
            Button numberButton = findViewById(buttonId);
            numberButton.setOnClickListener(new CalculatorClickListener());
        }

      ...

    }
```