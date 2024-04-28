## 該文件為測試上傳到git的方法

git init  
git status  
git add .  <!-- 這個.視為該層所有檔案 -->  
git status  
git commits -m " "  <!-- 引號內可填寫此次變更的原因 -->  
git log  
git remote add origin http://  
git remote  
git push origin master  

## 當你對本地的文件進行了修改後，想要將這些修改上傳到 GitHub 時，你需要執行以下步驟：  

1.首先，你需要將修改後的文件加入到暫存區中。你可以使用以下命令將 README.md 文件加入到暫存區：  
git add README.md  
2.接著，你需要提交這些修改到本地存儲庫。你可以使用以下命令提交：  
git commit -m "Update README.md"  
3.現在，你已經將修改提交到本地存儲庫，但是還沒有推送到遠端。為了將這些修改推送到遠端，你可以執行以下命令：  
git push origin master  
4.這樣就完成了將你對 README.md 文件的修改推送到 GitHub 的遠端存儲庫中。請記得在執行推送操作之前，確保你已經提交了所有的變更到本地存儲庫中。  

<p align="center">
  <img src="https://github.com/xuexiahanmei/test/blob/master/doc/pic/docpic1.png" width="550">
</p>