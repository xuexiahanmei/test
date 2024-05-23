# GitHub上傳步驟

要上傳一個資料夾到GitHub，你需要遵循以下步驟：

### 1.在你的電腦上安裝Git：
如果你還沒有安裝Git，你需要先在你的電腦上安裝Git。你可以在[Git官方網站](https://git-scm.com/)上找到相應的安裝指南。

### 2.建立一個新的GitHub存儲庫：
在GitHub上建立一個新的存儲庫，這是你要上傳資料夾的地方。你可以在GitHub網站上的首頁上找到「New」按鈕來創建新存儲庫。

### 3.在本地設置Git：
打開命令行或終端並導航到你的資料夾所在的位置。執行以下命令，將資料夾初始化為一個Git存儲庫：

```xml
git init
```
### 4.添加資料夾中的文件到Git：
使用以下命令將資料夾中的所有文件添加到暫存區：

```xml
git add .
```
這將添加資料夾中所有文件的變更。如果你只想添加特定文件，可以使用文件名替換"."。

### 5.提交變更：
執行以下命令提交你所做的變更：

```xml
git commit -m "Initial commit"
```

### 6.連接到GitHub存儲庫：
將本地存儲庫與在步驟2中創建的GitHub存儲庫關聯起來。在GitHub存儲庫頁面上找到適當的遠端URL，然後在終端中執行以下命令：

```xml
git remote add origin <GitHub存儲庫的URL>
```
### 7.推送到GitHub：
最後，執行以下命令將本地分支的變更推送到GitHub存儲庫：

```xml
git push -u origin master
```
現在，你的資料夾及其內容應該已經成功上傳到GitHub存儲庫中了！

# 二次修改

當你對本地的文件進行了修改後，想要將這些修改上傳到 GitHub 時，你需要執行以下步驟：

### 1.檢查倉庫狀況：
確任倉庫修改了哪些東西：

```xml
git status
```

### 2.添加資料夾中的文件到Git：
你需要將修改後的文件加入到暫存區中：

```xml
git add README.md
```

### 3.提交變更：
你需要提交這些修改到本地存儲庫：

```xml
git commit -m "Update README.md"
```
### 4.推送到GitHub：
現在，你已經將修改提交到本地存儲庫，但是還沒有推送到遠端。為了將這些修改推送到遠端，你可以執行以下命令：

```xml
git push origin master
```
### 5.這樣就完成了將你對 README.md 文件的修改推送到 GitHub 的遠端存儲庫中。

<p align="center">
  <img src="https://github.com/xuexiahanmei/test/blob/master/doc/pic/docpic1.png" width="550">
</p>