# practice-git
```javascript
#創建README.md
echo "# test" >> README.md

#把這個專案變成一個Git可以管理的倉庫
git init  

#把專案下的檔案新增到倉庫
git add  

#把檔案提交到倉庫
git commit -m "first version"

#將本地倉庫關聯到GitHub上
git remote add origin https://github.com/****/*******.git

#將程式碼上傳到GitHub上
git push -u origin master

### if first time

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
