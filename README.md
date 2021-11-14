自我學習使用github

建立git倉庫:

git init


Git的操作與檔案狀態:

git config --global user.name "FIRST_NAME LAST_NAME"
git config --global user.email "MY_NAME@example.com"

git status
git log
git add . 
git commit -m 'message'

檢視遠端資料夾(repo)

git remote -v

輸入後應該要看到

origin  https://github.com/linbeta/team_cv_cowork.git (fetch)
origin  https://github.com/linbeta/team_cv_cowork.git (push)

設定遠端資料夾 一開始會沒東西，把剛剛新建好的頁面其中一行指令貼下來進行設定

git remote add origin https://github.com/你的網址-請自行修改.git

把本地端的資料推到GitHub上面
推上遠端的指令 (備註，master的地方打你本地端的分支名稱，可能是main 或其他分支名)

git push origin mster
