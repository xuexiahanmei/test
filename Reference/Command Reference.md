## 初始化一個新的 Git 儲存庫。  
這個命令會在你當前的目錄下創建一個新的 .git 目錄，用來存儲 Git 版本控制所需的所有數據。

      git init  

## 查看當前工作目錄的狀態。  
這個命令會顯示哪些文件被修改過但尚未添加到暫存區，哪些文件已經添加到暫存區但尚未提交，以及當前分支的狀態等信息。  

      git status  

## 將當前目錄下的所有修改過的文件添加到暫存區。  
"." 代表當前目錄，所以這將添加資料夾中所有文件的變更。如果你只想添加特定文件，可以使用文件名替換"."。  

      git add .  

## 將暫存區中的修改提交到本地存儲庫。  
引號內的文字是本次提交的說明，用來描述這次提交的變更內容。  

      git commit -m " "  

## 顯示本地存儲庫的提交日誌。  
這個命令會列出所有的提交記錄，包括每個提交的哈希值、作者、日期、提交說明等信息。  

      git log  

## 將遠端存儲庫的 URL 添加到本地存儲庫中。  
origin 是一個慣例性的名稱，用來表示遠端存儲庫的別名。  

      git remote add origin <URL>  

## 將本地的 master 分支推送到名為 origin 的遠端存儲庫。  
這個命令會將本地的最新修改推送到遠端存儲庫的 master 分支，使兩者保持同步。  

      git push origin master  
